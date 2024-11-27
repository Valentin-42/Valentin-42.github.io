---
layout: splash
title:  "BBS : BlackBoxSeeker"
excerpt: " Completed in 2020. <br> An Autonomous Search and Recovery Vessel."
read_time: false

header: 
  overlay_image:
  show_overlay_excerpt : true
categories : 
  - Robotics
  - Prototype

---

# Project description

**! My first ever side- project !** 😎

The idea was to create an autonomous mini-boat from scratch. Most of my components came from Amamzon or Aliexpress or old piece of motors I found.
I asembled a small prototyped with a GPS, a compass, and a large Arduino (I still don't know why I chose the ATM Mega, looks a bit overkill now that I see it 😆).

The rest was mostly developing and testing a basic navigation algorithm on Arduino:
- I set up some key point where the boat should go. 
- The motor would react linearly to the the remaining distance, and stop for 3 seconds at each key-point. 
- The GPS was used to compute the distance to each keypoint.
- The compass was providing the direction to go, orienting the servo-motors controlling the rudder direction.


**Pictures Comming Soon! (they are quite old)**

I remember having issues as I first placed the compass inside the boat, next to the motor and GPS which were creating a magnetic field that was affecting the compass measurement.
That's why I decided to move to the front of the boat.


