---
layout: splash
title:  "My Internship experience @ Space Applications Services"
categories : [Robotics]
excerpt: "6 months internship (2023)"
read_time: false

header: 
  overlay_image: /assets/images/intern_sas/banner.png
  show_overlay_excerpt : true

---

I've always been attracted by the Space in general, and found space exploration attracting. I love the challenges of  having reliable and smart systems that can explore the rest of the universe.
My internship at Space Apps was great, I had the chance to spend 6 months as an intern withing a dynamic and great team that let me took responsibilities, like a real engineer. I worked on two inspiring and challenging projects that significantly enhanced my resilience, teamwork, and ability to build robust systems.

## **Project 1: EMRS** 

**EMRS** (ESA’s program “European Moon Rover System (EMRS)” is the first iteration of a European mobile robotic platformexpected to operate on the Moon surface by 2030.

I could contributed to the assembly, control and software development. I found it really engaging to be able to touch any aspects of the project and seeing the rover integration progression was exciting.

Some of the things I completed myself:
- Integration and routing: Placing, testing, agencing components, handling multiple power sources, soldering, hooking etc... Sometimes quite tedious, but the result was really amazing. This was also usefull in understanding how the software should interact with the hardware, and how different components are interconnected and work together.

- PCB design: My first actual PCB designed used in industry 🎉 Well, it was more like a power re-distribution board, pretty quick to design, but I could leverage some of the skills developed in the PCB class.

- Development of 6 locomotion modes using ROS2: This was the most fascinating part of this project, where I ran into complex geometric computations. Basically, based on the controller input, I developed six different locomotion modes for the rover: Differential Drive, Ackermann, Skid Steering, Double Ackermann, Crabbing (pure translation), and Point Turn (pure rotation). This experience significantly enhanced my understanding of robotic movement and control systems.

If you want to learn more about it: 
**Source:** (PDF) European Moon Rover System (EMRS). Available from: https://www.researchgate.net/publication/374373530_European_Moon_Rover_System_EMRS)


## **Project 2: X-aRm** 

**X-aRm**, a Force-Feedback Device to Train Future Astronauts with eXtended Realities.

This innovative project aims to provide a highly immersive and interactive training environment, where astronauts can practise their skills in 0 gravity object manipulation. 

For this project, I felt really trusted by the team, and had a truely enriching experience to tune, develop and deliver the project. Here is what I technically worked on: 

- Admittance Control Loop Development and Tuning: I worked on designing and refining the admittance control loop, which was a crucial component of the force-feedback system. This involved extensive testing and iteration to achieve optimal performance. It was very interesting to also look at the current literature methods to try different things, such as arm calibration methods, or small parameters adjustments that actually generates real feeling difference.

- Communication with VR Simulation: It was one of the most critical part of the system: real-time communication with the 3D simulation engines, that replicates the position of the arm state in the virtual environment. I worked inverse kinematics computation to compute the current arm state, and then packed it up into protobuf objects. 

- Web Interface Development and Dockerization: I also worked on deploying and modifying a web interface to monitor the system status. A large state machine had to be set up to handle multiple events and ensure the system was safe to use.

Learn more: 
**Source:** https://nebula.esa.int/content/x-arm-force-feedback-device-train-future-astronauts-extended-realities

</style>