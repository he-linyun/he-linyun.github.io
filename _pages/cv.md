---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
last update: October, 2026

{% assign cv_version = site.time | date: '%Y%m%d%H%M%S' %}
{% capture cv_url %}{{ site.baseurl }}/files/CV-Linyun_He.pdf?v={{ cv_version }}{% endcapture %}

If file does not load, please try <a href="{{ cv_url }}">here</a>.

<embed src="{{ cv_url }}" style="width: 100%; max-width: 800px;" height="1000" type='application/pdf'>
