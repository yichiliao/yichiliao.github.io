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

------
<img src='/images/button/pipeline.png'>

## Abstract
Designing a push-button with desired sensation and performance is challenging because the mechanical construction must have the right response characteristics. Physical simulation of a button’s force-displacement (FD) response has been studied to facilitate prototyping; however, the simulations’ scope and realism have been limited. In this paper, we extend FD modeling to include vibration (V) and velocity-dependence characteristics (V). The resulting FDVV models better capture tactility characteristics of buttons, including snap. They increase the range of simulated buttons and the perceived realism relative to FD models. The paper also demonstrates methods for obtaining these models, editing them, and simulating accordingly. This end-to-end approach enables the analysis, prototyping, and optimization of buttons, and supports exploring designs that would be hard to implement mechanically.

<iframe width="560" height="315" src="https://www.youtube.com/embed/OL2x3RrWnv4" frameborder="0" allowfullscreen></iframe>

------
## Build your own simulator!
All the code, data of various buttons, and the contruction materials for the button simulator are open for anyone to use. [Download](https://userinterfaces.aalto.fi/button_design/resources/button_simulator.zip), and make your own simulator!

The package includes:
- Papaer and the auxiliary material in pdf.
- Data and Models of the 6 physical buttons (Cherry MX Clear, Brown, Black, Red, and HP PR1101U, MacBook Pro 2011).
- Simulator prototype (3D-printing models, electronic components, and step-by-step assembling instructions).
- Actuation signals to render them using our simulator.
- Source code for running the simulator.

**Publication:** <br> 
<medium>
CHI 2020, 10-page Paper // [[Paper](chi2020-liao-button)], [[30s video](https://www.youtube.com/watch?v=gE7v3Ai5bFk)], [[60s video](https://www.youtube.com/watch?v=hOi_7O7USaI)], [[Presentation](https://www.youtube.com/watch?v=v9p-yCNbxzw)]. 
<br>Yi-Chi Liao, Sunjun kim, Byungjoo Lee, and Antti Oulasvirta.
</medium>