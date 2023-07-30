---
layout: archive
title: "Teaching and Syllabi"
permalink: /teaching/
author_profile: true
---

At the University of Washington, I teach courses on Taiwan Studies every year, as well as East Asia and global thematic courses on development, capitalism, environment, science and technology studies, political economy, and foreign relations.

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
