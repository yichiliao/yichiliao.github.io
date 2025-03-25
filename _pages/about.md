---
permalink: /
title: ""
excerpt: "Yi-Chi Liao's homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# Moi (Hello in Finnish)! This is Yi-Chi!
<br>
<small>
I’m a postdoc researcher in the [SIP Lab](https://siplab.org/) at [ETH Zürich](https://ethz.ch/en.html) (led by [Prof Christian Holz](https://www.christianholz.net/)) fully funded by the [ETH Zürich Postdoc Fellowship Programme](https://ethz.ch/en/research/research-promotion/eth-fellowships.html). I **advance human-in-the-loop optimization (HILO) frameworks for adaptive systems and streamlined human-AI co-design workflows**. HILO is a broad concept where the computational models learn directly from human performance, preferences, and feedback, iteratively improving designs with real-time observations. I advance HILO in three directions: (1) *Improving its efficiency for real-time interface adaptation*, (2) *Expanding the application scope of HILO to enable better human-AI co-design*, and (3) *Developing realistic human motion simulation to further enhance HILO*. I received my Ph.D. degree from [Aalto University](https://www.aalto.fi/en) (supervised by [Prof Antti Oulasvirta](https://users.aalto.fi/~oulasvir/)) with [**Human-in-the-Loop Design Optimization**](https://drive.google.com/file/d/1UcH6LuV7GiyRMvrVb9EZ34z-FeGPDBS7/view?usp=sharing). Previously, I was a postdoc researcher at [Saarland University](https://www.uni-saarland.de/en/home.html), supervised by both [Prof Jürgen Steimle](https://hci.cs.uni-saarland.de/people/juergen-steimle/) and [Prof Anna Feit](http://annafeit.de/). I also worked at [Meta Rality Labs](https://tech.fb.com/ar-vr/) as a research intern. Even before that, I received my bachelor’s and master’s degree at [National Taiwan University](https://www.ntu.edu.tw/english/). I have made [14 full-paper publications](https://scholar.google.com/citations?user=Ddny4V4AAAAJ&hl=en) in top-tier venues, including ACM CHI, UIST, TiiS, and IEEE PerCom. I have been serving as an Associate Chair for CHI and UIST, and was Video Preview Chair for CHI and Student Volunteer Chair for IUI. I also gave lectures on broad topics related to HCI and Computational Design.
</small>

------

Selected Publications (Last update: June, 2024)
======
<br>
**A Meta-Bayesian Approach for Rapid Online Parametric Optimization for Wrist-based Interactions** *[CHI '24, 38-page Paper]*<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/pxLGCKIEhjc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<small>
Wrist-based input often requires tuning parameter settings in correspondence to between-user and between-session differences, such as variations in hand anatomy, wearing position, posture, etc. Traditionally, users either work with predefined parameter values not optimized for individuals or undergo time-consuming calibration processes. We propose an online Bayesian Optimization (BO)-based method for rapidly determining the user-specific optimal settings of wrist-based pointing. Specifically, we develop a meta-Bayesian optimization (meta-BO) method, differing from traditional human-in-the-loop BO: By incorporating meta-learning of prior optimization data from a user population with BO, meta-BO enables rapid calibration of parameters for new users with a handful of trials. We evaluate our method with two representative and distinct wrist-based interactions: absolute and relative pointing. On a weighted-sum metric that consists of completion time, aiming error, and trajectory quality, meta-BO improves absolute pointing performance by 22.92% and 21.35% compared to BO and manual calibration, and improves relative pointing performance by 25.43% and 13.60%.
</small>

<small>In Proc. CHI '24 // 
[[Project Page](https://dl.acm.org/doi/full/10.1145/3613904.3642071)], [[Paper](https://dl.acm.org/doi/pdf/10.1145/3613904.3642071)], [[Video](https://www.youtube.com/watch?v=pxLGCKIEhjc)],  [[Presentation](https://www.youtube.com/watch?v=2mcCpN3DCyM)]</small>


<br>
**Real-time 3D Target Inference via Biomechanical Simulation** *[CHI '24, 18-page Paper]*<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/f9QA-ElytQc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<small>
Selecting a target in a 3D environment is often challenging, especially with small/distant targets or when sensor noise is high. To facilitate selection, target-inference methods must be accurate, fast, and account for noise and motor variability. However, traditional data-free approaches fall short in accuracy since they ignore variability. While data-driven solutions achieve higher accuracy, they rely on extensive human datasets so prove costly, time-consuming, and transfer poorly. In this paper, we propose a novel approach that leverages biomechanical simulation to produce synthetic motion data, capturing a variety of movement-related factors, such as limb configurations and motor noise. Then, an inference model is trained with only the simulated data. Our simulation-based approach improves transfer and lowers cost; variety-rich data can be produced in large quantities for different scenarios. We empirically demonstrate that our method matches the accuracy of human-data-driven approaches using data from seven users. When deployed, the method accurately infers intended targets in challenging 3D pointing conditions within 5–10 milliseconds, reducing users' target-selection error by 71% and completion time by 35%.
</small>

<small>In Proc. CHI '24 // 
[[Project Page](https://dl.acm.org/doi/full/10.1145/3613904.3642131)], [[Paper](https://dl.acm.org/doi/pdf/10.1145/3613904.3642131)], [[Presentation](https://www.youtube.com/watch?v=f9QA-ElytQc)]</small>


<br>
**Rediscovering Affordance: A Reinforcement Learning Perspective** *[CHI '22, 14-page Paper]*<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/MqzKMCnJt38" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<small>
We propose an integrative theory of affordance-formation based on the theory of reinforcement learning in cognitive sciences. The key assumption is that users learn to associate promising motor actions to percepts via experience when reinforcement signals (success/failure) are present. They also learn to categorize actions (e.g., "rotating" a dial), giving them the ability to name and reason about affordance. Upon encountering novel widgets, their ability to generalize these actions determines their ability to perceive affordances. We implement this theory in a virtual robot model, which demonstrates human-like adaptation of affordance in interactive widgets tasks. While its predictions align with trends in human data, humans are able to adapt affordances faster, suggesting the existence of additional mechanisms.
</small>

<small>In Proc. CHI '22 // 
[[Project Page](https://yichiliao.github.io/portfolio/7-affordance/)], [[Paper](https://arxiv.org/pdf/2112.12886.pdf)], [[Video](https://www.youtube.com/watch?v=MqzKMCnJt38)],  [[Full Video](https://www.youtube.com/watch?v=VNAcp-iC9tQ)]</small>

------

<br>
**Investigating Positive and Negative Qualities of Human-in-the-Loop Optimization for Designing Interaction Techniques** *[CHI '22, 13-page Paper, Honorable Mention]*<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/uK4o_2VY90E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<small>
In this paper, we study Bayesian optimization as an algorithmic method to guide the design optimization process. It operates by proposing to a designer which design candidate to try next, given previous observations. We report observations from a comparative study with 40 novice designers who were tasked to optimize a complex 3D touch interaction technique. The optimizer helped designers explore larger proportions of the design space and arrive at a better solution, however they reported lower agency and expressiveness. Designers guided by an optimizer reported lower mental effort but also felt less creative and less in charge of the progress. We conclude that human-in-the-loop optimization can support novice designers in cases where agency is not critical.
</small>

<small>In Proc. CHI '22 //
[[Project Page](https://yichiliao.github.io/portfolio/8-investigating/)], [[Paper](https://arxiv.org/pdf/2204.07641.pdf)], [[Video](https://youtu.be/uK4o_2VY90E)],  [[Full Video](https://www.youtube.com/watch?v=T8ijVKkajwg)]</small>

------


<br>
**Button Simulation and Design via FDVV Models** *[CHI '20, 10-page Paper]*<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gE7v3Ai5bFk" frameborder="0" allowfullscreen></iframe>

<small>
Designing a push-button with desired sensation and performance is challenging because the mechanical construction must have the right response characteristics. In this paper, we extend the typical force-displacement (FD) modeling to include vibration (V) and velocity-dependence characteristics (V). The resulting FDVV models better capture tactility characteristics of buttons. They increase the range of simulated buttons and the perceived realism relative to FD models. The paper also demonstrates methods for obtaining these models, editing them, and simulating accordingly. Our approach enables the analysis, prototyping, and optimization of buttons, and supports exploring designs that would be hard to implement mechanically.
</small>

<small>In Proc. CHI '20 // 
[[Project Page](https://yichiliao.github.io/portfolio/0-buttondesign/)], [[Paper](http://yichiliao.github.io/files/dwellplus_uist17.pdf)], [[30s Video](https://www.youtube.com/watch?v=gE7v3Ai5bFk)], [[Full Video](https://www.youtube.com/watch?v=hOi_7O7USaI)]. </small>

------

<br>
**Dwell+: Multi-Level Mode Selection Using Vibrotactile Cues** *[UIST '17, 10-page Paper]*<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/E90wT4RwuSk" frameborder="0" allowfullscreen></iframe>

<small>
This paper presents Dwell+, a method that boosts the effectiveness of typical dwell select by augmenting the passive dwell duration with active haptic ticks which promptly drives rapid switches of modes forward through the user's skin sensation. Dwell+ enables multi-level dwell select using rapid haptic ticks. To select a mode from a button, users dwell-touch the button until the mode of selection being haptically prompted. Applications demonstrated implementing Dwell+ across different interfaces; ranging from vibration-enabled touchscreens to non-vibrating interfaces. 
</small>

<small>In Proc. UIST '17 // 
[[Project Page](https://yichiliao.github.io/portfolio/1-dwellplus/)], [[Paper](http://yichiliao.github.io/files/dwellplus_uist17.pdf)], [[30s Video](https://youtu.be/E90wT4RwuSk)], [[Full Video](https://www.youtube.com/watch?v=SHxr5JcYqy8)]. </small>

------

<br>
**Outside-In: Visualizing Out-of-Sight Region-of-Interests in a 360 Video Using Spatial Picture-in-Picture Previews** <br>*[UIST '17, 9-page Paper]*<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/XyN1TRUhelw" frameborder="0" allowfullscreen></iframe>

<small>
We propose Outside-In, a visualization technique which re-introduces off-screen ROIs into the main screen as spatialpicture-in-picture (PIP) previews. The geometry of the pre-view windows further encodes the ROIs’ relative directions tothe main screen view, allowing for effective navigation. 
</small>

<small>In Proc. UIST '17 // 
[[Project Page](https://yichiliao.github.io/portfolio/2-outsidein/)], [[Paper](http://yichiliao.github.io/files/outsidein_uist17.pdf)], [[Video](https://www.youtube.com/watch?v=XyN1TRUhelw)].
</small>

------

<br>
**EdgeVib: Effective Alphanumeric Character Output Using a Wrist-Worn Tactile Display.** *[UIST '16, 6-page Paper]*<br>

<small>Yi-Chi Liao, Yi-Ling Chen, Jo-Yu Lo, Rong-Hao Liang, Liwei Chan, Bing-Yu Chen</small>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_2owlSeDg4" frameborder="0" allowfullscreen></iframe>

<small>
"Transferring rich spatialtemporal tactile messages while retaining the recognition rates" has been a major challenge in the development of tactile displays. We present EdgeVib, a set of multistroke alphanumeric patterns based on EdgeWrite. Learning these patterns takes comparable period to learning Graffiti (15min), while the recognition rates achive 85.9% and 88.6% for alphabet and digits respectively.
</small>

<small>In Proc. UIST '16 // 
[[Project Page](https://yichiliao.github.io/portfolio/3-edgevib/)], [[Paper](https://yichiliao.github.io/files/edgevib_uist16.pdf)], [[Video](https://www.youtube.com/watch?v=Q_2owlSeDg4)]. </small>

------

**ThirdHand: Wearing a Robotic Arm to Experience Rich Force Feedback.** *[Siggraph Asia'15 Emerging Technology]*<br> 

<small>Yi-Chi Liao, Shun-Yao Yang, Rong-Hao Liang, Liwei Chan, Bing-Yu Chen</small>

<iframe width="560" height="315" src="https://www.youtube.com/embed/sVRI0L7xu7E" frameborder="0" allowfullscreen></iframe>

<small>
ThirdHnad is a wearable robotic arm provides 5-DOF force feedback to enrich the mobile gaming experience. Comparing to traditional mounted-on-environment force-feedback devices such as phantom, ThirdHand provides higher mobility due to its wearable form. Also, comparing to the muscle-propelled and gyro-effect solutions, our approach enables more accurate control with stronger forces.
</small>

<small>In Proc. Siggraph Asia'15 Emerging Technology // 
[[Project Page](https://yichiliao.github.io/portfolio/5-thirdhand/)], [[Paper](http://yichiliao.github.io/files/thirdhand_sa15.pdf)], [[Video](https://www.youtube.com/watch?v=sVRI0L7xu7E)]. </small>

------



Academic Activities
======

<small>
**Program Committee:** <br>
ACM CHI 2024, 2025 Paper<br>
ACM UIST 2024, 2025 Paper<br>
ACM CHI 2021, 2022 Late-Breaking Work<br>
ACM TEI 2022 Work-in-Progress<br>
</small>
<br>

<small>
**Organizing Committee:** <br>
ACM CHI 2022 - 2024 Video Preview Chair<br>
ACM IUI 2022 Student Volunteer Chair<br>
</small>
<br>

<small>
**Paper Review:** <br>
IEEE Transactions on Haptics: 2019, 2021<br>
IEEE World Haptics Conference: 2021<br>
International Journal of Human - Computer Studies: 2021<br>
ACM CHI: 2016-2022 <br>
ACM Creativity and Cognition: 2021<br>
IEEE Haptics Symposium: 2020<br>
ACM MobileHCI: 2017-2020 <br>
ACM TEI: 2017-2018<br>
ACM UbiComp/ISWC: 2017<br>
Augmented Human: 2016-2017<br>
</small>
<br>
<small>
**Special Recognitions for Outstanding Reviews:** <br>
1 x recognition for IUI 2025 Papers <br>
2 x recognitions for CHI 2024 Late-Breaking Work <br>
1 x recognition for UIST 2022 Papers <br>
3 x recognition for CHI 2021 Papers <br>
1 x recognition for CHI 2020 Papers <br>
</small>

------

TEACHING
======


<small>
In 2020, I gave a lecture about **Bayesian Statistics** and its applications in _User Research_ course, Aalto University (by PhD. Aurélien Nioche). I also gave a lecture on **Deep Learning** in _Computational User Interface Design_, Aalto University (by Prof. Antti Oulasvirta).
</small>

<small>
In 2019, I gave a lecture in _Computational User Interface Design_ course, Aalto University (by Prof. Antti Oulasvirta) for introducing **Probilistic Decoding**. In another course, _Engineering for Humans_, Aalto University (by Prof. Antti Oulasvirta), I talked about **Input Sensing Pipeline and Data Processing**.
</small>

<small>
During 2014 to 2016, I've been a teaching assistant of _Introduction to HCI_ (lectured by [Prof. Rong-Hao Liang](http://www.cmlab.csie.ntu.edu.tw/~howieliang/) and [Prof. Bing-Yu Chen](https://www.cmlab.csie.ntu.edu.tw/~robin/)), and _Computer Architecture_ (lectured by [Prof. Bing-Yu Chen](https://www.cmlab.csie.ntu.edu.tw/~robin/)) in National Taiwan University.
</small>

