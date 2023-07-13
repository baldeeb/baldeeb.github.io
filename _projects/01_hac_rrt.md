---
layout: page
title: Planning with Hierarchical Reinforcement-Learning Agents
description: Motion Planning Course - Winter 2022 - Professor Dmitry Berenson
img: assets/img/hacrrt.png
importance: 1
category: Academic - Masters
---

I developed a Rapidly-Exploring Random-Tree (RRT) algorithm 
that used the intermediate layers of a Hierarchical-Actor-Critic (HAC) 
agent to model state propagation. In doing so, I demostrate the use of an 
RL agent for planning and the use of Q-fuctions to encourage
safer long-horizon plans.


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