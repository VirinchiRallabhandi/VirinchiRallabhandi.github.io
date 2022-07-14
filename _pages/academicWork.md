---
layout: archive
title: "Academic work"
permalink: /academicWork/
author_profile: true
---

{% include base_path %}

{% for post in site.academicWork reversed %}
  {% include archive-single.html %}
{% endfor %}
