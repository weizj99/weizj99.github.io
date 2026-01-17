---
layout: archive
title: "Discussion & Others"
permalink: /discussions/
author_profile: true
---

{% include base_path %}

[UPF Macro Development Reading Group](https://www.upf.edu/web/econ/seminar-series)

## Conference Discussions
{% for post in site.discussions reversed %}
  {% if post.category == "conference" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Reading Group Discussions
{% for post in site.discussions reversed %}
  {% if post.category == "reading_group" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
