---
layout: page
title: Fast motion
permalink: /fast/
nav_order: 5
---

| ![](/images/fast_images.png) |
|:--:|
| Frames from sequences used for evaluating performance in fast motion scenarios <br /> from the [EuRoC MAV](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) dataset  |

Fast movement may lead to poor input data featuring disturbances such as motion blur, and encumbering feature detection and matching.
We evaluate stereo and stereo-inertial algorithms (ORB-SLAM2, ORB-SLAM3, and OpenVINS) on the _difficult_ sequences of the EuRoC MAV dataset.
The data was acquired using a drone flying at high speeds in an industrial setting and in cluttered rooms.

-------------------------

<div>

<hr>
<img src="{{ '/results/euroc-fast/MH_04_difficult.png' | absolute_url }}" />
<p style="text-align:center"> Machine Hall 04 </p>
<hr>

<img src="{{ '/results/euroc-fast/MH_05_difficult.png' | absolute_url }}" />
<p style="text-align:center"> Machine Hall 05 </p>
<hr>

<img src="{{ '/results/euroc-fast/V1_03_difficult.png' | absolute_url }} " />
<p style="text-align:center"> Vicon Room1 03 </p>
<hr>

<img src="{{ '/results/euroc-fast/V2_03_difficult.png' | absolute_url }}" />
<p style="text-align:center"> Vicon Room2 03 </p>

</div>