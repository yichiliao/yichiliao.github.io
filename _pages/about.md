---
permalink: /
title: ""
excerpt: "Yi-Chi Liao's homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# **Yi-CHi Liao (廖以圻)**
**Postdoctoral fellow in [SIPLab](https://siplab.org/) (led by [Prof. Christian Holz](https://www.christianholz.net/)) at [ETH Zürich](https://ethz.ch/en.html), supported by the [ETH Zürich Postdoctoral Fellowship Programme](https://ethz.ch/en/research/research-promotion/eth-fellowships.html)** 

------ 

**I develop computational methods that transform interactive systems from static artifacts into adaptive systems that learn and optimize through interaction with humans.**
My research sits at the intersection of computational interaction and design optimization. 
Building on Bayesian optimization, reinforcement learning, user simulation, meta-learning, and related techniques, I advance **human-in-the-loop optimization** methods that enable interfaces to automatically and efficiently optimize themselves for different users during use. My ultimate goal is to advance human-in-the-loop optimization as the foundation for **future adaptive interfaces and scalable human–AI collaboration**.
<br>
<br>
I have published 17 full papers in top-tier venues, including ACM CHI, UIST, TiiS, IEEE PerComp, and ICCV. 
My work has contributed to a wide range of application domains, such as physical interaction, haptic displays, AR/VR interfaces, input techniques, visual design, and motion generation and reconstruction.
Below are selected key papers. A complete publication list can be found on my [Publications page](https://yichiliao.com/publications/) or my [Google Scholar profile](https://scholar.google.com/citations?user=Ddny4V4AAAAJ&hl=en). 
For a detailed overview of my research agenda and future directions, see my [Research Statement (PDF)](https://yichiliao.com/files/Research-Statement_LIAO.pdf).
<br>
<br>
Previously, I was a postdoctoral researcher at [Saarland University](https://www.uni-saarland.de/en/home.html) (with [Prof. Jürgen Steimle](https://hci.cs.uni-saarland.de/people/juergen-steimle/) and [Prof. Anna Feit](http://annafeit.de/)). I completed my Ph.D. studies at [Aalto University](https://www.aalto.fi/en) (supervised by [Prof. Antti Oulasvirta](https://users.aalto.fi/~oulasvir/)) on [Human-in-the-Loop Design Optimization (dissertation PDF)](https://drive.google.com/file/d/1UcH6LuV7GiyRMvrVb9EZ34z-FeGPDBS7/view?usp=sharing). I worked as a research intern at Reality Labs Research, Meta during my Ph.D. studies.
<br>
<br>
Please feel free to reach out via [email](mailto:yichi.liao@inf.ethz.ch) for more information about my research, potential collaborations, master’s and bachelor’s thesis opportunities, or the *Adaptive User Interfaces via Machine Learning* and *Reinforcement Learning for Modeling Humans* seminars at ETH Zurich.


------

Selected Publications 
======
<br>
**Preference-Guided Multi-Objective UI Adaptation (UIST '25)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/4b2kIEvvpAA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

3D Mixed Reality interfaces have nearly unlimited space for layout placement, making automatic UI adaptation crucial for enhancing the user experience. Such adaptation is often formulated as a multi-objective optimization (MOO) problem, where multiple, potentially conflicting design objectives must be balanced. We propose a novel optimization approach that efficiently determines user preferences from a minimal number of UI element adjustments. These determined rankings are translated into priority levels, which then drive our priority-based MOO algorithm. By focusing the search on user-preferred solutions, our method not only identifies UIs that are more aligned with user preferences, but also automatically and efficiently selects the personalized design.

*Yao Song, Christoph Gebhardt, <u>Yi-Chi Liao</u>, Christian Holz*<br>
*In Proc. UIST '25 // 
[[Project Page](https://siplab.org/projects/Preference-guided_UI_Adaptation)], [[Paper](https://arxiv.org/abs/2509.18960)], [[Video](https://www.youtube.com/watch?v=4b2kIEvvpAA)]*


------


<br>
**Efficient Visual Appearance Optimization by Learning from Prior Preferences (UIST '25)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Y5xcQQJk-O0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Adjusting visual parameters such as brightness and contrast is common in our everyday experiences. 
Finding the optimal parameter setting is challenging due to the large search space and the lack of an explicit objective function, leaving users to rely solely on their implicit preferences. 
We propose Meta-PO, a novel method that integrates Preferential Bayesian Optimization with meta-learning to improve sample efficiency. Specifically, Meta-PO infers prior users’ preferences and stores them as models, which are leveraged to intelligently suggest design candidates for the new users, enabling rapid convergence and more personalized visual filter design. 

*Zhipeng Li, <u>Yi-Chi Liao</u>, Christian Holz*<br>
*In Proc. UIST '25 // 
[[Project Page](https://siplab.org/projects/Visual_Appearance_Optimization)], [[Paper](https://arxiv.org/abs/2507.15355)], [[Video](https://www.youtube.com/watch?v=Y5xcQQJk-O0)]*


------

<br>
**Continual Human-in-the-Loop Optimization (CHI '25, Honorable Mentioned)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/_lMF20yep3s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

While human-in-the-loop optimization has the potential to identify optimal settings during use, it is rarely applied in practice due to its long optimization process. A more efficient approach would continually leverage data from previous users to accelerate optimization, exploiting shared traits while adapting to individual characteristics. We introduce the concept of Continual Human-in-the-Loop Optimization and a Bayesian optimization-based method that leverages a Bayesian-neural-network surrogate model to capture population-level characteristics while adapting to new users. 

*<u>Yi-Chi Liao</u>, Paul Streli, Zhipeng Li, Christoph Gebhardt, Christian Holz*<br>
*In Proc. CHI '25 **Honorable Mentioned Award** // 
[[Project Page](https://siplab.org/projects/Redefining_Affordance)], [[Paper](https://arxiv.org/abs/2503.05405)], [[Video](https://www.youtube.com/watch?v=_lMF20yep3s)]*

------

<br>
**Group Inertial Poser: Multi-Person Pose and Global Translation from Sparse Inertial Sensors and Ultra-Wideband Ranging (ICCV '25)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/6PrZR7REcQg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Tracking human full-body motion using sparse wearable inertial measurement units (IMUs) overcomes the limitations of occlusion and instrumentation of the environment inherent in vision-based approaches. We present a novel approach for robustly estimating body poses and global translation for multiple individuals by leveraging the distances between sparse wearable sensors-both on each individual and across different people. Our method Group Inertial Poser estimates these absolute distances between pairs of sensors from ultra-wideband ranging (UWB) and fuses them with inertial observations as input into structured state-space models to integrate temporal motion patterns for precise 3D pose estimation. Our novel two-step optimization further leverages the estimated distances for accurately tracking people's global trajectories through the world.

*Ying Xue, Jiaxi Jiang, Rayan Armani, Dominik Hollidt, <u>Yi-Chi Liao</u>, Christian Holz*<br>
*In Proc. ICCV '25 // 
[[Project Page](https://siplab.org/projects/GroupInertialPoser)], [[Paper](https://arxiv.org/abs/2510.21654)], [[Video](https://www.youtube.com/watch?v=6PrZR7REcQg)]*


------

<br>
**Redefining Affordance via Computational Rationality (IUI '25)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/6gGQF2cTdk0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This paper introduces a novel affordance theory grounded in Computational Rationality, positing that humans construct internal representations of the world based on bounded sensory inputs. Within these internal models, affordances are inferred through two core mechanisms: feature recognition and hypothetical motion trajectories. Our theory redefines affordance perception as a decision-making process, driven by two components: confidence (the perceived likelihood of successfully executing an action) and predicted utility (the expected value of the outcome). By balancing these factors, individuals make informed decisions about which actions to take. 

*<u>Yi-Chi Liao</u>, Christian Holz*<br>
*In Proc. IUI '25 // 
[[Project Page](https://siplab.org/projects/Redefining_Affordance)], [[Paper](https://arxiv.org/abs/2501.09233)], [[Video](https://www.youtube.com/watch?v=6gGQF2cTdk0)]*


------
<br>
**A Meta-Bayesian Approach for Rapid Online Parametric Optimization for Wrist-based Interactions (CHI '24)** <br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/pxLGCKIEhjc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Wrist-based input often requires tuning parameter settings in correspondence to between-user and between-session differences, such as variations in hand anatomy, wearing position, posture, etc. We propose an online Bayesian Optimization (BO)-based method for rapidly determining the user-specific optimal settings of wrist-based pointing. Specifically, we develop a meta-Bayesian optimization (meta-BO) method, differing from traditional human-in-the-loop BO: By incorporating meta-learning of prior optimization data from a user population with BO, meta-BO enables rapid calibration of parameters for new users with a handful of trials. 

*<u>Yi-Chi Liao</u>, Ruta Desai, Alec M Pierce, Krista E Taylor, Hrvoje Benko, Tanya R Jonker, Aakar Gupta*<br>
*In Proc. CHI '24 // 
[[Project Page](https://dl.acm.org/doi/full/10.1145/3613904.3642071)], [[Paper](https://dl.acm.org/doi/pdf/10.1145/3613904.3642071)], [[Video](https://www.youtube.com/watch?v=pxLGCKIEhjc)],  [[Presentation](https://www.youtube.com/watch?v=2mcCpN3DCyM)]*


------

<br>
**Real-time 3D Target Inference via Biomechanical Simulation (CHI '24, Honorable Mentioned)** <br> 
<iframe width="560" height="315" src="https://www.youtube.com/embed/f9QA-ElytQc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Selecting a target in a 3D environment is often challenging, especially with small/distant targets or when sensor noise is high. To facilitate selection, target-inference methods must be accurate, fast, and account for noise and motor variability. We propose a novel approach that leverages biomechanical simulation to produce synthetic motion data, capturing a variety of movement-related factors, such as limb configurations and motor noise. Then, an inference model is trained with only the simulated data. Our simulation-based approach improves transfer and lowers cost; variety-rich data can be produced in large quantities for different scenarios. 


*Hee-Seung Moon, <u>Yi-Chi Liao</u>, Chenyu Li, Byungjoo Lee, Antti Oulasvirta<br>*
*In Proc. CHI '24 **Honorable Mentioned Award** // 
[[Project Page](https://dl.acm.org/doi/full/10.1145/3613904.3642131)], [[Paper](https://dl.acm.org/doi/pdf/10.1145/3613904.3642131)], [[Presentation](https://www.youtube.com/watch?v=f9QA-ElytQc)]*


------

<br>
**Rediscovering Affordance: A Reinforcement Learning Perspective (CHI '22)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/MqzKMCnJt38" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

We propose an integrative theory of affordance-formation based on the theory of reinforcement learning in cognitive sciences. The key assumption is that users learn to associate promising motor actions to percepts via experience when reinforcement signals (success/failure) are present. They also learn to categorize actions (e.g., "rotating" a dial), giving them the ability to name and reason about affordance. Upon encountering novel widgets, their ability to generalize these actions determines their ability to perceive affordances. We implement this theory in a virtual robot model, which demonstrates human-like adaptation of affordance in interactive widgets tasks. While its predictions align with trends in human data, humans are able to adapt affordances faster, suggesting the existence of additional mechanisms.


*<u>Yi-Chi Liao</u>, Kashyap Todi, Aditya Acharya, Antti Keurulainen, Andrew Howes, Antti Oulasvirta<br>*
*In Proc. CHI '22 // 
[[Project Page](https://yichiliao.github.io/portfolio/7-affordance/)], [[Paper](https://arxiv.org/pdf/2112.12886.pdf)], [[Video](https://www.youtube.com/watch?v=MqzKMCnJt38)],  [[Full Video](https://www.youtube.com/watch?v=VNAcp-iC9tQ)]*

------

<br>
**Investigating Positive and Negative Qualities of Human-in-the-Loop Optimization for Designing Interaction Techniques (CHI '22, Honorable Mentioned)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/uK4o_2VY90E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In this paper, we study Bayesian optimization as an algorithmic method to guide the design optimization process. It operates by proposing to a designer which design candidate to try next, given previous observations. We report observations from a comparative study with 40 novice designers who were tasked to optimize a complex 3D touch interaction technique. The optimizer helped designers explore larger proportions of the design space and arrive at a better solution, however they reported lower agency and expressiveness. Designers guided by an optimizer reported lower mental effort but also felt less creative and less in charge of the progress. We conclude that human-in-the-loop optimization can support novice designers in cases where agency is not critical.


*Liwei Chan, <u>Yi-Chi Liao</u>, George B. Mo, John J. Dudley, Chun-Lien Cheng, Per Ola Kristensson, Antti Oulasvirta*<br>
*In Proc. CHI '22 **Honorable Mentioned Award** //
[[Project Page](https://yichiliao.github.io/portfolio/8-investigating/)], [[Paper](https://arxiv.org/pdf/2204.07641.pdf)], [[Video](https://youtu.be/uK4o_2VY90E)],  [[Full Video](https://www.youtube.com/watch?v=T8ijVKkajwg)]*

------


<br>
**Button Simulation and Design via FDVV Models (CHI '20)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gE7v3Ai5bFk" frameborder="0" allowfullscreen></iframe>


Designing a push-button with desired sensation and performance is challenging because the mechanical construction must have the right response characteristics. In this paper, we extend the typical force-displacement (FD) modeling to include vibration (V) and velocity-dependence characteristics (V). The resulting FDVV models better capture tactility characteristics of buttons. They increase the range of simulated buttons and the perceived realism relative to FD models. The paper also demonstrates methods for obtaining these models, editing them, and simulating accordingly. Our approach enables the analysis, prototyping, and optimization of buttons, and supports exploring designs that would be hard to implement mechanically.


*<u>Yi-Chi Liao</u>, Sunjun Kim, Byungjoo Lee, Antti Oulasvirta<br>*
*In Proc. CHI '20 // 
[[Project Page](https://yichiliao.github.io/portfolio/0-buttondesign/)], [[Paper](http://yichiliao.github.io/files/dwellplus_uist17.pdf)], [[30s Video](https://www.youtube.com/watch?v=gE7v3Ai5bFk)], [[Full Video](https://www.youtube.com/watch?v=hOi_7O7USaI)]*

------

<br>
**Dwell+: Multi-Level Mode Selection Using Vibrotactile Cues (UIST '17)**<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/E90wT4RwuSk" frameborder="0" allowfullscreen></iframe>


This paper presents Dwell+, a method that boosts the effectiveness of typical dwell select by augmenting the passive dwell duration with active haptic ticks which promptly drives rapid switches of modes forward through the user's skin sensation. Dwell+ enables multi-level dwell select using rapid haptic ticks. To select a mode from a button, users dwell-touch the button until the mode of selection being haptically prompted. Applications demonstrated implementing Dwell+ across different interfaces; ranging from vibration-enabled touchscreens to non-vibrating interfaces. 

*<u>Yi-Chi Liao</u>, Yen-Chiu Chen,Liwei Chan, Bing-Yu Chen <br>*
*In Proc. UIST '17 // 
[[Project Page](https://yichiliao.github.io/portfolio/1-dwellplus/)], [[Paper](http://yichiliao.github.io/files/dwellplus_uist17.pdf)], [[30s Video](https://youtu.be/E90wT4RwuSk)], [[Full Video](https://www.youtube.com/watch?v=SHxr5JcYqy8)]* 

------

<br>
**EdgeVib: Effective Alphanumeric Character Output Using a Wrist-Worn Tactile Display (UIST '16)**<br>

Yi-Chi Liao, Yi-Ling Chen, Jo-Yu Lo, Rong-Hao Liang, Liwei Chan, Bing-Yu Chen

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_2owlSeDg4" frameborder="0" allowfullscreen></iframe>


Transferring rich tactile messages while retaining the recognition rates has been a major challenge in the development of tactile displays. We present EdgeVib, a set of multistroke alphanumeric patterns based on EdgeWrite. Learning these patterns takes comparable period to learning Graffiti (15min), while the recognition rates achive 85.9% and 88.6% for alphabet and digits respectively.

*<u>Yi-Chi Liao</u>, Yi-Ling Chen, Jo-Yu Lo, Rong-Hao Liang, Liwei Chan, Bing-Yu Chen <br>*
*In Proc. UIST '16 // 
[[Project Page](https://yichiliao.github.io/portfolio/3-edgevib/)], [[Paper](https://yichiliao.github.io/files/edgevib_uist16.pdf)], [[Video](https://www.youtube.com/watch?v=Q_2owlSeDg4)].* 


------
# Academic Activities


**Program Committee:** <br>
ACM CHI 2024 - 2026 Paper<br>
ACM UIST 2024 - 2026 Paper<br>
ACM CHI 2021 - 2022 Late-Breaking Work<br>
ACM TEI 2022 Work-in-Progress<br>

**Organizing Committee:** <br>
ACM CHI 2022 - 2024 Video Preview Chair<br>
ACM IUI 2022 Student Volunteer Chair<br>

**Special Recognitions for Outstanding Reviews:** <br>
1 x recognition for CHI 2026 Paper <br>
1 x recognition for IUI 2025 Paper <br>
2 x recognitions for CHI 2024 Late-Breaking Work <br>
1 x recognition for UIST 2022 Paper <br>
3 x recognition for CHI 2021 Papers <br>
1 x recognition for CHI 2020 Paper <br>

I constantly review papers for top-tier venues, including ACM CHI, UIST, TEI, MobileHCI, ToCHI, IJHCS, IEEE Transactions on Haptics, Haptics Symposium, etc. Please see my [CV (PDF)](https://yichiliao.com/files/YiChi_Liao.pdf) for more details.
<br>

------

# Teaching

At **ETH Zürich**, I teach and organize courses that introduce computational and learning-based perspectives to Human–Computer Interaction at both undergraduate and graduate levels. I lecture in the Bachelor’s *Introduction to Human-Computer Interaction* course, covering core topics in computational interaction, including visual search and design, input devices, experiment design, adaptive interfaces, optimization, and computational rationality. These lectures emphasize how formal models and learning methods can be used to analyze and design interactive systems.

I am also the organizer for two seminar courses at ETH Zürich: *Adaptive User Interfaces via Machine Learning* (undergraduate) and *Reinforcement Learning for Modeling Humans* (graduate). In these seminars, students read and discuss recent research, critically analyze methods, and develop research ideas, with a strong focus on connecting theory and machine learning approaches to emerging HCI topics.

Previously at **Aalto University**, I lectured in the Master’s-level *Computational Interface Design* course, teaching topics such as input and sensing, Bayesian optimization, deep learning for HCI, and probabilistic inference. I also gave guest lectures in *User Research* on Bayesian statistics and probabilistic programming, introducing rigorous statistical foundations for user-centered research and evaluation.


------

# Supervision and Thesis Opportunities

I always welcome motivated students from **ETH Zürich** and the **University of Zurich** to conduct Bachelor’s and Master’s theses with me. I am particularly happy to supervise thesis projects related to computational interaction, adaptive user interfaces, human–AI interaction, and optimization- and learning-based approaches to support interface design. Previously, students I have supervised and supported have gone on to publish their work at top-tier international conferences. I encourage students who are interested in research-oriented projects to reach out to me via [email](mailto:yichi.liao@inf.ethz.ch) with your transcript and CV.
