---
layout: post
title:  "Deformable Formation Planning"
date:   2022-03-28 00:00:00 -0400
categories: posts
---

Formation flying offers great benefits to teams of UAS. The close proximity of UAS to each other within a formation enables enhanced coverage, reliable communication, and reduced planning computational complexity. However, if a sudden vehicle failure or pop-up obstacle occurs the system needs to be able to respond in an intelligent way without forcing the entire formation to remain rigid while avoiding the failure, or worse colliding with the failure.

Our approach to this problem is to have the UAS deform along a fluid flow field to avoid the failure [1]. We developed a computationally efficient navigation algorithm that maintains a maximum speed for all vehicles to follow. Additionally, when a minimum agent separation condition is met in the starting formation, we guarantee safety through this deformation. Experimental results validate the method as shown in the video below.    


<iframe width="560" height="315" src="https://www.youtube.com/embed/VTWM2BcMfVA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

[1] M. Romano, H. Uppaluru, H. Rastgoftar, and E. Atkins, “Quadrotor Formation Flying
Resilient to Abrupt Vehicle Failures via a Fluid Flow Navigation Function,” 2022 IEEE/RSJ
International Conference on Intelligent Robots and Systems (IROS), 2022 (Under Review). [arxiv](https://arxiv.org/abs/2203.01807)