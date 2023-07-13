---
layout: page
title: 
description: 
img: assets/img/
importance: 1
category: 
---




<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<!----------------------------- HAC RRT Project ------------------------------>
<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
    <tbody>
        <td width="30%" style="text-align: center;">
            <img src='./images/hac_rrt_path.png' width="75%">
        </td>
        <td valign="top" width="70%">
            <p>
                <papertitle>
                Safer Planning Using a Hierarchical Reinforcement-Learning Agent
                </papertitle>
                <br>
                <em>
                <a href="https://web.eecs.umich.edu/~dmitryb/courses/winter2022motionplanning/index.html" target="_blank">
                    Motion Planning
                </a>
                - Winter 2022 - Professor Dmitry Berenson
                <br>
                [<a href="./pdfs/hac-rrt-writeup.pdf" target="_blank">report</a>]
                </em>
                <!-- <br>
                A class project in which I explored the potential of finding a safe path 
                while using reinforcement learning to learn dynamics. -->
                <br>
                <br style="line-height: 8px;">
                I developed a Rapidly-Exploring Random-Tree (RRT) algorithm 
                that used the intermediate layers of a Hierarchical-Actor-Critic (HAC) 
                agent to model state propagation. In doing so, I demostrate the use of an 
                RL agent for planning and the use of Q-fuctions to encourage
                safer long-horizon plans.
                <!-- The RRT would discard proposed next 
                steps if they led to high Q-values. Attempting to reach random goals 
                exposes less risky paths. -->
            </p>
        </td>
    </tr>
    </tbody>

</table>

<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<!---------------------------- Dense Descriptors ---------------------------->
<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
    <tbody>
        <td width="30%">
            <img src='./images/DenseDescriptorsWithLoss.png' width="100%">
        </td>
        <td valign="top" width="70%">
            <p>
                <papertitle> Dense Descriptors Towards Fine Manipulation </papertitle>
                <br>
                <em>
                Directed Study - Fall 2021 - 
                <a href="https://ocj.name/"  target="_blank"> Professor Chad Jenkins </a> 
                <br>
                [<a href="./pdfs/Abbreviated-Writup-Evolving-Dense-Descriptors-Towards-Fine-Manipulation.pdf" target="_blank">abridged report</a>]
                </em>
                <br> <br style="line-height: 8px;">
                To train dense descriptors for fine object manipulation, we construct
                a more granular model and explore losses that encouraged
                the model to encode a sense of parts and poses.  
            </p>
        </td>
    </tr>
    </tbody>

</table>

<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<!------------------- PHD-Filter Exploration -------------------->
<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
    <tbody>
    <td width="30%">
        <img src='./images/PhdFilterPeopleTracking.gif' width="100%">
    </td>
    <td valign="top" width="70%">
        <p>
        <papertitle>
            Probability-Hypothesis-Density Filters for Pedestrian Tracking 
        </papertitle>
        <br>
        <em>
            <a href="https://github.com/UMich-CURLY-teaching/UMich-ROB-530-public" target="_blank">Mobile Robotics</a> 
            - Winter 2021 - Professor Maani Ghaffari 
            <br>
            [<a href="https://github.com/MobileRoboticistsW21/PHD-object-tracking" target="_blank">code</a>] 
        </em>
        <br>
        <br style="line-height: 8px;">
        We explore an object tracking filter that does not assume any association, 
        unlike variants that the course discusses. The P.H.D. filter models the 
        extent of track association as a Gaussian distribution.
        The project showed the success of the filter in certain settings
        and the general difficulty of estimating people (highly deformable 
        objects) using low dimensional (bounding box) tracks. 
        </p>
    </td>
    </tr>
</tbody>

</table>


<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<!------------------- Aversarial Augmentation -------------------->
<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
    <tbody>
    <td width="30%">
        <img src='./images/AdversarialAug.png' 
        style="width: 125px; margin: auto; display: flex;">
    </td>
    <td valign="top" width="70%">
        <p>
        <papertitle>
            Adversarial Augmentation For Positive-Sample Learning.
        </papertitle>
        <br>
        <em>
            <a href="https://web.eecs.umich.edu/~ahowens/eecs598-012/w21/" target="_blank">
            Unsupervised Visual Learning
            </a> 
            - Winter2021 - Proessor Andrew Owens
            <br>
            [<a href="./pdfs/Adversarial-Augmentations-for-non-Contrastive-Learning.pdf" target="_blank">report</a>]
        </em>
        <br>
        <br style="line-height: 8px;">
        We explored the benefit of training a non-contrastive model using 
        structured adversarial augmentation.   
        </p>
    </td>
    </tr>
</tbody>

</table>




<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<!------------------- Sparse Pose Estimation -------------------->
<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
    <tbody>
    <td width="30%">
        <img src='./images/SSPF.png' width="100%">
    </td>
    <td valign="top" width="70%">
        <p>
        <papertitle>
            Sparse Neural Generative Inference Based Pose Estimation
        </papertitle>
        <br>
        <em>
            <a href="https://web.eecs.umich.edu/~fouhey/teaching/EECS542_F20/" target="_blank">
            Advanced Computer Vision
            </a> 
            - Fall 2020 - Professor David Fouhey
            <br>
            [<a href="./pdfs/SPPFNet.pdf" target="_blank">report</a>]
        </em>
        <br> <br style="line-height: 8px;">
        We envisioned a light weight pose estimation model that learns end-to-end to
        leverage moving particles that sample portions of the image to inform object pose
        estimation.    
        </p>
    </td>
    </tr>
</tbody>

</table>




<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<!------------------- Hybrid mapping -------------------->
<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
<tbody>
    <td width="30%">
    <img src='./images/hybridSLAM.png' height="125px" style="display:flex; margin:auto">
    </td>
    <td valign="top" width="70%">
    <p>
        <papertitle> SLAM Using Hybrid Maps </papertitle>
        <br>
        <em>
        <a href="https://web.eecs.umich.edu/~kuipers/teaching/eecs467-F19.html" target="_blank">
            Introduction to Autonomous Robotics 
        </a> 
        - Winter 2018 - Professor Benjamin Kuipers
        <br>
        [<a href="https://www.youtube.com/watch?v=Q4Nzotdwz_s" target="_blank">demo video</a>] 
        <br>
        </em>
        <br style="line-height: 8px;">
        Implemented SLAM using a hybrid of dense and topological maps on a 
        robot equipped with a single beam LIDAR for the purpose of reducing 
        time complexity and memory usage.    
    </p>
    </td>
</tr>
</tbody>

</table>



<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->
<!------------------------------ Other Projects ----------------------------->
<!--------------------------------------------------------------------------->
<!--------------------------------------------------------------------------->

<!-- <table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
<tbody> <tr> <td width="100%" valign="top">

    <heading style="line-height: 2em;">
    Other Projects
    </heading>
    <br>
    <table width="100%" valign="top" border="0" cellspacing="0" cellpadding="2">

    <tr valign="top"> 
        <td>  
        <br style="line-height: 8px;">
        <papertitle> <a href="./pdfs/Adversarial-Augmentations-for-non-Contrastive-Learning.pdf" target="_blank">
            Adversarial Augmentation For Positive-Sample Learning.
        </a> </papertitle> 
        <br>
        <em> Unsupervised Visual Learning - Winter2021</em>
        <br> 
        We explored the benefit of training a non-contrastive model using contrastive augmentation.  
        </td> 
    </tr>
    <tr valign="top"> 
        <td>  
        <br style="line-height: 8px;">
        <papertitle> <a href="./pdfs/SPPFNet.pdf" target="_blank">
            Sparse Neural Generative Inference Based Pose Estimation
        </a> </papertitle> 
        <br>
        <em> Advanced Computer Vision - Fall 2020</em>
        <br> 
        We envisioned a light weight pose estimation model that learns end-to-end to
        leverage moving particles that sample portions of the image to inform object pose
        estimation.  
        </td> 
    </tr>
    <tr valign="top"> 
        <td>  
        <br style="line-height: 8px;">
        <papertitle> <a href="https://www.youtube.com/watch?v=Q4Nzotdwz_s">
            SLAM Using Hybrid Maps
        </a> </papertitle> 
        <br>
        <em> Introduction to Autonomous Robotics - Winter 2018</em>
        <br> 
        Implemented SLAM using a hybrid of dense and topological maps on a 
        robot equipped with a single beam LIDAR for the purpose of reducing 
        time complexity and memory usage.  
        </td> 
    </tr>
    

    </table>
</td> </tr> </tbody>
</table> -->


