---
title: A Field Experiment on Music Preference during Learning
summary: This study aims to a) profile the music preference of learners in view of potential individual differences, and b) investigate the association between music characteristics and listeners’ learning experience.
tags:
- Music
- Learning
- Learning experience
- Flow
- Engagement
- MIR system
- User study
- Naturalistic settings
- Master thesis
date: "2019-12-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Conceptual framework
  focal_point: Smart

links:
# - icon: twitter
#  icon_pack: fab
- name: Thesis
  url: media/master_thesis/thesis.pdf
- name: Moody
  url: media/master_thesis/cheatsheet.pdf
- name: N-Back Test Demo
  url: https://youtu.be/4Cn03gJ0nNA
- name: Multitasking Test Demo
  url: https://youtu.be/PQu51J9s4ss
- name: Multitasking Test @ Github
  url: https://github.com/Fanjie-Li/Multitasking-Test
- name: External Link
  url: http://ccmir.cite.hku.hk/index.php/leverage-the-power-of-music-for-learning/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

gallery_item:
- album: gallery
  image: moody_search.png
  caption: Music Filtering
- album: gallery
  image: moody_playlist.png
  caption: Favourite Music
- album: gallery
  image: tag_cloud.png
  caption: Genre Cloud
- album: gallery
  image: mosaic_plots.png
  caption: Mosaic Plot
---

{{% callout note %}}
Feb. 2019 - Dec. 2019 (Supervisor: Dr. Xiao Hu)
{{% /callout %}}

This study aims to a) profile the music preference of learners in view of potential individual differences, and b) investigate the association between music characteristics and listeners’ learning experience in view of the potential moderating effect of learners’ traits and task load.

A one-week field experiment was conducted in participants’ own study places. During the experiment, participants were asked to conduct learning sessions with music in the background and collect the tracks they deemed suitable for learning using a novel mobile music app (i.e., Moody App). A set of participant-related, context-related, and music-related data were collected via the pre-experiment questionnaire, surveys popped up during the learning session, and the logging system of the music app.


**Highlights:**
- Designed and developed the Moody music app (iOS client with a Flask-based backend and the MySQL database) to facilitate longitudinal data collection in naturalistic settings;
- Performed acoustic analysis on the 10k music pool and estimated music emotion in the arousal-valence space via Support Vector Machines (SVM);
- Collected users’ motion data (e.g., sedentary state), heart rate, etc. using the Fitbit Versa smartwatch.
- Implemented the Multitasking test using PsychoPy based on specifications in literature, and refined an existing Python-based N-Back Test for assessing participants’ working memory capacity.
- Conceived the conceptual framework. Performed data cleansing and analysis using Python and R.

**In Progress / Working Papers:**
- Optimizing Background Music for Learning: The Role of Music Characteristics, Task Load, and Learners’ Cognitive Capacity
- Profiling the Music Preference of Learners: A Field Study.

**Gallery:**

{{< gallery album="gallery" >}}



<div style="height: 20px;"></div>
