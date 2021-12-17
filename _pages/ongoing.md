---
layout: archive
title: "Ongoing work"
permalink: /ongoing/
author_profile: true
---

{% include base_path %}

{% for post in site.ongoing reversed %}
  {% include archive-single.html %}
{% endfor %}
