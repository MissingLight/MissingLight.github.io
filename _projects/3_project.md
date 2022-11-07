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

### Design

<div class="row">
    <div class="col-sm-2">
    </div> 
    <div class="col-sm-8">
        {% include figure.html path="assets/img/robots/scan/design.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm-2">
    </div> 
</div>

### Analysis
<div class="row">
    <div class="col-sm-5">
        {% include figure.html path="assets/img/robots/scan/fem_demo.gif" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm-7">
        {% include figure.html path="assets/img/robots/scan/fem.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
</div>


### Results
<div class="row">
    <div class="col-sm-1">
    </div> 
    <div class="col-sm-10">
        {% include figure.html path="assets/img/robots/scan/demo.gif" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm-2">
    </div> 
</div>

The bending images of the manipulator from 1-4 N are shown below. The calibrated friction coefficient and Young’s modulus are 0.08 and 67 GPa, respectively. It demonstrates the model estimation results and the experimental results. The mean tip error is 0.41 ± 0.24 mm and its normalization with the total flexible length of the manipulator (38 mm) is 1.074%±0.064%. The max bending angle could reach 172◦ with cable tension about 7 N. 

The increased length of bending members and parallel flexures pairs in each joint could enlarge the range of motion within the constraint of ultimate strain and ensure stiffness. The main contribution is that we integrate the CCAFP into a notched-tube compliant mechanism to solve the trade-off between the range of motion and stiffness, thus making the SCAN manipulator suitable for hard-to-reach lumen accessing and precise tissue manipulation.

<div class="row">
    <div class="col-sm-2">
    </div> 
    <div class="col-sm-8">
        {% include figure.html path="assets/img/robots/scan/results.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm-2">
    </div> 
</div>