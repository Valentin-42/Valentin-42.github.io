---
layout: splash
title:  "Internship @ Space Applications Services"
categories : [Robotics]
excerpt: "6 months internship (2023)"
read_time: false

header: 
  overlay_image: /assets/images/intern_sas/banner.png
  show_overlay_excerpt : true

---
# Projects 

**Project 1:** EMRS (ESA’s program “European Moon Rover System (EMRS)” is the first iteration of a European mobile robotic platformexpected to operate on the Moon surface by 2030.

- Integration and routing
- PCB design
- Development of 6 locomotion modes using ROS2: Differential Drive, Ackermann, Skid Steering, Double Ackermann, Crabbing or pure translation, Point Turn or pure rotation. 

**Source:** (PDF) European Moon Rover System (EMRS). Available from: https://www.researchgate.net/publication/374373530_European_Moon_Rover_System_EMRS)

**Project 2:** X-aRm, a Force-Feedback Device to Train Future Astronauts with eXtended Realities.

- Development and tuning of the Admittance Control loop (and a lot of testings !)
- PID Tuning
- Protobuf Communication with VR simulation
- Web interface development and Dockerization

**Source:** https://nebula.esa.int/content/x-arm-force-feedback-device-train-future-astronauts-extended-realities

# Skills developed 

<div class="skill-bar">
    <div class="skill-name">ROS2 Installation and Development</div>
    <div class="bar-container">
        <div class="bar" style="width: 90%;">90%</div>
    </div>
</div>

<div class="skill-bar">
    <div class="skill-name">C++ Multithreading</div>
    <div class="bar-container">
        <div class="bar" style="width: 90%;">90%</div>
    </div>
</div>

<div class="skill-bar">
    <div class="skill-name">Electronics Integration</div>
    <div class="bar-container">
        <div class="bar" style="width: 75%;">75%</div>
    </div>
</div>

<div class="skill-bar">
    <div class="skill-name">Control Theory</div>
    <div class="bar-container">
        <div class="bar" style="width: 60%;">60%</div>
    </div>
</div>

<div class="skill-bar">
    <div class="skill-name">Soldering / Routing / PCB Design / SolidWorks / 3D Printing</div>
    <div class="bar-container">
        <div class="bar" style="width: 50%;">50%</div>
    </div>
</div>

<style>
.skill-bar {
  margin: 20px 0;
}

.skill-name {
  font-weight: bold;
  margin-bottom: 5px;
}

.bar-container {
  background-color: #e0e0e0;
  border-radius: 25px;
  padding: 5px;
}

.bar {
  background-color: #4caf50;
  height: 25px;
  border-radius: 20px;
  line-height: 25px;
  color: white;
  text-align: center;
  width: 0;
  animation: fillBar 2s forwards;
}

@keyframes fillBar {
  from { width: 0; }
  to { width: var(--final-width); } /* Use the inline style for final width */
}
</style>