---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<br>
<small>**EdgeVib: Effective Alphanumeric Character Output Using a Wrist-Worn Tactile Display**<br>
**Yi-Chi Liao**, Yi-Ling Chen, Jo-Yu Lo, Rong-Hao Liang, Liwei Chan, Bing-Yu Chen <br>
In Proc. UIST 2016, page 595 - 601. </small><br>
<small>[[Project Page](https://yichiliao.github.io/portfolio/portfolio-1/)] , [[Paper](http://yichiliao.github.io/files/edgevib_uist16.pdf)] , [[video](https://www.youtube.com/watch?v=Q_2owlSeDg4)] , [[Presentation](https://www.youtube.com/watch?v=4aogj5g-Ft0)] , [[Slide](https://goo.gl/mpHQ70)]</small>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
