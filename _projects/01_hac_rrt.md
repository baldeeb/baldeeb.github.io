---
layout: page
title: Planning with Hierarchical Reinforcement-Learning Agents
description: #Motion Planning Course - Winter 2022 - Professor Dmitry Berenson
img: assets/img/hacrrt.png
importance: 1
category: Academic - Masters
---

:page_facing_up: [report](/assets/pdf/hac-rrt-writeup.pdf)

[Motion Planning Course](https://web.eecs.umich.edu/~dmitryb/courses/winter2022motionplanning/index.html) - Winter 2022 - Professor Dmitry Berenson

I developed a Rapidly-Exploring Random-Tree (RRT) algorithm that used the intermediate layers of a Hierarchical-Actor-Critic (HAC) agent to model state propagation. In doing so, I demostrate the use of an RL agent for planning and the use of Q-fuctions to encourage safer long-horizon plans.

<div class="col-sm">
    {% include figure.html path="assets/img/hacrrt.png" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
    The image shows the paths explored by the RRT that utilizes a hierarchical-actor-critic agents' policy to predict take steps, and the agents' Q-functions to detrmine the quality of the predicted path. Different levels of the hierarchy weigh on the path's quality to explore and produce more promising paths.
</div>
