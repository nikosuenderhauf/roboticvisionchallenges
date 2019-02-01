---
layout: default
---

# The Probabilistic Object Detection Challenge

<!-- <h2 class="project-tagline">Evaluating Uncertainty Estimation, Continuous Learning and Active Learning</h2> -->
## Overview
Our first challenge requires participants to **detect objects in video** data produced from high-fidelity simulations. The novelty of this challenge is that participants are rewarded for providing **accurate estimates of both spatial and semantic uncertainty** for every detection using probabilistic bounding boxes.

Accurate spatial and semantic uncertainty estimates are rewarded by our newly developed probability-based detection quality (PDQ) measure. Full details about this new measure are available in our [arxiv paper](https://arxiv.org/abs/1811.10800).

We invite anyone who is interested in object detection and appreciates a good challenge to please participate and compete in the competition so that we may continue to push the state-of-the-art in object detection in directions more suited to robotics applications. We also appreciate any and all feedback about the challenge itself and look forward to hearing from you.



<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/6TR97EKUlaM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>


## Participation and Presentation of Results
Please head to our [Codalab page](https://competitions.codalab.org/competitions/20940) to participate, download the training/validation and test dataset, and find out further information around the dataset and submission format.

<img src="assets/img/CVPR19logo.jpg" width="200" style="float:left; margin-right:10px;">
We are organising a [workshop at CVPR 2019](cvpr2019) in June. Participants can present their results and we will announce the challenge winners.



<!-- ![](assets/img/longbeach.png) -->


## Example Data
For this challenge, we use simulated data and vary both the lighting conditions (day and night), as well as the camera height (to simulate domestic service robots of different size).
![](https://c1.staticflickr.com/5/4852/46183850271_764bcaac56_o.png)

The dataset uses a subset of the Microsoft COCO classes:  
``['bottle', 'cup', 'knife', 'bowl', 'wine glass', 'fork', 'spoon', 'banana', 'apple', 'orange', 'cake', 'potted plant', 'mouse', 'keyboard', 'laptop', 'cell phone', 'book', 'clock', 'chair', 'dining table', 'couch', 'bed', 'toilet', 'television', 'microwave', 'toaster', 'refrigerator', 'oven', 'sink', 'person']``

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/EffaE3pJyx8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>
<div class="col three caption">
      Training scene with labeled objects.
</div>




## New Evaluation Measure - PDQ

We developed a new [probability-based detection quality (PDQ)](https://arxiv.org/abs/1811.10800) evaluation measure for this challenge, please see the [arxiv paper](https://arxiv.org/abs/1811.10800) for more details.

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/LzyTHktKUZ4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

PDQ is a new visual object detector evaluation measure
which not only assesses detection quality, but also accounts
for the spatial and label uncertainties produced by
object detection systems. Current evaluation measures such
as mean average precision (mAP) do not take these two aspects
into account, accepting detections with no spatial uncertainty
and using only the label with the winning score
instead of a full class probability distribution to rank detections.

To overcome these limitations, we propose the
probability-based detection quality (PDQ) measure which
evaluates both spatial and label probabilities, requires no
thresholds to be predefined, and optimally assigns groundtruth
objects to detections.

Our [experimental evaluation]([arxiv paper](https://arxiv.org/abs/1811.10800)) shows that PDQ rewards detections with accurate spatial probabilities and explicitly evaluates label probability to determine detection quality. PDQ aims to encourage the
development of new object detection approaches that provide
meaningful spatial and label uncertainty measures.
