---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<br>
<small>**Button Simulation and Design via FDVV Models**<br>
<u>Yi-Chi Liao</u>, Sunjun Kim, Byungjoo Lee, Antti Oulasvirta<br>
In Proc. CHI 2020. (Acceptance rate = 24.3%)</small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/0-buttondesign/)], [[Paper](/files/chi2020-liao-button.pdf)], [[video](https://www.youtube.com/watch?v=gE7v3Ai5bFk)],  [[full video](https://www.youtube.com/watch?v=hOi_7O7USaI)]</small>
  

<small>**One Button to Rule Them All: Rendering Arbitrary Force-Displacement Curves**<br>
<u>Yi-Chi Liao</u>, Sunjun Kim, xAntti Oulasvirta<br>
In Proc. UIST 2018 adjunct.</small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/0-buttondesign/)], [[Paper](https://dl.acm.org/doi/abs/10.1145/3266037.3266118)], [[video](https://www.youtube.com/watch?v=-CbhRR6199U)]</small>
  

<small>**Dwell+: Multi-Level Mode Selection Using Vibrotactile Cues**<br>
<u>Yi-Chi Liao</u>, Yen-Chiu Chen,Liwei Chan, Bing-Yu Chen <br>
In Proc. UIST 2017. (Acceptance rate = 22%)</small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/1-dwellplus/)], [[Paper](http://yichiliao.github.io/files/dwellplus_uist17.pdf)], [[video](https://www.youtube.com/watch?v=E90wT4RwuSk)],  [[full video](https://www.youtube.com/watch?v=SHxr5JcYqy8)]</small>
  

<small>**Outside-In: Visualizing Out-of-Sight Regions-of-Interest in a360 Video Using Spatial Picture-in-Picture Previews**<br>
Yung-Ta Lin, <u>Yi-Chi Liao</u>, Shan-Yuan Teng, Yi-Ju Chung, Liwei Chan, Bing-Yu Chen <br>
In Proc. UIST 2017. (Acceptance rate = 22%)</small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/2-outsidein/)], [[Paper](http://yichiliao.github.io/files/outsidein_uist17.pdf)], [[video](https://www.youtube.com/watch?v=tCeRS1ObPA8)]</small>
  

<small>**EdgeVib: Effective Alphanumeric Character Output Using a Wrist-Worn Tactile Display**<br>
<u>Yi-Chi Liao</u>, Yi-Ling Chen, Jo-Yu Lo, Rong-Hao Liang, Liwei Chan, Bing-Yu Chen <br>
In Proc. UIST 2016. (Acceptance rate = 20%) </small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/3-edgevib/)], [[Paper](http://yichiliao.github.io/files/edgevib_uist16.pdf)], [[video](https://www.youtube.com/watch?v=Q_2owlSeDg4)], [[Presentation](https://www.youtube.com/watch?v=4aogj5g-Ft0)], [[Slide](https://goo.gl/mpHQ70)]</small>
  

<small>**ThirdHand: Wearing a Robotic Arm to Experience Rich Force Feedback**<br>
<u>Yi-Chi Liao</u>, Shun-Yao Yang, Rong-Hao Liang, Liwei Chan, Bing-Yu Chen<br>
In Proc. Siggraph Asia 2015 Emerging Technology. (Acceptance rate = 30%). </small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/5-thirdhand/)], [[Paper](http://yichiliao.github.io/files/thirdhand_sa15.pdf)], [[video](https://www.youtube.com/watch?v=Q_2owlSeDg4)]</small>
  

<small>**fStrip: a Malleable Shape-retaining Wearable Strip for Interface On-demand**<br>
Chin-Yu Chien, Cheng-Yuan Li, Liwei Chan, <u>Yi-Chi Liao</u>, Rong-Hao Liang, Hao-Hua Chu, Bing-Yu Chen<br>
In Proc. UbiComp 2015 adjunct. </small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/6-fstrip/)], [[Paper](http://dl.acm.org/citation.cfm?id=2800883&CFID=944733130&CFTOKEN=32899269)]</small>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
