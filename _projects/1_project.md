---
layout: page
title: LunarLink
description: A Sickle Cell Disease Patient/Provider Match Tool for SCD patients to find their best-matched providers and get support from online communities (2024)
img: assets/img/SCD-cover.JPG
importance: 1
category: MS
related_publications: false
---

## Project Overview

This is an **EE598 Capstone Project with Novo Nordisk** to develop a software platform for sickle cell disease (SCD) patients to find their best-matched healthcare providers and receive support from online communities.

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
          Project Lead & PoC<br>
          UX/UI Designer<br>
          ML Engineer
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Team</strong></h5>
        <p class="card-text">
          Mingzhuo Ma<br>
          Mo Kahil<br>
          Jason Tran<br>
          Jingxian Chen<br>
          Bowen Shu<br>
          Chengyuan Guo<br>
          Yangyang Wu
        </p>
      </div>
    </div>
  </div>

  <div class="col-sm-4 mt-3 mt-md-0">
    <div class="card h-100 project-overview-card">
      <div class="card-body">
        <h5 class="card-title"><strong>Skills</strong></h5>
        <p class="card-text">
          Figma<br>
          UX/UI Design<br>
          Python<br>
          Recommender Systems
        </p>
      </div>
    </div>
  </div>

</div>

---

## Software Interaction Demo

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    <video controls class="w-100 rounded z-depth-1">
      <source src="{{ '/assets/img/projects/scd/SCD-demo.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

<div class="caption">
Software interaction demo of the SCD patient-provider matching platform.
</div>

---

## Presentation Video

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    <video controls class="w-100 rounded z-depth-1">
      <source src="{{ '/assets/img/projects/scd/SCD-video.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

<div class="caption">
Project presentation introducing the motivation, system design, and implementation.
</div>

---

## Poster

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    <iframe
      src="{{ '/assets/img/projects/scd/2024 ENGINE Showcase Horizontal Poster.pdf' | relative_url }}"
      width="100%"
      height="500px"
      style="border: none;"
      class="rounded z-depth-1">
    </iframe>
  </div>
</div>

<div class="caption">
Poster presented at the 2024 UW ENGINE Showcase.
</div>

---

## 2024 UW ENGINE Showcase

<div class="row justify-content-sm-center">
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/projects/scd/20240529_050326000_iOS.jpg"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/projects/scd/20240529_051742256_iOS.jpg"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>

<div class="caption">
Presenting the SCD Patient/Provider Match Tool at the 2024 UW ENGINE Showcase.
</div>



<!-- 
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %} -->
