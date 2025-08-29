---
layout: page
title: Instructor contact and appointment info
description: Where and when to find me
nav_order: 6
---


## Course Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Office Location
Renaissance Park office building, room 432
Renaissance Park office building is NOT Renaissance Park garage!


## [Make an appointment!](https://calendly.com/v-ricks/ricks-fall-2025-student-appointment-hours)


