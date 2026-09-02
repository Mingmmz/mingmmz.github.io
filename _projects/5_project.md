---
layout: page
title: Five Notes
description: An interactive music game promoting a traditional Chinese musical instrument “Bian Zhong (Chime)” through hand movements recognization with Leapmotion (Kinect for initial design), ESP8266 and an accelerometer with gyroscope (2022)
img: assets/img/projects/3 five-notes/IMG_7061.JPG
importance: 4
category: UG & iArt
---

## Project Overview

**Five Notes** is an interactive music game designed to introduce and reinterpret the traditional Chinese musical instrument **Bianzhong (chime bells)** through embodied interaction, sound, and generative visuals.

The project combines embedded sensing, motion-based interaction, and audiovisual design to create a playful experience centered around the ancient Chinese pentatonic scale.

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
        <h5 class="card-title"><strong>Concept</strong></h5>
        <p class="card-text">
          Traditional Chinese Music<br>
          Embodied Interaction<br>
          Interactive Art
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Interaction</strong></h5>
        <p class="card-text">
          Motion Sensing<br>
          Gesture-based Control<br>
          Audiovisual Feedback
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Tools</strong></h5>
        <p class="card-text">
          ESP8266<br>
          IMU / Gyroscope<br>
          TouchDesigner<br>
          After Effects
        </p>
      </div>
    </div>
  </div>

</div>

## Project Description

The interaction is built around an **ESP8266-based embedded system** with motion sensing. A gyroscope continuously estimates the orientation and movement of a wine glass, allowing the player's gestures to control musical and visual elements in real time.

The visual environment was created using **TouchDesigner** and **Adobe After Effects**. Rather than following the conventional rhythm-based mechanics of many music games, *Five Notes* emphasizes relaxed, exploratory, and personalized interaction. Players are encouraged to improvise freely through movement, sound, and visual feedback.

To make the experience accessible to people without formal musical training, the interaction is based on the traditional Chinese pentatonic scale:

**Gong · Shang · Jue · Zhi · Yu**

Using only five tones simplifies the musical structure while maintaining a connection to traditional Chinese musical culture.

The use of chime bells as the musical medium is intended to evoke the resonant and lingering character of traditional Bianzhong performances. Gesture-based interaction recreates a sense of freely shaping sound through movement, while the wine glass serves as a playful physical interface inspired by scenes of traditional Chinese banquets and social gatherings.

## Illustration Video

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    <div
      style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;"
      class="rounded z-depth-1"
    >
      <iframe
        src="https://www.youtube.com/embed/l4BTRSXslo8"
        title="Five Notes Illustration Video"
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>
  </div>
</div>

<div class="caption">
Illustration and demonstration of the Five Notes interactive music experience.
</div>

## System Design

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/projects/3 five-notes/schematic.jpg"
      title="Five Notes system schematic"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>

<div class="caption">
System schematic showing the embedded sensing and audiovisual interaction pipeline.
</div>