---
layout: archive
title: "Releases"
permalink: /releases/
author_profile: true
---

{% if site.author.github %}
  You can find my releases on <u><a href="https://github.com/domidt/">my Github repositories</a>.</u>
{% endif %}

{% for post in site.releases reversed %}
  {% include archive-single.html %}
{% endfor %}
