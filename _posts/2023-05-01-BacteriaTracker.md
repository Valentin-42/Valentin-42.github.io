---
layout: splash
title:  "Bacteria Tracker"
categories : [Computer Vision]
read_time: false
excerpt: "Completed in 2023 for micro-biologists. <br> **YOLO-based solution to track bacteria in videos**"


header: 
  overlay_image:  /assets/images/BacteriaTracker/header.jpg
  show_overlay_excerpt : true
  actions:
    - label: "Github"
      url: "https://github.com/Valentin-42/bacteria_tracker"

---

# About 

This project takes place in the context of a collaboration with the microbiologists with whom we are intending to develop a pipeline to detect and track bacteria attaching themselves on a glass substrate. In this experimental setup, a flow of water loaded with bio-luminescent bacteria is passing a glass substrate while being imaged with a microscope at 0.5Hz. Some bacteria attach to the surface, sometimes detaching after some time. The objective of the project is to build a detector and tracker to follow these events and provide statistics on the adherence properties of the bacteria in various conditions, as a function of their angles with respect to the flow in particular.

# Procedure

We started with a set of 500 images and applied a basic green threshold to quickly create a preliminary dataset. With this dataset, we trained a small YOLOv5 model. We then used Model Assisted Labeling on Labelbox to further refine our model. We incorporated a Kalman filter and bounding box overlap matching step for tracking, including orientation. Finally, we saved all metadata to CSV files and used Pandas to build statistics.

# Skills developped

✅ Object detection <br>
✅ Pytorch <br>
✅ Datasets creation, Data Analysis <br>
✅ MAL <br>
✅ Communication <br>

# Slides / Report

<div style="text-align:center;">
  <a href="https://docs.google.com/presentation/d/1IzDbCYl1f1OtAy6J5RWzvNzrpVyTDHdpT4xsQvKNCBk/edit?usp=sharing" download class="btn btn-primary" style="border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);">Open in Google Slides</a>
</div>


<div style="text-align:center; margin-top:80px; margin-bottom:80px; height:100vh; ">
  <iframe src="https://docs.google.com/presentation/d/1IzDbCYl1f1OtAy6J5RWzvNzrpVyTDHdpT4xsQvKNCBk/edit?usp=sharing" style="width:70%; height:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>