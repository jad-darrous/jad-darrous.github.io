---
layout: archive
title: "Academic projects"
permalink: /projects/
author_profile: true
---


{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}