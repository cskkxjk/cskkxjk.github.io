---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## 2023

{% for post in site.publications reversed %}
  {% if post.year == '2023' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
