---
layout: archive  # Use the layout that fits your theme and needs.
title: "Research Projects"
permalink: /research/
author_profile: true  # If you're using a theme that supports author profiles and yo
---

{% include base_path %}


{% for post in site.research reversed %}
  <div class="post-preview">
    <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt | strip_html }}</p>
    <div style="text-align: center;">
      <a href="{{ site.baseurl }}{{ post.url }}">
        <img src='https://davidhao1994.github.io/weixinghao.github.io/images/research-project-1.jpg' alt='Example Image' width='200' />
         <img src='https://davidhao1994.github.io/weixinghao.github.io/images/research-project-2.jpg' alt='Example Image' width='400' />
         <img src='https://davidhao1994.github.io/weixinghao.github.io/images/research-project-3.jpg' alt='Example Image' width='500' />
          <img src='https://davidhao1994.github.io/weixinghao.github.io/images/research-project-4.jpg' alt='Example Image' width='500' />
    </div>
    </div>
      </a>
    </div>
  </div>
{% endfor %}



