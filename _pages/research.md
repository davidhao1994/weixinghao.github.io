---
layout: archive  # Use the layout that fits your theme and needs.
title: "Research Projects"
permalink: /research/
author_profile: true  # If you're using a theme that supports author profiles and yo
---

{% include base_path %}

{% for post in site.research reversed %}
  <a href="{{ site.baseurl }}{{ post.url }}">
    <img src="https://davidhao1994.github.io/weixinghao.github.io/images/{{ post.slug }}.jpg" alt="{{ post.title }}" width="200" />
  </a>
{% endfor %}

