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
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/analysis.gif" title="analysis image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/rotcenter.jpg" title="rotcenter image" class="img-fluid rounded z-depth-1" %}
    </div>   
</div>
<div class="caption">
    Analysis of the fin ray figner and the adaptive pivot.
</div>

### Results

The compliant finger design and the pivotable fingers allow the hand to grasp objects of different sizes and shapes including a sphere, a long cylinder, an insulated bottle, a box, an irregular pentagon plate, an RC car wheel, and an irregularly shaped puzzle. All of these objects can be grasped with both pinch grasp and power grasp. They can also be securely grasped at different poses, which is the foundation of a stable in-hand manipulation.

<div class="row">
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/result.jpg" title="result image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
    </div>    
</div>
<div class="caption">
    Experimental objects being manipulated by BACH. (Top row left to right: a spherical puzzle, an irregularly shaped puzzle, an insulated bottle, an irregular pentagon shaped bracket; bottom row left to right: an RC car wheel, a long cylinder, a box manipulated by two fingers)
</div>



<div class="row">
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/demo1.gif" title="result image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/demo2.gif" title="result image" class="img-fluid rounded z-depth-1" %}
    </div>
        <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/demo3.gif" title="result image" class="img-fluid rounded z-depth-1" %}
    </div> 
</div>
<div class="row">
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/demo4.gif" title="result image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/demo5.gif" title="result image" class="img-fluid rounded z-depth-1" %}
    </div>
        <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/robots/bach/demo6.gif" title="result image" class="img-fluid rounded z-depth-1" %}
    </div> 
</div>


