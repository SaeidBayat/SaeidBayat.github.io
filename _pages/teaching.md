---
layout: default
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<h2>Teaching & Mentoring</h2>

<ul>
  {% for item in site.teaching %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a><br/>
      {{ item.excerpt }}
    </li>
  {% endfor %}
</ul>
