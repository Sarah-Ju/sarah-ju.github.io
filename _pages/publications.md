---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://www.researchgate.net/profile/Sarah-Juricic">my Researchgate profile</a>.

Also, check out [*here*](https://sarah-ju.github.io/posts/2022/05/researchjourney/) a roadmap to my research journey (/!\under construction).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
