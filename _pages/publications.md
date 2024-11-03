---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

The focus of my research is on creating and analyzing simulation-based decision-making algorithms and experiment designs, particularly under <i>model risks</i>.
I explore both the theoretical foundations and practical applications of operations research and machine learning.

Below is a list of my articles.
You can also find them on my <a href="{{site.author.googlescholar}}">Google Scholar</a> profile.

<h2 class="archive__item-title" itemprop="headline"> Publications</h2>
<ol reversed>
  {% for post in site.publications reversed %}
    {% if post.status == "published" or post.status == "accepted" %}
      <li> {% include linyun-publication-single.html %} </li>
    {% endif %}
  {% endfor %}
</ol>

<h2 class="archive__item-title" itemprop="headline"> Preprints and Working Papers </h2>
<ol reversed>
  {% for post in site.publications reversed %}
    {% if post.status == "arxiv" or post.status == "submitted" or post.status == "revision" or post.status == "preparing" %}
      <li> {% include linyun-preprint-single.html %} </li>
    {% endif %}
  {% endfor %}
</ol>
