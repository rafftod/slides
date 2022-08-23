---
marp: true
theme: academic
paginate: true
class: lead
footer: "Raffaele Todesco - Master thesis - RVR : A new robot platform for swarm robotics - 2022"
author: Raffaele Todesco
title: "RVR : A new robot platform for swarm robotics"
---

<!-- paginate: false -->
<!-- _class: lead -->
<!-- footer: "" -->

# RVR : A new robot platform for swarm robotics

<br/>

###### Raffaele Todesco

<br/>

---

<!-- header: Table of contents -->
<!-- paginate: true -->
<!-- footer: "Raffaele Todesco - Master thesis - RVR : A new robot platform for swarm robotics - 2022"-->

1. Introduction
2. The Sphero RVR
3. Simulation
4. Control software
5. Experiments
6. Results
7. Conclusion

---

<!-- header: Introduction -->

#### Objectives

-   Design and implement an architecture for swarm robotics development, in order to :
    -   Run virtual experiments with multiple RVRs and design control software within a simulation environment
    -   Transpose the control software to real robot transparently
    -   Build a modular platform, both on the hardware and software sides
-   Evaluate the quality of existing swarm robotics techniques with this platform, notably automatic

---

<!-- header: The Sphero RVR -->

#### The Sphero RVR

-   Differential treaded robot with a large sensor set :

    -   Ground color sensor
    -   IMU (Accelerometer, magnetometer, gyroscope)
    -   Ambient light
    -   Locator (odometry)

-   Extended with proximity sensors and a lidar

---

slide double photos

---
