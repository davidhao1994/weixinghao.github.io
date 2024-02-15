---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

{% include base_path %}

<div align="center">
<table><tr>
{% for i in (1..5) %}
  {% capture image_name %}image{{i}}.jpg{% endcapture %}
  <td style="padding:10px">
    <img src="https://davidhao1994.github.io/weixinghao.github.io/images/gallery/{{ image_name }}" alt="Image {{i}}" style="width:150px;"/>
  </td>
  {% if i | modulo: 3 == 0 %}
    </tr><tr>
  {% endif %}
{% endfor %}
</tr></table>
</div>


