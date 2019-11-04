# CPSC 334 - Creative Embedded Systems

## Module 4 Task 2: Kinetic Sculpture

### Table of contents

- [CPSC 334 - Creative Embedded Systems](#cpsc-334---creative-embedded-systems)
  - [Module 4 Task 2: Kinetic Sculpture](#module-4-task-2-kinetic-sculpture)
    - [Table of contents](#table-of-contents)
      - [Video demo](#video-demo)
      - [Requirements](#requirements)
      - [Goals & vision](#goals--vision)
      - [Iteration](#iteration)
      - [Technical challenges](#technical-challenges)
      - [Laser cutting the Moire mask](#laser-cutting-the-moire-mask)
        - [Quality of Moire effect](#quality-of-moire-effect)
      - [Schematic](#schematic)

#### Video demo

Link is here: <https://youtu.be/fooL-Xw-Lkg>

#### Requirements

- [x] You must use a minimum of (2* number of group members) motors and may use as many motors as you have available to your group
- [x] The device must have an enclosure or enclosures
- [x] The device must be safe to operate over long periods of time. For instance, if you have continuous motion, you should **provide a switch** that allows a user to switch off the actuators
- [x] The device utilizes actuators
- [x] Reuses previous sensors, **config code**, **design principles**

#### Goals & vision



#### Iteration


#### Technical challenges

#### Laser cutting the Moire mask

The masks we created are for the radial Moire effect. We cut them with a laser cutter. But because the spokes are so fine, they are prone to breaking very easily. We experimented with a number of materials for the right combination of weight and durability. 

We started with cardboard, but the extremely fine ends of the spokes would crumble when touched. At that point, we contemplated either scaling up the design (which would also require changes to all our printed animations), or trying other materials.

We next used wood, which best met our needs, and was easy to paint black to increase contrast with the animation. We also cut a mask in acrylic, but it proved to be difficult to paint, and required multiple rounds of rough sanding and coats of acrylic paint.

##### Quality of Moire effect

The final display does incorporate the Moire effect, which leads to the aliasing in spinning wheels (the eyes). However, we encountered a number of challenges:

1. The wheels we laser cut had extremely delicate and thin spokes, which were prone to breaking.


Despite that, the slits were not wide enough for observers to comprehend the animation through them. 




  - Small slits
  - 
  - Low light
  - Type of animation
- ESP32 support of multiple steppers

#### Schematic

![Schematic](./docs/schematic_bb.png)