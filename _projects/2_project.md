---
layout: page
title: Bach
description: Belt-Augmented Compliant Hand with active 
img: assets/img/robots/bach.jpg
importance: 2
category: work
---

### Abstract

In this work, we developed BACH (Belt–Augmented Compliant Hand), a compliant robotic hand
equipped with active surfaces. The hand can securely grasp an object using power grasp and simultaneously manipulate the grasped object. The hand consists of three identical fingers,
each with an actuated timing belt wrapped around a Fin Ray based compliant finger backbone. Each finger is mounted on a compliant pivot joint allowing for further adaptability. The combination of compliant mechanisms and active surfaces allows the hand to perform dexterous in-hand manipulation with great robustness. Multiple analyses were conducted to optimize and validate the design of BACH. The hand was experimentally tested for grasping and manipulating objects
of various geometries and sizes, and it demonstrated highly robust and efficient robust in-hand manipulation capabilities.

### Design

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/design.jpg" title="Design of the Robotic Hand" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A CAD model of the BACH: (a) An illustration of the BACH mounted on a UR5 robot. (b) An exploded view of the palm. (c) An exploded view of the finger with active surface. (d) Compliant grasping of the finger. (e) Adaptive pivot joints.
</div>

### Analysis

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/analysis.gif" title="analysis image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/rotcenter.jpg" title="rotcenter image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Analysis
</div>


    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
