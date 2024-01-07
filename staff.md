---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff
Your friendly CS175 Teaching Staff is here to make sure you have a great experience!
## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

{% assign tutor = site.staffers | where: 'role', 'Course Tutor' %}
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
## Course Tutors
{% for staffer in tutor %}
{{ staffer }}
{% endfor %}
{% endif %}
## Domain Specialists / Collaborators
{% for staffer in domain_specialists %}
{{ staffer }}
{% endfor %}
{% endif %}
