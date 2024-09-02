```dataviewjs

dv.span("** Research **")

const calendarData = {
    year: 2024, // optional, remove this line to autoswitch year
    colors: {
        purple: ["#e063ff","#c722f0","#a414c7","#7e0e99","#620878",]
    },
    entries: []
}

for(let page of dv.pages('"Calendar Todo Lists"').where(p=>p.research)){
    calendarData.entries.push({
        date: page.file.name,
        intensity: page.research,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })
       
}

renderHeatmapCalendar(this.container, calendarData)

```

```dataviewjs

dv.span("** USACO **")

const calendarData = {
    year: 2024, // optional, remove this line to autoswitch year
    colors: {
        blue: ["#757bff","#4148fa","#2229e6","#0a0f94","#070b69",]
    },
    entries: []
}

for(let page of dv.pages('"Calendar Todo Lists"').where(p=>p.usaco)){
    calendarData.entries.push({
        date: page.file.name,
        intensity: page.usaco,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })
       
}

renderHeatmapCalendar(this.container, calendarData)

```

```dataviewjs

dv.span("** Startup **")

const calendarData = {
    colors: {
        green: ["#91ffae","#5cfa86","#2cc755","#1d8a3a","#135425",]
    },
    entries: []
}

for(let page of dv.pages('"Calendar Todo Lists"').where(p=>p.startup)){
    calendarData.entries.push({
        date: page.file.name,
        intensity: page.startup,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })
       
}

renderHeatmapCalendar(this.container, calendarData)

```

```dataviewjs

dv.span("** Encode Justice **")

const calendarData = {
    year: 2024, // optional, remove this line to autoswitch year
    colors: {
        purple: ["#ffadad","#f74d4d","#f71616","#a30303","#5e0101",]
    },
    entries: []
}

for(let page of dv.pages('"Calendar Todo Lists"').where(p=>p.encode_justice)){
    calendarData.entries.push({
        date: page.file.name,
        intensity: page.encode_justice,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })
       
}

renderHeatmapCalendar(this.container, calendarData)

```



