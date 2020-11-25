---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}

## Work in progress
[Screening with behavioral buyers](https://nrpastrian.github.io/files/draft_screening_20201124.pdf) Last update: November 24, 2020
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
