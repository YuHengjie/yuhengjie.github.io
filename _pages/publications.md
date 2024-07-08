---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}


## 2024
{% for post in site.publications reversed %}
  {% if post.year == 2024 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## 2023
{% for post in site.publications reversed %}
  {% if post.year == 2023 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## 2022
{% for post in site.publications reversed %}
  {% if post.year == 2022 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## 2021
{% for post in site.publications reversed %}
  {% if post.year == 2021 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
