---
layout: page
title: Sparse Neural Generative Inference Based Pose Estimation
description: # Advanced Computer Vision Course - Fall 2020 - Professor David Fouhey
img: assets/img/SSPF.png
importance: 1
category: Academic - Masters
---

:page_facing_up: [report](/assets/pdf/SPPFNet.pdf)

[Advanced Computer Vision](https://web.eecs.umich.edu/~fouhey/teaching/EECS542_F20/) - Fall 2020 - Professor David Fouhey

We envisioned a light weight pose estimation model that learns end-to-end to leverage moving particles that sample portions of the image to inform object pose estimation.

<div class="col-sm ">
    {% include figure.html path="assets/img/SSPF.png" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
    The image shows the produced pipeline. Movitated by reducing model and time coplexity, we aimed to utilize particle-filter like sampling to attend to areas where objects might be present in high resolution images.
</div>
