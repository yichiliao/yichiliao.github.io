---
title: "Button Simulation and Design via FDVV Models"
excerpt: "We introduced a novel model that better captures the haptic characteristics of push-buttons.<br/><img src='/images/dwellplus/dwellplusplus.png'><br><br>"
collection: portfolio
---

<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gE7v3Ai5bFk" frameborder="0" allowfullscreen></iframe>

------

## How to design the tactility of a button?

- Different push-buttons have varying haptic characteristics (tactility), which further leads to distinct sensations and user performance.
- We present a novel force-displacement-vibration-velocity (FDVV) model to capture the haptic characteristics of a button.
- We further introduce an end-to-end simulation pipeline that covers from measurements, modeling, controlling to real-time physical simulation.
- Several applications are enabled by our approach, including an interactive button-editing tool, software-side optimization, and designing innovative buttons.
- Want to build your own button simulator? Download our materials below and start designing your button!


<img src='/images/button/pipeline.png'>
<small>
Designing a push-button with desired sensation and performance is challenging because the mechanical construction must have the right response characteristics. Physical simulation of a button’s force-displacement (FD) response has been studied to facilitate prototyping; however, the simulations’ scope and realism have been limited. In this paper, we extend FD modeling to include vibration (V) and velocity-dependence characteristics (V). The resulting FDVV models better capture tactility characteristics of buttons, including snap. They increase the range of simulated buttons and the perceived realism relative to FD models. The paper also demonstrates methods for obtaining these models, editing them, and simulating accordingly. This end-to-end approach enables the analysis, prototyping, and optimization of buttons, and supports exploring designs that would be hard to implement mechanically.
</small>

<iframe width="560" height="315" src="https://www.youtube.com/embed/OL2x3RrWnv4" frameborder="0" allowfullscreen></iframe>

All the code, data of various buttons, and the contruction materials for the button simulator are open for anyone to use. You can download the whole package at once at button_simulator.zip. Then, build the simulator step-by-step based on the readme.pdf file. Alternatively, you can download the files separately as listed below.

<small>
**Publication:** <br> 
UIST 2017, 12-page Paper // [[Paper](http://yichiliao.github.io/files/dwellplus_uist17.pdf)], [[video](https://youtu.be/E90wT4RwuSk)] 
<br>Yi-Chi Liao, Yen-Chiu Chen, Liwei Chan, Bing-Yu Chen</small>