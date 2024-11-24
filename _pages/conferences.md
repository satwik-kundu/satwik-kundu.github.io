---
layout: page
permalink: /conf/
title: Conferences
show_title: false
description: #Materials for courses you taught. Replace this text with your description.
nav: false
nav_order: 5

---

# Upcoming Conferences

<br>

{% assign current_date = 'now' | date: '%Y-%m-%d' %}
{% assign upcoming_conferences = site.data.conferences | sort: "deadline" %}

{% for conference in upcoming_conferences %}
  {% if conference.deadline > current_date %}
#### [{{ conference.name }}]({{ conference.link }}) ({{ conference.deadline | date: "%b %d, %Y" }})
---
  {% endif %}
{% endfor %}
