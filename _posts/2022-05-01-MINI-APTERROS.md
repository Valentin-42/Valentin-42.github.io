---
layout: splash
title:  "MINI-APTERROS"
excerpt: "Realized in 2022. <br> **Reusable rocket launcher demonstrator.**"
read_time: false

header: 
  overlay_image:  /assets/images/MINI-APTERROS/header.jpg
  show_overlay_excerpt : true
  caption: "Photo credit: [**T. Pesquet**](https://twitter.com/thom_astro/status/1397622938078167044)"
  overlay_filter : 0.2
categories : 
  - Robotics
  - System Control

---

# About

**MINI-APTERROS** (**A**dvanced **P**ropulsion **T**echnology for **Re**ussible **R**ocket and **O**perating **S**ystem) is a technology demonstrator for a new generation of reusable launch vehicles being developed by CNES (French Space Agency) in collaboration with some universities. 

The project aims to develop new technologies for vertical landing and reusability of rockets and booster. Our team was composed of 8 people splitted in the 4 following pairs :
 * Integration and PCB design
 * Altitude control
 * Orientation control
 * Motors study 

I worked in the Orientation control team and proposed a mecanical system to orient the boosters to balance the rocket during flights.



# Video

{% include video id="cH4shGK4SWk" provider="youtube" %}

# Gallery

<div class="gallery" style="margin-top:60px; margin-bottom:60px;">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/images/MINI-APTERROS/gallery' %}
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