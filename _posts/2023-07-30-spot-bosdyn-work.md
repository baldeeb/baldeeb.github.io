---
layout: post
title: A Year With Boston Dynamics Spot
date: 2023-7-30 15:00:00
# description: asdfasdfasdfasdf
tags: spot-bosdyn
categories: RPM-lab
---

Through my work at RPM I got the chance to developm tools and demonstrate research using the lab's Boston Dynamics Sport robot. To kickstart our mobile manipulation work, we were motivated by leveraging robots for in home organization, particularly chair manipulation. Chairs are comopled and learning to utilize a robot to orgnize them without requiring rigid algorithms seemed a sufficiently challenging feat.

<div class="container">
<div class="row justify-content-md-center justify-content-around">
    <div class="col-6">
        <!-- {% include video.html path="assets/video/20230429_spot_chair_pitch_final.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %} -->
        <iframe src="https://drive.google.com/file/d/12V2PiA86X8rsWzxrB732bLIm3iUmxYQI/preview?mute=1" allow="autoplay"></iframe>
    </div>
</div>
    <div class="caption">
        Teleoperated demonstration of the intedned outcome. Model results will be added in the future.
    </div>
</div>

After a few months I demonstrating the tools developed at a local conference. These demonstrations formed bases for our datacollection efforts.
<!-- A few months after starting at the Robotics: Perception & Manipulation lab, we [recieved our spot robot](https://cse.umn.edu/cs/news/desingh-lab-unpacks-first-spot-robot-boston-dynamics). I was tasked with setting it up and building it tools that could facilitate research towards mobile manipulation. Many tasks ran alongside this work but throughout the year much thought was given towards what might be worth exploring and setting up to advance research around using movile manipulators in domestic settings towards task execution.

Thanks to all the open sourced code and Boston Dynamics' great engineering, I managed to assemble a set of tools to facilitate and complement the use of the Spot Robot. By adding onto existant tools and chaining capabilities, Spot became ready for demonstrating perceptually and dynamically complex tasks such as detecting and dragging a chair. -->

<div class="row mt-2 justify-content-around">
    <div class="col-sm mt-2 mt-md-0">
        <!-- {% include video.html path="assets/video/excel_spot_chair/tracking_chair.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %} -->
        <iframe src="https://drive.google.com/file/d/1CRGFCi3UDZxn60pNHLN6Q5gQvilM__WB/preview?mute=1" allow="autoplay"></iframe>
    </div>
    <div class="col-sm mt-2 mt-md-0">
        <!-- {% include video.html path="assets/video/excel_spot_chair/grabbing_chair.mp4" class="img-fluid rounded z-depth-1" controls=true %} -->
        <iframe src="https://drive.google.com/file/d/1HjGXmrSYA209F4m5mcokDUraG6_SgnAC/preview?mute=1" allow="autoplay"></iframe>
    </div>
</div>
<div class="caption">
    A demonstration of spot's engineered grasping tools at an Excel Engineering conference. This demonstration complement the discussion around the difficulties and importance of further researching robot learning of perception and manipultion. These demonstration tools are now used to collect robot training data.
</div>

<!-- 
This was the only beginning of our exploration. Our initial efforts were geared towards utilizing pre-trained 2D-models (CLIP, [DINO](https://github.com/facebookresearch/dino), ...) and dense correspondences ([NOCS](https://arxiv.org/abs/1901.02970)). Soon after, our focus shifted to exploring the use of multi-task imitation learning 3D models such as [PerAct](https://peract.github.io/). I am actively expanding the use of such model to dynamically complex mobile manipluation tasks such as furniture rearrangement. Future posts will be dedicated to the technical details. -->

### Technically

<!-- Poster-Skill_Chaining_for_Mobile_Malipulation_Task_Learning.pdf -->


Apart from this experience being a major research endeavor, it allowed me the opportunity of leading a group of undergraduates interested in pursuing robotics research. I wrote project proposals for 2 works that are being carried out partly by 5 capable undergrads. Seeing their work come to fruition has been rewarding.

<div class="container">
    <div class="row  align-items-center justify-content-around">
        <div class="col-4">
            {% include figure.html path="assets/img/spot_undergraduate_crew.jpg" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-6">
            <!-- {% include video.html path="https://drive.google.com/file/d/1otIK2uVudY0fnEes0oEtdQRIl3rkCZU9/preview" class="img-fluid rounded z-depth-1" controls=true autoplay=true %} -->
            <iframe src="https://drive.google.com/file/d/1otIK2uVudY0fnEes0oEtdQRIl3rkCZU9/preview?mute=1" allow="autoplay"></iframe>
        </div>
    </div>
    <div class="caption">
        On the right side is the group of students who worked with me in the lab through the summer of 2023. To the right is a debut of one of the works from the group that exposes the path record replay abilities and results using Rviz. More results are coming soon!
    </div>
</div>

#### Closing

In the span of 9 months, with the help of enthusiastic undergraduates and an amazing community, I have taken spot out of the box and made it into a capable mobile manipulation AI research tool. I gave it sight through NOCS and the ability to reason through PerAct. Our robot is now a reseach, data collection, and development tool. It communicates over ROS, interfaces through Rviz, is able to understand AprilTags and link to external sensors to augment its view.

This platform is set to be a catalyst for future research at the RPM lab and has proven to expose many future researchers to what robots are capable of.
