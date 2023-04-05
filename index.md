---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }} 📊
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<b style='color: green'> 👋 Welcome!</b>
Please start by reading this website, especially the [syllabus](../syllabus) and the schedule below. 

{{ site.staffersnobio }}

[Zoom Link for Remote Office Hours](https://ucsd.zoom.us/j/93291940198?pwd=aWJvWmNwRFJpalF1dXh0dTBDSUo5UT09){: .btn .btn-blue } [Podcast Recordings](https://podcast.ucsd.edu/default.aspx){: .btn .btn-green }

{% for module in site.modules %}
{{ module }}
{% endfor %}
