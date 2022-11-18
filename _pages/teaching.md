---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

At the University of Washington, I teach courses on Taiwan Studies every year, as well as East Asia or global thematic courses on development, capitalism, political economy, and foreign relations.

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
