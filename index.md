---
layout: default
---

# Introduction
>Big benchmark challenges like [ILSVRC](http://www.image-net.org/challenges/LSVRC/) or [COCO](http://cocodataset.org) supported much of the remarkable progress in computer vision and deep learning over the past years.
>
>We aim to recreate this success for robotic vision.

We develop a set of new benchmark challenges specifically for robotic vision, and evaluate:
   * scene understanding,
   * uncertainty estimation,
   * continuous learning for domain adaptation, and to incorporate previuosly unseen classes,
   * active learning,
   * active vision, and eventually
   * complex tasks requiring a combination of scene understanding, learning, navigation, and interaction with the environment.

We combine the variety and complexity of real-world data with the flexibility of synthetic graphics and physics engines.

<!--
Expect the first challenges to go live around **November 2018**.

https://competitions.codalab.org/competitions/20940 -->


<!-- ## Active Challenges -->

# First Challenge - Probabilistic Object Detection

Our [probabilistic object detection challenge](object-detection) requires participants to **detect objects in video** data from high-fidelity simulation. As a novelty, our evaluation metric rewards accurate estimates of **spatial and semantic uncertainty** using probabilistic bounding boxes.

We made a *validation* and *test-dev* dataset with a public leaderboard available for ongoing evaluation of probabilistic object detection approaches. In addition, a *test-challenge* dataset and evaluation server will become available when we are organising a public competition. The first of those competitions was organised for a [workshop at CVPR 2019](cvpr2019), and the next will be available around Setember 2019, leading up to IROS.


<img src="assets/img/logo-IROS-2019.png" width="200" style="float:left; margin-right:10px;"> We organise a workshop at IROS 2019 on the topic of [The Importance of Uncertainty in Deep Learning for Robotics](iros2019). For that workshop, we will run a second round of the [probabilistic object detection challenge](object-detection). Stay tuned for further details.

To **participate** and for more information around the dataset [read more here ...](object-detection).

<!-- <img src="assets/img/CVPR19logo.jpg" width="200" style="float:left; margin-right:10px;"> We organised a first competition and [workshop at CVPR 2019](cvpr2019) in June 2019, where the best submissions will be presented and $5000 AUD in prize money will be available to the winning entries. -->



<!-- We provide a new dataset (split into *test-challenge*, *test-dev*, and *validation*), evaluation measure, and evaluation servers.

 We organise a competition and [workshop at CVPR 2019](cvpr2019) in Long Beach in June 2019

The **winners** of the competition will be announced at our .



, please go to our [Codalab page](https://competitions.codalab.org/competitions/20940). -->



<center>
<iframe width="560" height="315"  src="https://www.youtube.com/embed/6TR97EKUlaM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<!-- <center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/TZbEManAy-c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ISVkUqxk-sk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center> -->

<!--
 We released our first Robotic Vision [object detection challenge](https://competitions.codalab.org/competitions/20940)! Participants are tasked with **object detection** on a **video** stream, where each detection must provide accurate estimates of **spatial and semantic uncertainty** using probabilistic bounding boxes. Participants are evaluated using a new  measure which will reward accurate estimations of spatial and semantic uncertainty. -->

# News

  **May 2019:** We will organise a workshop at IROS 2019 on the topic of [The Importance of Uncertainty in Deep Learning for Robotics](iros2019). Stay tuned for further details.

  **January 2019:** We are happy to announce that CVPR 2019 is hosting our [workshop](cvpr2019). Participants of our Robotic Vision [object detection challenge](https://competitions.codalab.org/competitions/20940) will present their approaches and results, and we will announce the competition winners at the workshop.

  **December 2018:** We released our first Robotic Vision [object detection challenge](https://competitions.codalab.org/competitions/20940), requiring object detection on video data and rewarding accurate estimates of spatial and semantic uncertainty.

  **June 2018:** We presented our initial ideas for new benchmarks and metrics at two workshops during CVPR and RSS. Thanks to all who engaged in discussions and shared their thoughts during the workshops on [Real-World Challenges and New Benchmarks for Deep Learning in Robotic Vision](https://sites.google.com/view/cvpr2018-robotic-vision) at CVPR, and
 [New Benchmarks, Metrics, and Competitions for Robotic Learning](https://sites.google.com/view/rss2018-robotic-learning/home) at RSS.

 **Stay in touch** and follow us on Twitter for news and announcements: [@robVisChallenge](https://twitter.com/robVisChallenge).



# Coming Soon

Stay tuned for more challenges, focussing on active vision, and active and continuous learning in 2019.


# Motivation
Big computer vision challenges and competitions like [ILSVRC](http://www.image-net.org/challenges/LSVRC/) or [COCO](http://cocodataset.org) had a significant influence on the advancements in object recognition, object detection, semantic segmentation, image captioning, and visual question answering in recent years. These challenges posed motivating problems to the research community and proposed datasets and evaluation metrics that allowed to compare different approaches in a standardized way.

However, visual perception for robotics faces challenges that are not well covered or evaluated by the existing benchmarks.
These challenges comprise calibrated uncertainty estimation, continuous learning for domain adaptation and incorporation of novel classes, active learning, and active vision.

There is currently a lack of meaningful standardised evaluation protocols and benchmarks for these research challenges. This is a significant roadblock for the evolution of robotic vision, and impedes reproducible and comparable research.



We believe that by posing a new robotic vision challenge to the research community, we can motivate computer vision and robotic vision researchers around the world to develop solutions that lead to more capable, more robust, and more widely applicable robotic vision systems.


<!-- [principles](principles) -->

# Organisers, Support, and Acknowledgements

**Stay in touch** and follow us on Twitter for news and announcements: [@robVisChallenge](https://twitter.com/robVisChallenge).

<div class="portrait_row">
<img class="col fith portrait" src="assets/img/niko.jpg"/>  
<img class="col fith portrait" src="assets/img/feras.jpg"/>
<img class="col fith portrait" src="assets/img/david.jpg"/>
<img class="col fith portrait" src="assets/img/john.jpg"/>
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
      John Skinner <br>Queensland University of Technology
</div>
<div class="col fith caption">
      <a href="https://staff.qut.edu.au/staff/haoyang.zhang.acrv">Haoyang Zhang</a> <br>Queensland University of Technology
</div>

<br><br>

The Robotic Vision Challenges organisers are with the [Australian Centre for Robotic Vision](http://www.roboticvision.org).
This project is supported by a **Google Faculty Research Award** to Niko Sünderhauf in 2018.

<div style="display:flex; justify-content:center;">
<a href="http://www.roboticvision.org"><img style="height:120px;" src="assets/img/acrv.png"></a>
<img style="margin-left:100px; height:100px" src="assets/img/google-logo.png">
</div>

## Supporters
We thank the following supporters for their valuable input and engaging discussions.
<div class="portrait_row">
<img class="col fith portrait" src="assets/img/gustavo.jpg"/>  
<img class="col fith portrait" src="assets/img/anelia.png"/>  
<img class="col fith portrait" src="assets/img/anton.jpg"/>  
</div>
<div class="col fith caption">
      <a href="https://cs.adelaide.edu.au/~carneiro/">Gustavo Carneiro</a> <br> University of Adelaide
</div>
<div class="col fith caption">
      <a href="https://ai.google/research/people/AneliaAngelova">Anelia Angelova</a> <br> Google Brain
</div>
<div class="col fith caption">
      <a href="https://cs.adelaide.edu.au/users/hengel/">Anton van den Hengel</a> <br> University of Adelaide
</div>
<br><br>
