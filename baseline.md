---
layout: page
title: Baseline
permalink: /baseline/
nav_order: 2
---

# Baseline 

Before evaluating the performance of SLAM algorithms in the presence of perturbations, it is important to understand what their performance is when environments are mostly free of perturbations and the inputs to the algorithms are of good quality.
We refer to this as **baseline performance**.


| ![](/images/rgbd_baseline_images.png) |
|:--:|
| Frames from sequences used for evaluating the baseline performance of RGB-D algorithms <br /> from the [TUM RGB-D](https://vision.in.tum.de/data/datasets/rgbd-dataset/download) and [ICL-NUIM](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html) datasets  |

Algorithms with RGB-D input support (ORB-SLAM2, ORB-SLAM3, ReFusion, FullFusion, and ElasticFusion) are evaluated on 12 sequences of the TUM RGB-D dataset, captured with a Kinect camera
and the 4 synthetic sequences of the ICL-NUIM dataset.

<details>
	<summary>ICL-NUIM results</summary>

<img src="{{ '/results/iclnuim/living_room_traj0_loop.png' | absolute_url }}"/>
<p style="text-align:center"> ICL-NUIM Living Room 0 </p>


<img src="{{ '/results/iclnuim/living_room_traj1_loop.png' | absolute_url }} "/>
<p style="text-align:center"> ICL-NUIM Living Room 1 </p>

<img src="{{ '/results/iclnuim/living_room_traj2_loop.png' | absolute_url }} "/>
<p style="text-align:center"> ICL-NUIM Living Room 2 </p>

<img src="{{ '/results/iclnuim/living_room_traj3_loop.png' | absolute_url }} "/>
<p style="text-align:center"> ICL-NUIM Living Room 3 </p>
</details>



<details>
	<summary>TUM RGB-D results</summary>
</details>



| ![](/images/stereo_baseline_images.png) |
|:--:|
| Frames from sequences used for evaluating stereo(-inertial) algorithms from the [EuRoC MAV](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) dataset |

Algorithms with stereo and stereo-inertial support are evaluated on the _easy_ and _medium_ sequences of the EuRoC MAV dataset.

<details>
	<summary>EuRoC results</summary>

<img src="{{ '/results/euroc-baseline/MH_01_easy.png' | absolute_url }}"/>
<p style="text-align:center"> Machine Hall 01 (easy) </p>
<hr> 

<img src="{{ '/results/euroc-baseline/MH_02_easy.png' | absolute_url }} "/>
<p style="text-align:center"> Machine Hall 02 (easy) </p>
<hr> 

<img src="{{ '/results/euroc-baseline/MH_03_medium.png' | absolute_url }}"/>
<p style="text-align:center"> Machine Hall 03 (medium) </p>
<hr> 

<img src="{{ '/results/euroc-baseline/V1_01_easy.png' | absolute_url }} "/>
<p style="text-align:center"> Vicon Room1 01 (easy) </p>
<hr> 

<img src="{{ '/results/euroc-baseline/V1_02_medium.png' | absolute_url }} "/>
<p style="text-align:center"> Vicon Room1 02 (medium) </p>
<hr> 

<img src="{{ '/results/euroc-baseline/V2_01_easy.png' | absolute_url }} "/>
<p style="text-align:center"> Vicon Room2 01 (easy) </p>
<hr> 

<img src="{{ '/results/euroc-baseline/V2_02_medium.png' | absolute_url }}"/>
<p style="text-align:center"> Vicon Room2 02 (medium) </p>
<hr> 

</details>
