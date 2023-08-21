---
layout: post
title: A Year With Boston Dynamics Spot
date: 2023-7-30 15:00:00
# description: asdfasdfasdfasdf
tags: spot-bosdyn
categories: RPM-lab
---
A few months after starting at the Robotics: Perception & Manipulation lab, we [recieved our spot robot](https://cse.umn.edu/cs/news/desingh-lab-unpacks-first-spot-robot-boston-dynamics). I was tasked with setting it up and building it tools that could facilitate research towards mobile manipulation. Many tasks ran alongside this work but throughout the year much thought was given towards what might be worth exploring and setting up to advance research around using movile manipulators in domestic settings towards task execution.

Thanks to all the open sourced code and Boston Dynamics' great engineering, I managed to assemble a set of tools to facilitate and complement the use of the Spot Robot. By adding onto existant tools and chaining capabilities, Spot became ready for demonstrating perceptually and dynamically complex tasks such as detecting and dragging a chair.

<div class="row mt-2">
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
    Demonstrating spot's engineered grasping tools at an Excel Engineering conference. This demonstration complement the discussion around the difficulties and importance of further researching robot learning of perception and manipultion. These demonstration tools are now used to collect robot training data.
</div>

Needless to say, this was the only beginning of our exploration. Our initial efforts were geared towards utilizing pre-trained 2D-models (CLIP, DINO, ...) and dense correspondences (NOCS). Soon after, our focus shifted to exploring the use of multi-task imitation learning 3D models such as [PerAct](https://peract.github.io/). We took on the challenge of expanding such model to dynamically complex tasks and mobile manipluation. We set our sight on the furnature rearrangement and house tasks. Future posts will be dedicated to the technical details.

<div class="container">
<div class="row justify-content-md-center">
    <div class="col-6">
        <!-- {% include video.html path="assets/video/20230429_spot_chair_pitch_final.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %} -->
        <iframe src="https://drive.google.com/file/d/12V2PiA86X8rsWzxrB732bLIm3iUmxYQI/preview?mute=1" allow="autoplay"></iframe>
    </div>
</div>
    <div class="caption">
        Teleoperated demonstration of the intedned outcome. Model results will be added in the future.
    </div>
</div>


Apart from this experience being a major research edeavor, it coupled with an opportunity to lead a group of undergraduates interested in pursuing robotics research. I wrote project proposals for 2 works that are being carried out partly by 5 capable undergrads. Seeing their work come to fruition has been rewarding.

<div class="container">
    <div class="row justify-content-md-center">
        <div class="col-4">
            {% include figure.html path="assets/img/spot_undergraduate_crew.jpg" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-8">
            <!-- {% include video.html path="https://drive.google.com/file/d/1otIK2uVudY0fnEes0oEtdQRIl3rkCZU9/preview" class="img-fluid rounded z-depth-1" controls=true autoplay=true %} -->
            <iframe src="https://drive.google.com/file/d/1otIK2uVudY0fnEes0oEtdQRIl3rkCZU9/preview?mute=1" allow="autoplay"></iframe>
        </div>
    </div>
    <div class="caption">
        On the right side is the group of students who worked with me in the lab through the summer of 2023. To the right is a debut of one of the works from the group that exposes the path record replay abilities and results using Rviz. More results are coming soon!
    </div>
</div>
