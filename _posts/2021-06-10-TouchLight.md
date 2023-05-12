---
layout: splash
title:  "TouchLight: Interactive Illumination Effects"
excerpt: "Realized in 2021. <br> **VHDL school Project**"
read_time: false

header: 
  overlay_image: "/assets/images/TouchLight/header.jpg"
  show_overlay_excerpt : true
  overlay_filter : 0.2

categories : 
  - VHDL
  - NeoPixel

---

# Project description 

This 3 months project involves controlling the color of one or more LEDs based on the position of a finger on a resistive touch screen. The project was implemented using a neopixel and a touch screen box that includes a resistive touch surface, a display, and an ADC. A Basys 3 board was also used. The report below includes sections on the implementation of the neopixel, integration of the touch screen, display of colors on the neopixel along the X axis, mode Y, and additional information in the annexes.

# PDF Report 

<div style="text-align:center;">
  <a href="/assets/images/TouchLight/project_report.pdf" download class="btn btn-primary" style="border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);">Download PDF</a>
</div>

<div style="text-align:center; margin-top:80px; margin-bottom:80px;">
  <iframe src="/assets/images/TouchLight/project_report.pdf" style="width:70%; min-height:100vw; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);" frameborder="0"></iframe>
</div>





# Gallery

<div class="gallery" style="margin-top:60px; margin-bottom:60px;">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/images/TouchLight/gallery' %}
      <div class="gallery-item" style="box-shadow: 2px 2px 5px rgba(0,0,0,0.3);">
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
  min-width: 100%;
  min-height: 100%;
  max-width: 100%;
  height: 300px;
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


# Slides

Here is our Google Slides presentation :

<div style="text-align:center;">
  <a href="https://docs.google.com/presentation/d/1u-xUvSW6nCS6rS0w4zPCPsZCQlNiDVicjZBKPYF13Pg/edit?usp=sharing" download class="btn btn-primary" style="border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);">Open in Google Slides</a>
</div>

<div style="text-align:center; margin-top:80px; margin-bottom:80px; height:100vw; ">
  <iframe src="https://docs.google.com/presentation/d/1u-xUvSW6nCS6rS0w4zPCPsZCQlNiDVicjZBKPYF13Pg/edit?usp=sharing" style="width:70%; height:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>


   