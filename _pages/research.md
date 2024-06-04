---
layout: archive
title: "Publications"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Working Papers
======

JMP [[draft]](http://qddang.github.io/files/draft2.pdf')

Publications
======

Paper 1 [[paper]](http://qddang.github.io/files/CDKP_UK.pdf')

Paper 2 [[paper]](http://qddang.github.io/files/CDKP_USdebt_nber.pdf')
