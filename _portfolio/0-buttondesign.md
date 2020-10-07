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


<img src='/images/dwellplus/teaser.jpg'>
<small>
Our haptic stimulation design consists of a short 10ms vibrotacile feedback that indicates a mode arriving and a break that separates consecutive modes. We first tested the effectiveness of 170ms 150ms, 130ms, 110ms intervals between modes for a 10-level selection. The results reveal that three-beat-per-chunk rhythm design, e.g., displaying longer 25ms vibration at the first of every three modes, could potentially bring higher accuracy. 
</small>

<img src='/images/dwellplus/dwell_vibpattern.png'>
<small>
The second user study reveals significant improvement where a 94.5% accuracy was achieved for a 10-level dwell++ select using the 170ms interval with 3-beat-per-chunk design, and a 93.82% accuracy using the faster 150ms interval with similar chunks for 5-level selection. 
</small>

<img src='/images/dwellplus/dwell_study3.png'>
<small>
The approximate performance of conducting touch and receiving vibration from different hands was investigated at the last study for providing a wider range of usage for Dwell++.
</small>

<img src='/images/dwellplus/dwell_applications.png'>

<small>
**Publication:** <br> 
UIST 2017, 12-page Paper // [[Paper](http://yichiliao.github.io/files/dwellplus_uist17.pdf)], [[video](https://youtu.be/E90wT4RwuSk)] 
<br>Yi-Chi Liao, Yen-Chiu Chen, Liwei Chan, Bing-Yu Chen</small>