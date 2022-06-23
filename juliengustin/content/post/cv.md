---
layout:     post
title:      "Curriculum Vitae"
subtitle:   "About me and my projects"
date:       2022-06-23
author:     "Julien"
description: "My name is Julien Gustin I am 22 and I am currently pursuing master studies in Data Science at @Uliege in Belgium. I am passionate about AI and more mostly about deep learning, during my free time I like photographie, traveling, hiking and climbing."
# image:      "httpes://img.zhaohuabing.com/post-bg-2015.jpg"
---



# About me

My name is Julien Gustin I am 22 and I am currently pursuing master studies in Data Science at [@Uliege](https://www.uliege.be/cms/c_8699436/en/portail-uliege) in Belgium. I am passionate about AI and more mostly about deep learning, during my free time I like photographie, traveling, hiking and climbing. 


---
# Education

- MSc. in Data Science | [University of Liege](https://www.uliege.be/cms/c_8699436/en/portail-uliege)
  - 2021 - 2023
- BSc. in Computer Science | [University of Liege](https://www.uliege.be/cms/c_8699436/en/portail-uliege)
  - 2018 - 2021

--- 
# Projects

### [Image colorization](https://github.com/Julien-Gustin/Image-Colorization)

Given a grayscale image, we automatically colorize it without any user input. To achieve so, we built and trained a conditional generative adversarial network (cGAN) from scratch. Our neural network has to understand the different elements present on an image (segmentation) and recolor them in a coherent way for a human. We started from an architecture that has already proven itself from existing works (cfr. Pix2Pix). Understand the architecture in depth, then try variations in order to make it ours and improve it.

![colorization](/img/sky.png)


<p align="center">
    <img src="https://github.com/Julien-Gustin/RL-INFO8003/blob/master/gif/optimal_policy.gif" width="600" height="400" />
    <br>
    <em>Agent trained for 500 epochs using DDPG algorithm and gamma set to 0.99</em>
</p>

### [Smart-Heating](https://github.com/Julien-Gustin/Smart-heating)

The objective of this project is to develop a thermal model of the building and to adjust the parameters of this model based on measurements of the building's ambient temperature, setpoint temperatures, outdoor temperature and heating outputs. Then to use this model to control the switches and the heating temperature with model predictive control (MPC) in order to minimise the temperature difference between the room temperature and the setpoint temperature.


![heater](/img/projects/heater/kitchen.png)


### [Inverted double pendulum](https://github.com/Julien-Gustin/Inverted-Double-pendulum)

The Double Inverted Pendulum consists of two joint pendulums connected to a cart that is moving on a track, the agent needs to keeps in equilibrium the Double Inverted Pendulum by interacting with the environment by applying an horizontal force on a cart. At each transition, additionally to the reward given by the environment, the agent receives a positive, constant signal. A terminal state of the environment is reached when the distance between the upright and the current state is above a given thresold.

![pendule](/img/projects/pendulum/pendule.png)


**More projects are available on my [github](https://github.com/Julien-Gustin)**

---

# Link to PDF version

[CV](/img/Julien_Gustin_CV.pdf)