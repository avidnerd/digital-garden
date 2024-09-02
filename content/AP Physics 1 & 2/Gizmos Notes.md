---
date:
  - 2024/09/03
subject: ap physics
tags:
  - "#concept-notes"
unit: "1"
---

### Distance-Time and Velocity-Time Graphs


### Free Fall Motion
Objects falling through air are slowed by air resistance. The amount of air resistance on an object is dependent on the about of surface area/contact with air that the object has.

If there is constant acceleration, velocity will increase linearly with time.

If an object falls through the air for a long time, it reaches *terminal velocity*, which means it stops accelerating due to air resistance.

Larger objects have more surface area and more air resistance, resulting in a lower terminal velocity. Objects with higher mass have a larger downward force pushing on them.

$v_{avg} = \dfrac {(v_{initial} + v_{final})} {2}$

$v_{avg} = \dfrac {at} {2}$

### Feed the Monkey (Projectile Motion)
If you wanted to hit a monkey which is falling from a tree with a cannon, you should aim directly at it because they are experiencing the same acceleration (gravity).

In order to calculate the horizontal and vertical components of velocity, multiply $v_{initial}$ by the cosine of the angle and sine of the angle to calculate $v_x$ and $v_y$ , respectively. 

In free fall, the horizontal component does not change as the object moves, but the vertical component does change (because there are no horizontal forces acting upon it, such as wind).

$a = \dfrac{(v_{current} - v_{initial})}{t}$ 
### Vectors 
A *vector* is an object that has magnitude and direction. Examples include:
* displacement
* velocity
* momentum
* acceleration
* force
A *scalar* is different because it has only magnitude- such as speed.

A vector can be described by two components- the i component and the j component. these two components make up **unit vector notation.**

### Atwood Machine
An *Atwood Machine* has two masses connected by a rope that passes over a pulley.

![[Pasted image 20240724215052.png]]


**Gravity** is the force that pulls down the heavier object.

The **net force acting on the system** can be defined as $$9.81M_1 - 9.81M_2$$
The *tension of the rope* is the force that pulls the mass up

#### Primary Equation: $F = ma$

##### What controls the speed of the two weights as they get pulled down/up?
1. The **difference in mass** between the two objects: The larger the difference, the higher the speed. However, the increase in speed becomes smaller and smaller as more mass is added.
2. The **total mass** of the two objects: a smaller total mass results in a faster speed. This is because according to Newton's second law, acceleration is directly proportional to net force and inversely proportional to total mass

Acceleration can be defined as $a = v_{final} / t_{final}$

**If the masses are the same,** an instantaneous force can be applied (they will not accelerate)

#### Pulleys
*A frictional pulley* is one that spins as the rope is pulled over it.

How does the pulley affect the speed of the objects?
* Increasing the mass **decreases** the speed
* Increasing/decreasing has **no effect** on the speed

The acceleration is lower than expected in frictional pulleys because friction **slows down acceleration.**

The **equivalent mass of a pulley** is equal to approximately **half** of its actual mass.

#### Sample Problems

1. What will be the acceleration of an Atwood machine with a frictional pulley with the following mass values? Pulley: 3.6 kg Mass A: 1.4 kg Mass B: 4.1 kg
	 $a = f_{net} / mass$
	 
	 $f_{net} = (4.1 - 1.4) * 9.81 = 26.487 N$
	 
	 $mass = mass_{pulley} + mass_{objects}$
	 $mass_{pulley} = 0.5 * 3.6 = 1.8 kg$
	 
	 $a = 26.487 N / 7.3 = 3.63 m/s^2$


2. In the diagram below, Block 1 has 1.5 times the mass of Block 2. Assume that the pulley is frictionless and that both the rope and pulley are massless. Use $g=9.8\,\dfrac{{m}}{{s}^2}$

![Two masses are connected by a string and pulley. Mass one is represented by a box hanging from the left side of the pulley. Mass two is represented by a smaller box hanging from the right side of the pulley. Mass two hangs farther down than mass one.](https://cdn.kastatic.org/ka-perseus-images/14213177c28d37af9fa058773dd0ca3dd82c9d29.svg)

**Calculate the magnitude of acceleration of the blocks.**  

To write the sum the forces, we need to consider the weight (given by $mg$) and the tension on each block. ***The heavier mass will be pulled down, and tension should be subtracted from the net force.***
$F_{\text{net}_{2}}=m_2g-T$
$F_{\text{net}_{1}}=T-m_1g$

Using Newton's second law, we can rewrite force as the product of mass and acceleration:
$m_2a=m_2g-T$
$m_1a=T-m_1g$

Next, we move tension to one side and set the equations as equal to each other:
$T = m_1a + m_1g$
$T = m_2g - m_2a$

$m_1a + m_1g = m_2g - m_2a$

Next, we isolate $a$:
$m_1a+m_2a=m_2g-m_1g$
$(m_1+m_2)a=m_2g-m_1g$

$a= \dfrac{m_2g-m_1g}{m_1+m_2}$

$m_1 = 1.5m_2$

$a= \dfrac{m_2g-1.5m_2g}{1.5m_2+m_2}$

$a= \dfrac{-0.5m_2g}{2.5m_2}$

$a= \dfrac{-0.5g}{2.5}$

$a=-1.96 \dfrac {m} {s^2}$

### Weight and Mass

*Weight* is the force of gravity on an object. It varies by planet because gravity differs by planet. 

Mass is proportional to gravity because **everything with mass emits tiny particles called gravitons, which are responsible for gravitational attraction**.

On Earth, the gravitational constant is $9.81$ m/sec. 

Mass is absolute because the amount of matter in an object does not change based on gravity.
### Force and Fan Carts

A *force* is something that causes change in motion. 

*Friction* is a force that works against motion as surfaces rub against each other.

Force causes the speed of objects to change. If more force is used, the speed of the cart changes more quickly.

If a surface is frictionless and a  force is applied on it, it will **never stop moving** because of **Newton's first law of motion: An object at rest remains at rest, and an object in motion remains in motion at constant speed and in a straight line unless acted on by an unbalanced force.**

If an object is heavier, the speed will be lower when acted upon by a force
