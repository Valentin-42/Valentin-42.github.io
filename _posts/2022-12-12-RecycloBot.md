---
layout: splash
title:  "RecycloBot"
excerpt: "Realized in 2022. <br> **A Robot collecting empty cans.**"
read_time: false

categories : 
  - Robotics
  - Deep Learning
  - Reinforcement learning

header: 
  overlay_image: /assets/images/RecycloBot/header.png
  show_overlay_excerpt : true
  overlay_filter : 0.1
---


# About 
   
We participated in a 3-month school challenge aimed at developing a robot capable of collecting empty cans from a table and placing them in a specific area. To accomplish this, we undertook a number of tasks including 3D printing the robot's structure, creating the PCB, integrating sensors, developing firmware using FreeRTOS, and integrating all components. To achieve the high-level task of picking up and moving the cans, we utilized reinforcement learning and trained a neural network using a combination of X-Cube-AI and Unity3D ml-agent package.


# Training 

![Generations ](/assets/images/RecycloBot/generations.gif)


# Gallery

<div class="gallery" style="margin-top:60px; margin-bottom:60px;">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/images/RecycloBot/gallery' %}
      <div class="gallery-item">
        <a href="{{ image.path }}" data-lightbox="gallery">
          <img src="{{ image.path }}" alt="{{ image.name }}" style="max-width:100%; max-height:100%; border-radius: 10px;">
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
  /* min-width: 100%; */
  /* min-height: 100%; */
  max-width: 100%;
  /* height: 300px; */
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


# Slide


<div style="text-align:center;">
  <a href="https://docs.google.com/presentation/d/1Ua8Yso0nb4UkJnpigyOGkqx0J10J4MU-0cG9D3aCUOo/edit?usp=sharing" download class="btn btn-primary" style="border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);">Open in Google Slides</a>
</div>


<div style="text-align:center; margin-top:80px; margin-bottom:80px; height:100vh; ">
  <iframe src="https://docs.google.com/presentation/d/1Ua8Yso0nb4UkJnpigyOGkqx0J10J4MU-0cG9D3aCUOo/edit?usp=sharing" style="width:70%; height:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>