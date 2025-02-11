---
layout: page
title: APP Controlled 3D Dance Cube
description: We project the 3D form of a person from the live video feed of an Android app into a 8x8x8 LED cube.
img: assets/img/391workflow.PNG
importance: 4
category: software engineering
related_publications:
---

This project includes a 3D 8x8x8 LED cube, connnected and controlled via WIFI by an app. Additionally, besides lighting up cool moving animations in the LED cube, there is an function to use the camera on the phone with a local ML model that does pose eatimation to project the real-time moving shape of the person in the camera frame into the cube in 3D.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dancecube.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/UI.png" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/391ex.PNG" title="example image" class="img-fluid rounded z-depth-1" %}
</div>

<video width="320" height="240" controls>
  <source src="{{ site.baseurl }}/assets/video/41video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
