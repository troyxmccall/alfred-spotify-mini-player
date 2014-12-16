---
layout: archive
permalink: /
title: "Welcome to Spotify Mini Player !"
image:
  feature: test.png
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->