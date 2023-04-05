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
Please start by reading this website, especially the [syllabus](../about) and the schedule below. 

![uci_brain](/assets/images/valentin_brain_logo.png)

[Zoom Link for Remote Office Hours](https://uci.zoom.us/my/drbuci){: .btn .btn-blue }

{% for module in site.modules %}
{{ module }}
{% endfor %}
