---
layout: post
title:  "Deformable Formation Control"
date:   2020-07-17 00:00:00 -0400
categories: posts
---
![ACC 2019](/images/acc2019_teaser_figure.png)


We considered the formation control of a team of UAVs using a cooperative control technique called Continuum Deformation. This is a leader-follower technique that treats agents as particles of a deformable shape. We implemented this protocol in 2D, experimentally as seen below. We assigned three leaders (UAVs 1,2, and 3) to form a triangle to contain two followers (UAVs 4 and 5). Leaders had their desired trajectories explicitly planned, but followers obtained their desired trajectories based on their neighbors and communication weights. Local deviation bounds of UAVs were used to set limits on the deformation of the shape as a whole in order to guarantee inter-agent collision avoidance and containment within the triangle [1].




<iframe width="560" height="315" src="https://www.youtube.com/embed/ve7XYELyWXg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<br>

[1] M. Romano, P. Kuevor, D. Lukacs, O. Marshall, M. Stevens, H. Rastgoftar, J. Cutler, and E. Atkins, “Experimental evaluation of continuum deformation with a five quadrotor team,” in 2019 American Control Conference (ACC). IEEE, 2019, pp. 2023–2029. [arxiv](https://arxiv.org/abs/1809.10250). [IEEEexplore](https://ieeexplore.ieee.org/abstract/document/8815266).