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

{% assign sorted_posts = site.publications | sort: 'date' | reverse %}
{% assign current_year = "" %}

{% for post in sorted_posts %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post_year != current_year %}
    {% assign current_year = post_year %}
    <h2>**{{ current_year }}**</h2>
  {% endif %}
  {% include archive-single.html %}
{% endfor %}