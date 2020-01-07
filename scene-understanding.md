---
layout: default
---
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>


# Robotic Vision Scene Understanding Challenge

## Overview
The Robotic Vision Scene Understanding Challenge evaluates how well a robotic vision system can understand the semantic and geometric aspects of its environment.
There will be two tasks in this challenge: *Object-based Semantic Mapping / SLAM*, and *Scene Change Detection*.
<!-- **We are working towards presenting this new challenge in November 2018 during our [workshop](iros2019) at IROS.** -->

Key features of the challenge:
 * The evaluation is run on our evaluation server, and participants will upload their dockerized code to our server. This allows us to keep the test set secret.
 * We will make heavy use of the Nvidia Isaac simulator for this challenge.
 * We will provide a simple API to interface the simulated robot, following the OpenAI Gym API.
 * The best teams are invited to execute their code on a real robot in our lab. This robot can be controlled using the same API as the simulated robot.



**Watch the video below to learn more:**
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/jQPkV29KFvI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>


## Task 1: Object-based Semantic Mapping / SLAM

For this task we evaluate how well participants can build a map of the environment that contains all objects of interest. The evaluation metric rewards accurate pose, shape, and object semantics.

This task can be done in one of two modes (Active or Passive) and two Streams (with or without groundtruth camera pose). In Active mode, the user can control the robot's motion to explore the environment. In Passive mode, the user has no control over the robot. In both modes, the user code has access to the data from the robot's RGB-D camera.


## Task 2: Scene Change Detection
The goal of this task is to identify all objects that disappeared, appeared, or moved in an environment from one day to another. The robot can explore the environment on both days, but has to spot all the differences.

This task can be done in one of two modes (Active or Passive) and two Streams (with or without groundtruth camera pose). In Active mode, the user can control the robot's motion to explore the environment. In Passive mode, the user has no control over the robot. In both modes, the user code has access to the data from the robot's RGB-D camera.

**Watch the videos below** Some objects disappeared, some new objects appeared. Can you spot the differences between both days? Which objects are new, which are gone? Can you write an algorithm to solve this problem?
<table><tr><th>Day 1</th><td><iframe width="560" height="315" src="https://www.youtube.com/embed/68zADNn9zLY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </td></tr>
<tr><th>Day 2</th><td> <iframe width="560" height="315" src="https://www.youtube.com/embed/K4udDOlLKTA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </td></tr></table>



# Organisers, Support, and Acknowledgements



**Stay in touch** and follow us on Twitter for news and announcements: [@robVisChallenge](https://twitter.com/robVisChallenge).

<div class="portrait_row">
<img class="col fith portrait" src="assets/img/niko.jpg"/>  
<img class="col fith portrait" src="assets/img/feras.jpg"/>
<img class="col fith portrait" src="assets/img/david.jpg"/>
<img class="col fith portrait" src="assets/img/haoyang.jpg"/>
</div>
<div class="col fith caption">
      <a href="http://www.nikosuenderhauf.info">Niko Sünderhauf</a><br>Queensland University of Technology
</div>
<div class="col fith caption">
      <a href="http://www.ferasdayoub.com">Feras Dayoub</a> <br>Queensland University of Technology
</div>
<div class="col fith caption">
      <a href="https://sites.google.com/view/davidhallcv/home">David Hall</a> <br>Queensland University of Technology
</div>
<div class="col fith caption">
      <a href="https://staff.qut.edu.au/staff/haoyang.zhang.acrv">Haoyang Zhang</a> <br>Queensland University of Technology
</div>

<div class="portrait_row">
<img class="col fith portrait" src="assets/img/ben.jpg"/>
<img class="col fith portrait" src="assets/img/suman.jpg"/>
</div>
<div class="col fith caption">
      Ben Talbot <br>Queensland University of Technology
</div>
<div class="col fith caption">
      Suman Bista <br>Queensland University of Technology
</div>


<br><br>

The Robotic Vision Challenges organisers are with the [Australian Centre for Robotic Vision](http://www.roboticvision.org) at Queensland University of Technology (QUT) in Brisbane, Australia.

<div style="display:flex; justify-content:center;">
<a href="http://www.roboticvision.org"><img style="height:120px;" src="assets/img/acrv.png"></a>
<img  style="margin-left:100px;height:120px;" src="assets/img/qut-logo.png">
<!-- <img style="margin-left:100px; height:100px" src="assets/img/google-logo.png"> -->
</div>
