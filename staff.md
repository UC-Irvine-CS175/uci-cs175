---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`.

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

{% assign domain_specialists = site.staffers | where: 'role', 'Domain Specialist' %}
{% assign num_domain_specialists = domain_specialists | size %}
{% if num_domain_specialists != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Domain Specialists / Collaborators
{% for staffer in domain_specialists %}
{{ staffer }}
{% endfor %}
{% endif %}
