---
layout: archive  # Use the layout that fits your theme and needs.
title: "Research Projects"
permalink: /research/
author_profile: true  # If you're using a theme that supports author profiles and yo
---

{% include base_path %}


{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

