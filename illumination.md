---
layout: page
title: Illumination changes
permalink: /illumination/
nav_order: 4
---

| ![](/images/ethi_images.jpg) |
|:--:|
| Frames from sequences used for evaluating performance in the presence of illumination changes <br /> from the [ETH Illumination](https://www.cvg.ethz.ch/research/illumination-change-robust-dslam) dataset  |

Many SLAM algorithms assume that lighting will be consistent and rely on color information to estimate the camera position.
In practice, lighting conditions often change unpredictably - for example if a light source is temporarily occluded. 
Here we study the effect of lighting changes on two dense systems which use a photometric error as part of their pose computation, 
ReFusion and ElasticFusion, and two sparse, feature-based algorithms: ORB-SLAM2 and ORB-SLAM3.

We use the ETH Illumination dataset, which is based on the TUM and ICL-NUIM datasets, containing both real and synthetic sequences with local and global illumination changes,
as well as sequences where a flashlight shining from the perspective of the camera is used.
It is immediately clear from the results that thanks to lighting-invariance, the feature-based algorithms perform significantly better.


<div>

<hr>

<img src="{{ '/results/ethi/ethl_real_flash.png' | absolute_url }} " />
<p style="text-align:center"> Real Flashlight </p>
<hr>

<img src="{{ '/results/ethi/ethl_real_global.png' | absolute_url }} " />
<p style="text-align:center"> Real Global Illumination </p>
<hr>

<img src="{{ '/results/ethi/ethl_real_local.png' | absolute_url }}" />
<p style="text-align:center"> Real Local Illumination </p>
<hr>

<img src="{{ '/results/ethi/ethl_syn1_global.png' | absolute_url }}" />
<p style="text-align:center"> Synthetic1 Global Illumination </p>
<hr>

<img src="{{ '/results/ethi/ethl_syn1_local.png' | absolute_url }}" />
<p style="text-align:center"> Synthetic1 Local Illumination </p>
<hr>

<img src="{{ '/results/ethi/ethl_syn1_loc_glo.png' | absolute_url }}" />
<p style="text-align:center"> Synthetic1 Local + Global Illumination </p>
<hr>

<img src="{{ '/results/ethi/ethl_syn2_flash.png' | absolute_url }}" />
<p style="text-align:center"> Synthetic2 Flashlight </p>
<hr>

<img src="{{ '/results/ethi/ethl_syn2_global.png' | absolute_url }}" />
<p style="text-align:center"> Synthetic2 Global Illumination </p>
<hr>

<img src="{{ '/results/ethi/ethl_syn2_local.png' | absolute_url }}" />
<p style="text-align:center"> Synthetic2 Local Illumination  </p>
<hr>

<img src="{{ '/results/ethi/ethl_syn2_loc_glo.png' | absolute_url }}" />
<p style="text-align:center"> Synthetic2 Local + Global Illumination</p>
<hr>

</div>