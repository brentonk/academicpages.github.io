---
layout: archive
title: "Working Papers"
permalink: /papers/
author_profile: true
---

If you plan to cite or circulate one of the papers here, please email me first to see if there is a more recent draft available.

{% include base_path %}

{% for post in site.papers reversed %}
  {% include archive-single-paper.html %}
{% endfor %}

