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
## <b style='color: green'> 👋 Welcome!</b> 
Please start by reviewing the [syllabus](https://uc-irvine-cs175.github.io/uci-cs175/syllabus/).

**👩‍🏫 Instructor:** Nadia Ahmed

**🕞 Time and Location:** There are two sections for the course:
- Lecture A: MW 3:30-4:50p [ALP 1600](https://classrooms.uci.edu/classroomtechnology/classrooms/alp/alp-1600)
- Lecture B: W 5:30 - 8:20p [SH 174](https://classrooms.uci.edu/classroomtechnology/classrooms/sh/sh-174)
  
**📲 Staff Contact:** The best way to reach the staff is by making posts on the [CS175 Discord Server](https://discord.gg/cjFSr3ejqW).


This course aims to enable students to construct a working artificial intelligence system and evaluate its capabilities, including the impact of knowledge representation on a real-world problem.

In this course offering, collaborating domain specialists from the open source community will highlight use cases that can benefit from the application of machine learning in its understanding of a particular phenomenon. Facilitated by the instructional staff, small student teams will assess the needs and requirements of the problem while developing project proposals. Using best practices from software engineering, students will develop project repositories that demonstrate good modular design with respect to different components of their machine learning pipeline. Documentation, testing, version control, and continuous integration practices ensure that the system is reproducible. Students will present in their results in a Final Showcase to collaborating subject matter experts and the broader community. 

<b style='color: green'> 🛑 Prerequisites:</b> COMPSCI 171 and COMPSCI 178

## **🖍️ Miro Boards:**
  - **[Section A: MW 3:30-4:50p](https://miro.com/app/board/uXjVN8kFK4I=/?share_link_id=120736279658)**
  - **[Section B: W 5:30-8:20p](https://miro.com/app/board/uXjVN8kFKMc=/?share_link_id=828552320449)**

## 📆 Course Calendar
{% for module in site.modules %}
{{ module }}
{% endfor %}
