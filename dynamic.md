---
layout: page
title: Dynamic scenes
permalink: /dynamic/
nav_order: 3
---

# Dynamic scenes

| ![](images/bonn_images.png) |
|:--:|
| Frames from sequences used for evaluating performance in dynamic environments <br /> from the [Bonn](https://www.ipb.uni-bonn.de/data/rgbd-dynamic-dataset/) and [TUM RGB-D](https://vision.in.tum.de/data/datasets/rgbd-dataset/download) datasets  |

Most SLAM algorithms have an in-built assumption that the environment will be static. In reality, the vast majority of SLAM use-cases take place 
in environments with dynamic objects. Dynamic objects are not only a perturbation to be dealt with but often the most important elements of a scene:
humans, vehicles, tools, agents able to modify other aspects of the environment. It is thus crucial for a robotic system that they are recognized and modelled appropriately.
From the point of view of camera localization, the static world assumption implies that all changes from one frame to another can be accounted for by a single causal factor: camera position.
Systems which work under this assumption will therefore include changes produced by dynamic objects when computing the camera pose, and perform erroneously. 

Algorithms with RGB-D support are evaluated on the 24 dynamic sequences of the Bonn dataset and the 8 dynamic sequences 
of the _freiburg3_ TUM dataset. 


<div>

<hr>
<img src="{{ '/results/bonn/rgbd_bonn_balloon.png' | absolute_url }} " />
<p style="text-align:center"> Balloon </p>
<hr>

<img src="{{ '/results/bonn/rgbd_bonn_balloon2.png' | absolute_url }}"/>
<p style="text-align:center"> Balloon 2 </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_balloon_tracking.png' | absolute_url }}"/>
<p style="text-align:center"> Balloon tracking  </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_balloon_tracking2.png' | absolute_url }}"/>
<p style="text-align:center"> Balloon tracking 2 </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_crowd.png' | absolute_url }} "/>
<p style="text-align:center"> Crowd </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_crowd2.png' | absolute_url }}"/>
<p style="text-align:center"> Crowd 2 </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_crowd3.png' | absolute_url }} "/>
<p style="text-align:center"> Crowd 3 </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_moving_nonobstructing_box.png' | absolute_url }}"/>
<p style="text-align:center"> Moving nonobstructing box </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_moving_nonobstructing_box2.png' | absolute_url }}"/>
<p style="text-align:center"> Moving nonobstructing box 2 </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_person_tracking.png' | absolute_url }}"/>
<p style="text-align:center"> Person tracking </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_person_tracking2.png' | absolute_url }} "/>
<p style="text-align:center"> Person tracking 2 </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_moving_obstructing_box.png' | absolute_url }}"/>
<p style="text-align:center"> Moving obstructing box </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_moving_obstructing_box2.png' | absolute_url }}"/>
<p style="text-align:center"> Moving obstructing box 2  </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_placing_nonobstructing_box.png' | absolute_url }}"/>
<p style="text-align:center"> Placing nonobstructing box </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_placing_nonobstructing_box2.png' | absolute_url }}"/>
<p style="text-align:center"> Placing nonobstructing box 2 </p>
<hr> 


<img src="{{ '/results/bonn/rgbd_bonn_placing_nonobstructing_box3.png' | absolute_url }}"/>
<p style="text-align:center"> Placing nonobstructing box 3 </p>
<hr> 


<img src="{{ '/results/bonn/rgbd_bonn_placing_obstructing_box.png' | absolute_url }}"/>
<p style="text-align:center"> Placing obstructing box </p>
<hr> 


<img src="{{ '/results/bonn/rgbd_bonn_removing_nonobstructing_box.png' | absolute_url }} "/>
<p style="text-align:center"> Removing nonobstructing box </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_removing_nonobstructing_box2.png' | absolute_url }} "/>
<p style="text-align:center"> Removing nonobstructing box 2 </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_removing_obstructing_box.png' | absolute_url }} "/>
<p style="text-align:center"> Removing Obstructing Box </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_synchronous.png' | absolute_url }} "/>
<p style="text-align:center"> Synchronous </p>
<hr> 

<img src="{{ '/results/bonn/rgbd_bonn_synchronous2.png' | absolute_url }}"/>
<p style="text-align:center"> Synchronous2 </p>
<hr> 

</div>

