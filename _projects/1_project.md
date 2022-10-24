---
layout: page
title: Medical Snake
description: A tendon-driven highly articulated surgical robot probe
img: assets/img/robots/medsnake.jpg
importance: 1
category: work
---


<iframe src="https://player.vimeo.com/video/763459276?h=8d87847fa6&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" width="810" height="540" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen title="demo3.mp4"></iframe>


### Statics Modeling of Discrete Joint Surgical Probes with Tendon-based Stiffening

Prior works have shown that follow-the-leader motion in surgical manipulators can be achieved using two concentric tendon-driven segments that can independently lock their shape, and alternating between locking and advancing each segment. By varying the tendon tension, such manipulators can be both flexible during insertion for safe access and stiff during manipulation for operation precision and high payload capacity.
However, 3D kinetostatics modeling and the variable stiffness properties of this class of manipulators have not been fully investigated. One challenge in modeling these manipulators is the intentionally introduced friction within the structure that enables follow-the-leader motion and variable stiffness. This paper presents a kinetostatic model that includes the effect of link-to-link friction as well as the external load. This model provides a prediction of the maximum admissible external load on the manipulator, which can be used at the design stage to size mechanical and actuation components given a maximum required surgical task load. We also investigate how the stiffness is influenced by the shape of the manipulator. We validate the model experimentally on a prototype surgical manipulator, showing that our model can predict the maximum permissible load to within 15%. We believe this kinetostatic model lays the groundwork for future design, control, and planning methods with this class of surgical manipulator.
    

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
