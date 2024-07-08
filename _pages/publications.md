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



# 2024

{% for post in sorted_posts %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post_year != current_year %}
    {% assign current_year = post_year %}
      {% if current_year == 2024 %}
        {% include archive-single.html %}
      {% endif %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}


# 2023

{% for post in sorted_posts %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post_year != current_year %}
    {% assign current_year = post_year %}
      {% if current_year == 2023 %}
        {% include archive-single.html %}
      {% endif %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

# 2022

{% for post in sorted_posts %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post_year != current_year %}
    {% assign current_year = post_year %}
      {% if current_year == 2022 %}
        {% include archive-single.html %}
      {% endif %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

# 2021

{% for post in sorted_posts %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post_year != current_year %}
    {% assign current_year = post_year %}
      {% if current_year == 2021 %}
        {% include archive-single.html %}
      {% endif %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}