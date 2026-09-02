---
layout: page
title: Real-time Breath Monitoring through Smart Fashion
description: A real-time breath monitoring smart necklace to detect sleep apnea and hyperventilation using ESP32C3 and accelerometer with up to 75% accuracy.
img: assets/img/projects/5 breath/IMG_7119.JPG
# redirect: https://www.wikipedia.org/
importance: 1
category: UG & iArt
---

## Project Overview

This was my **undergraduate final-year project**, advised by **Prof. Lina Mohjazi**.

I developed a smart necklace for real-time respiratory monitoring by combining embedded sensing and signal processing. The system uses a **Seeed XIAO ESP32-C3** and an **MMA8451 accelerometer** to estimate breathing rate, detect abnormal breathing events such as hyperventilation and apnea, and send email alerts for notification.

The project received the **2023 Outstanding Dissertation Award (College-level)**.

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
          Independent Researcher<br>
          Hardware Developer<br>
          Signal Processing
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Hardware</strong></h5>
        <p class="card-text">
          Seeed XIAO ESP32-C3<br>
          MMA8451 Accelerometer<br>
          Custom Wearable Form Factor
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Skills</strong></h5>
        <p class="card-text">
          Arduino IDE<br>
          MATLAB<br>
          Circuit Design<br>
          Signal Processing
        </p>
      </div>
    </div>
  </div>

</div>

## System Design

<div class="row justify-content-sm-center">
  <div class="col-sm-9 mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/projects/5 breath/Design.png"
      title="Hardware and software integration for the smart breathing-monitoring necklace"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>

<div class="caption">
Hardware and software architecture of the wearable breathing-monitoring system.
</div>

## Poster

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    <iframe
      src="{{ '/assets/img/projects/5 breath/FYP_Poster_Mingzhuo_Ma.pdf' | relative_url }}"
      width="100%"
      height="900"
      style="border: none;"
      class="rounded z-depth-1">
    </iframe>
  </div>
</div>

<div class="caption">
Undergraduate final-year project poster.
</div>