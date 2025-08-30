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

## Click [to make an appointment!](https://calendly.com/v-ricks/ricks-fall-2025-student-appointment-hours)

## Office Location - Renaissance Park office building, room 432
![Renaissance Park office building](/assets/images/RPbldg.jpg)
This is the office building
#
![Renaissance Park office building](/assets/images/RPgarage.jpg)
This is NOT the office building




