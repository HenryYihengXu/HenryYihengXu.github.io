---
title:  "Research"
layout: single
permalink: /research
author_profile: true
comments: true
---

{% for research in site.research %}
## {{ research.title }}
{{ research.content }}
{% include archive-single.html %}
{% endfor %}
