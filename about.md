---
layout: page
title: Syllabus
description: >-
    Course policies and information.
nav_order: 2
---

# Syllabus 📖
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## About and Student Learning Outcomes
Welcome to CS 175: Project in Artificial Intelligence!

This course aims to enable students to construct a working artificial intelligence system and evaluate its capabilities, including the impact of knowledge representation on a real-world problem. 

In this course offering, a collaborating domain specialist from the open source community will present the class with a use case that can benefit from the application of machine learning in its understanding of a particular phenomenon. Facilitated by the instructional staff, small student teams will assess the needs and requirements of the problem while developing project proposals. Using best practices from software engineering, students will develop project repositories that demonstrate good modular design with respect to different components of their machine learning pipeline. Documentation, testing, version control, and continuous integration practices ensure that the system is reproducible. Students will present in the Final Showcase to collaborating subject matter experts and the broader community. 

Prerequisites: COMPSCI 171 and COMPSCI 178

### Acknowledgements
This course is adapted from UC Berkeley's CS194-080 Full Stack Deep Learning, created by Sergey Karayev, Josh Tobin, and Pieter Abbeel with recent contributions from Charles Frye. The course research workflow is inspired by the Heliophysics Inovation in Technology and Science Solar Dynamics Observatory (HITS-SDO) program coordinated by Subhamoy Chatterjee and Andres Jaramillo-Munoz of Southwest Research Institute with contributions from Anirudh Koul co-author of [Practical Deep Learning for Coud, Mobile, and Edge](https://learning.oreilly.com/library/view/practical-deep-learning/9781492034858/). Finally, this unique opportunity would not be possible without the contributions of Lauren Sanders of Blue Marble Space Institute of Science and NASA GeneLab.

### Lecture
The lecture meets at [Social Science Lab (SSL) 140](https://goo.gl/maps/XBz5QSv8Xs59oKRm7) from:
- MWF 12-12:50PM

Lecture time will introduce main concepts and techniques of machine learning, facilitation of a research design sprint, as well as cover domain knowledge necessary to get started. Consistent attendance is strongly recommended as you will get the opportunity to ask questions, interact with our scientific collaborator, and participate in group discussions. 

Slides will be available online after each lecture with some latency to encourage attendance.

### Discussion
There are two discussion sections held in [Social Ecology II 1306](https://goo.gl/maps/oNNhFoVeFi6GwMKy8)
- F 9-9:50AM
- F 10-10:50AM
  
Discussion sessions are focused on implementation and practice with tooling via assignments and troubleshooting specifics with respect to your project implementation.

### Office Hours
See the [Calendar](../calendar) tab of the course website for the most up to date schedule and instructions.

Office hours are a great opportunity to get your questions answered with respect to assignments, your project results, and the tooling. When meeting with course staff remember to keep your questions detailed, descriptive, and specific. We understand that it can be difficult to troubleshoot models, but we hope you can assist us in assisting you by being clear on your proposed intent and model architecture. Results in the form of output logs and plots can be helpful in diagnosing issues as well.

## Course Tools

Course content will be linked from this website but there are additional platforms that you'll need to access:

- **[Discord](https://discord.gg/8faDygwq):** We will be using Discord as our course message and discussion board.

- **[Canvas](https://canvas.eee.uci.edu/):** We will use Canvas to disseminate up to date information with respect to your grades. 

- **[Gradescope](https://www.gradescope.com):** We will use Gradescope for assignment submission.

- **[Github Classroom](https://classroom.github.com):** The final project in this course will involve programming in Python and dexterity with deep learning frameworks like PyTorch and PyTorch Lightning. We will also be using github actions, a continuous integration tool.

- **[Miro](https://miro.com/app/board/uXjVMWu-Mho=/):** The whiteboard used in the project planning and design sprint phase.

{: .warning }
**Note that we will be using Canvas only as a gradebook this quarter. Please do not contact the staff through Canvas -- we will be focusing our attention on Discord**

In addition to the course tools, we will use several different tools to develop our machine learning models.

- We will use [PyTorch](https://pytorch.org/) and [PyTorch Lightning](https://www.pytorchlightning.ai/).
  
- We will use CNNs and Transformers for different tasks.
  
- We will manage and monitor our experiments using [Weights & Biases](https://docs.wandb.ai/)
  
- We will package and deploy our system
  
- We will set up a front-end using [Gradio](https://gradio.app/docs) or [Streamlit](https://streamlit.io/)
  

## Communication
This quarter we will be using Discord as our course message board. If you have a question about anything pertinent to the course, post it on the appropriate channel on Discord. We ask that you make your questions public to the class so that the other students may benefit from the interaction in addition to getting a chance to answer as well. Course staff will try to answer any questions you have regularly. 

Please use Discord **instead of email**, since this will help keep all course communication in one place. Please do not send course staff questions about course content over email or social media--Discord is where to go!

## Suggested Reading
Suggested reading will be linked with the corresponding lecture as we move through the course. To get the most out of it, we recommend reading it after lecture and before assignment submission.

## Assignments
Assignments will help you gain practice with tools and concepts from machine learning that will assist you in identifying models and techniques to solve different aspects of the research problem presented. 

### Project Proposal
The project proposal will be due early in the quarter following the close of the design sprint. It should represent the full end-to-end solution proposed and identify why it may be beneficial to the original research question it seeks to answer. It should include all team members involved along with a flowchart describing all system components, timeline, and proposed team schedule.

### Pull Request Friday
Code reviews for each team will take place every Friday in discussion section. The team must designate a rotating member to present the issue the pull request closed, explain the code, and screenshare with the teaching staff. Based on the feedback received by the staff, if the merge is made, the team will receive full credit or will have to refactor.

### Status Report
Present midterm milestones that have been reached as well as refinement of the ML system components. At this stage, baseline models should be identified and prototyped.

### The Final Project
For the final project, you can work in groups of 4 people maximum. In terms of time commitment, expect to take roughly **40 hours per person total**.

Your final project will be graded based on several factors.
  * Repository - The repository must have the appropriate structure and documentation for reproducibility of the study.
  * Technical Memorandum - Final project paper (template to be linked)
  * Poster - A companion poster presentation
  * Final Showcase Presentation - A short 5 min project presentation that will be recorded and open to the public June 14, 2023 from 4-6p PST.

### Deadlines and Grace Days
Life happens, we get it. Each student is allowed up to **3 "grace days"** to use towards their individual assignement and each team is allowed **4 "grace days"** to use towards their project deadlines. How you choose to distribute them is up to you but once you run out, and you still haven't submitted the assignment you will receive a zero for the assignment. Due to the time sensitivity of the task, design sprint exercises are not eligible for "grace day" usage. If you submit team project proposal, status report, or final project items late you and all team members will have to use grace days.

## Grades

| **Component** | **Weight** | **Notes** |
| ------------- | ---------- |
| Participation | 10% | Attendance & Engagement |
| Assignments | 20% | |
| Proposal | 10% | |
| Pull Requests | 30% |5% each x 6|
| Status Report | 5% | |
| Final Repository with Documentation | 10% | |
| Poster | 5% | |
| Presentation | 5% | |
| Tech Memo | 5% | |


### Regrade Requests
If you'd like to request a regrade on any assignment, you must do so within one
week of the assignment being graded. If you think there is a problem with how your written question was graded, submit a regrade request through Gradescope.

### Letter Grades and Incompletes
We will use a standard scale for assigning letter grades:

| **Letter Grade** | A | A- | B+ | B | B- | C+ | C | C- | D | F |
| **Percentage** | 93+ | 90+ | 87+ | 83+ | 80+ | 77+ | 73+ | 70+ | 60+ | below 60 |


## Academic Dishonesty

Academic Dishonesty will not be tolerated. If the staff determines that academic dishonesty has occurred, we will enforce the [UCI Academic Integrity and Student Conduct Procedures](https://aisc.uci.edu/students/academic-integrity/procedures.php). Campus-wide sanctions are determined by the Associate Dean of your department. Please note that instances of academic dishonesty will be reflected in the final grade because dishonesty devalues the learning experience for the whole class.

## Students Requiring Accommodations

Any student who feels he or she may need an accommodation based on the impact of a disability should contact me privately to discuss his or her specific needs.  Also contact the Disability Services Center at (949) 824-7494 as soon as possible to better ensure that such accommodations are implemented in a timely fashion.

## Syllabus Changes
The staff reserve the right to change this syllabus without limitation and without prior notice. If any item or policy is modified, the teaching staff will notify students directly.