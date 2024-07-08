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

<div style="margin-top: 0; margin-bottom: 40px;"></div>  

## 2024
<div style="margin-top: 0; margin-bottom: 20px;"></div>  
{% for post in site.publications reversed %}
  {% if post.year == 2024 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## 2023
<div style="margin-top: 0; margin-bottom: 20px;"></div>  
{% for post in site.publications reversed %}
  {% if post.year == 2023 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## 2022
<div style="margin-top: 0; margin-bottom: 20px;"></div>  
{% for post in site.publications reversed %}
  {% if post.year == 2022 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## 2021
<div style="margin-top: 0; margin-bottom: 20px;"></div> 
{% for post in site.publications reversed %}
  {% if post.year == 2021 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
