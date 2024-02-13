---
layout: archive  # Use the layout that fits your theme and needs.
title: "Research Projects"
excerpt: "About me"
permalink: /research/
author_profile: true  # If you're using a theme that supports author profiles and you want it to appear on this page.
---

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
