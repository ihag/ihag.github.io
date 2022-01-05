---
layout: main
title: 웹
main: true
---

<div class="loading-animation">

<!--{% include hashtag.html %}-->

<ul class="catalogue">
{% assign sorted = site.pages | sort: 'date' | reverse | where: 'type', 'web' %}
{% for page in sorted %}
{% include post-list.html %}
{% endfor %}
</ul>
</div>