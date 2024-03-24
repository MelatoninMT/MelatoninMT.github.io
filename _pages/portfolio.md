---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: fault
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
