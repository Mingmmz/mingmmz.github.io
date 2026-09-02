---
layout: page
title: Multifunctional Robot Design (UESTC-UoGJEP Creative Lab)
description: A smart car for tracking, crossing bridge, and transporting a ball to a target location by Autonomous Control Design and ML Coding.								
img: assets/img/projects/4 smart-car/IMG_7064.JPG
importance: 2
category: UG & iArt
---

## Project Overview

This was a **one-year group project** in the UESTC-UoG Joint Educational Program Lab to develop a multifunctional smart car capable of line tracking, bridge crossing, and transporting a ball to a target location through autonomous control and computer vision.

I was primarily responsible for the **computer vision and tracking module**, using an OpenMV camera and Canny edge detection to estimate the road direction and support autonomous steering.

<style>
.project-overview-card {
  border: 1px solid var(--global-divider-color);
  border-radius: 8px;
  box-shadow: none;
}

.project-overview-card .card-body {
  padding: 1.25rem;
}

.project-overview-card .card-title {
  margin-bottom: 0.75rem;
  font-size: 1.1rem;
}

.project-overview-card .card-text {
  margin-bottom: 0;
  line-height: 1.7;
}
</style>

<div class="row mt-3 mb-4">

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Role</strong></h5>
        <p class="card-text">
          Computer Vision Developer<br>
          Tracking Algorithm Design<br>
          Embedded Implementation
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>System</strong></h5>
        <p class="card-text">
          Autonomous Smart Car<br>
          OpenMV Camera<br>
          Vision-based Navigation
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Skills</strong></h5>
        <p class="card-text">
          OpenMV<br>
          C Programming<br>
          Computer Vision<br>
          Canny Edge Detection
        </p>
      </div>
    </div>
  </div>

</div>

## Computer Vision Tracking

Our tracking algorithm was based on **Canny edge detection** and window-based image analysis.

The lower region of each image captured by the OpenMV camera was divided into multiple windows of equal area. For each window, the standard deviation of pixel values was calculated to distinguish the road surface from the surrounding environment.

Regions identified as background or surroundings were discarded, while regions classified as part of the road were retained. The center road region was then selected to estimate the desired travel direction.

Based on the estimated road position, a direction line was generated and used by the autonomous controller to determine whether the smart car should **turn left, turn right, or continue straight**. The position of each selected window also corresponded to an approximate steering angle.

## System and Tracking Results

<div class="row justify-content-sm-center">
  <div class="col-sm-5 mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/projects/4 smart-car/5.png"
      title="Multifunctional smart car platform"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm-7 mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/projects/4 smart-car/1.png"
      title="Computer vision tracking result"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>

<div class="caption">
Multifunctional smart car platform and an example of the vision-based road tracking algorithm.
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-5 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/4 smart-car/2.png"
      title="Road detection result"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm-7 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/4 smart-car/3.png"
      title="Road tracking and steering estimation"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>

<div class="caption">
Examples of road-region identification and steering-direction estimation under different driving conditions.
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/4 smart-car/4.png"
      title="Vision-based tracking algorithm result"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>

<div class="caption">
Visualization of the final road-tracking result used for autonomous steering.
</div>