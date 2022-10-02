---
layout: archive
title: "Other musings"
permalink: /otherMusings/
author_profile: true
---
The following is a collection of some of the essays I have written over the years on topics unrelated to my academic work. The opinions expressed here are solely mine. They should not be interpreted as views held or endorsed by any institution I am currently affiliated to or any institution I have been affiliated to in the past.

{% include base_path %}

{% for post in site.otherMusings reversed %}
  {% include archive-single.html %}
{% endfor %}
