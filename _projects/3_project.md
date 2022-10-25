---
layout: page
title: SCAN Continuum Robot
description: Steerable Cross-axis Notched (SCAN) Continuum Manipulator
img: assets/img/robots/scan.png
importance: 3
category: work
---


### Abstract

This paper developed a Steerable Cross-axis Notched (SCAN) continuum manipulator based on Cylindrical Cross-axis Flexural Pivots (CCAFP). The design aims to address the trade-off between notched-tube compliant joints’ range of motion and stiffness by integrating asymmetric cross-axis notch to the manipulator. Two pairs of cross-tiled beams are arranged at each joint section as the flexural member. The increased length of bending members and parallel flexures pairs could enlarge the range of motion within the constraint of ultimate strain and ensure the stiffness.The static model for single and multiple flexural joint sections is built to investigate the bending characteristic of the developed continuum manipulator. The Finite Element Analysis (FEA) is conducted to validate the static model and quantify the superiority of the proposed manipulator in bending angle and strain distribution compared with rectangular notched design.The model verification experiments and stiffness testing experiments are carried out to demonstrate that the developed continuum manipulator could bend to 172◦ by 7 N-acutation force.




<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    </div>
    <div class="col-sm mt-7 mt-md-0">
        {% include figure.html path="assets/img/robots/scan/design.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>


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
