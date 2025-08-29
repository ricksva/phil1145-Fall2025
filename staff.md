---
layout: page
title: Instructor contact and appointment info
description: Where and when to find me
nav_order: 6
---


## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
