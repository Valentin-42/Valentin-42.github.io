---
layout: splash
title:  "WiFiWanderer Bot"
categories : [Robotics]
excerpt: "Realized in 2023. <br> A Robotics system Mapping WiFi Signals."
read_time: false

header: 
  overlay_image: /assets/images/WifiWanderer/Occupancy.png
  show_overlay_excerpt : true

---
# Context

Realized as a final 3 weeks project for : CS 7630 Autonomous robotics @ GaTech Europe.

# Scenario 

In this project, we used a TurtleBot, ROS packages, and CoppeliaSim to accomplish the task of localizing the robot and mapping the WiFi signal level of the first floor of our university. Our main objective was to integrate all packages developed during the course, which included:

* Localization with odometry
* Mapping using TurtleBot's Kinect point cloud
* Implementing A* / Dijkstra algorithm to find paths for exploration and obstacle avoidance
* Joystick commands and obstacle prevention based on laser obstacle distances
* Utilizing the autodock package from the TurtleBot repository


# Steps

- **1** Undocking
- **2** Exploring 
- **3** Publishing signal map 

<div class="gallery" style="margin-top:60px; margin-bottom:60px;">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/images/WifiWanderer/gallery' %}
      <div class="gallery-item">
        <a href="{{ image.path }}" data-lightbox="gallery">
          <img src="{{ image.path }}" alt="{{ image.name }}" style="max-width:100%; max-height:100%;border-radius: 10px;">
        </a> 
      </div>
    {% endif %}
  {% endfor %}
</div>

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  grid-gap: 10px;
  justify-content: center;
}

.gallery-item {
  flex: 0 0 calc(25% - 20px);
  margin: 10px;
}

.gallery img {
  min-height: 100%;
  max-width: 100%;
  display: block;
  margin: 0 auto;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.3);
}

@media screen and (max-width: 767px) {
  .gallery-item {
    flex-basis: calc(50% - 20px);
  }
}
</style>


# Report / Slides

<div style="text-align:center;">
  <a href="https://docs.google.com/presentation/d/1Cph7DQELKf_s43IZuK-kRxhRNBna7I4FWuRhe_fuN5s/edit?usp=sharing" download class="btn btn-primary" style="border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);">Open in Google Slides</a>
</div>


<div style="text-align:center; margin-top:80px; margin-bottom:80px; height:100vh; ">
  <iframe src="https://docs.google.com/presentation/d/1Cph7DQELKf_s43IZuK-kRxhRNBna7I4FWuRhe_fuN5s/edit?usp=sharing" style="width:70%; height:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>