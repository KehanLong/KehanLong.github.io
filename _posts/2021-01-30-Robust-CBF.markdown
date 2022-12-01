---
layout: post
title:  "Learning Barrier Functions with Memory for Robust Safe Navigation"
date:   2021-01-30 22:21:59 +00:00
image: /images/Robust_cbf_1.PNG
categories: research
authors: "<strong>Kehan Long</strong>, Cheng Qian, Jorge Cortes, Nikolay Atanasov"
venue: "IEEE Robotics and Automation Letters (RA-L)"
arxiv: https://arxiv.org/abs/2011.01899
---

Control barrier functions are widely used to enforce safety properties in robot motion planning and control. However, the problem of constructing barrier functions online and synthesizing safe controllers that can deal with the associated uncertainty has received little attention. This paper investigates safe navigation in unknown environments, using on-board range sensing to construct control barrier functions online. To represent different objects in the environment, we use the distance measurements to train neural network approximations of the signed distance functions incrementally with replay memory. This allows us to formulate a novel robust control barrier safety constraint which takes into account the error in the estimated distance fields and its gradient. Our formulation leads to a second-order cone program, enabling safe and stable control synthesis in a prior unknown environments.
