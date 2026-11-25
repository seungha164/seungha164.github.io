---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Electrical Engineering** (major: Computer Engineering), Korea University, Seoul, Korea
  * Mar. 2026 – Present
  * Advisor: Prof. Jin Tae Kwak
* **M.S. in Computer Science**, Kyonggi University, Suwon, Korea
  * Mar. 2024 – Feb. 2026
  * Advisor: Prof. Byoung-Dai Lee
  * GPA: 4.33 / 4.5
* **B.S. in Computer Engineering**, Kyonggi University, Suwon, Korea
  * Mar. 2020 – Feb. 2024
  * GPA: 4.1 / 4.5

Research Interests
======
* Computer Vision
* Medical Deep Learning
* Multi-modality (Text–Image)
* Vision Foundation Models
* Image Segmentation / Object Detection

Experience
======
* **Quantitative Imaging & Informatics (QuIIL) Lab**, Korea University, Seoul, Korea
  * Feb. 2026 – Present
* **Medical Deep Learning Lab (ACS)**, Kyonggi University, Suwon, Korea
  * Jun. 2022 – Jan. 2026
* **ML/DL Research Intern**, VisualSyn, Seoul, Korea
  * Oct. 2023 – Sep. 2024
  * Deployed and optimized deep learning models on the web using ONNX and WebGPU
* **Research Trainee**, Electronics and Telecommunications Research Institute (ETRI), Daejeon, Korea
  * Jul. 2023 – Aug. 2023
  * Developed models for fall detection in CCTV video

Publications
======
{% for category in site.publication_category %}
**{{ category[1].title }}**
  <ul>{% for post in site.publications reversed %}{% if post.category == category[0] %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>
{% endfor %}

Awards
======
* **2nd Place**, AIMS-TBI 2026 Challenge, MICCAI 2026 (Oct. 2026)
* **Outstanding Paper Award**, APIC-IST 2025 (2025)
* **Bronze Prize**, Open-Source SW Developer Contest, Ministry of Science and ICT (Dec. 2023)
* **2nd Place**, Kyonggi University Software-Industry Collaboration Competition (Nov. 2023)
* **1st Place**, Kyonggi University Capstone Design Competition (Jun. 2023)

Scholarships
======
* **KGU Scholarship (Type A)**, recommended by Kyonggi University (Fall 2023)
* **KGU Scholarship (Type B)**, recommended by Kyonggi University (Spring 2023)
* **Academic Excellence Scholarship**, Kyonggi University (Fall 2022): 1st place in academic performance
* **Academic Excellence Scholarship**, Kyonggi University (Spring 2022): top 15% of students

Technical Skills
======
* **Programming languages**: Python, Java, C
* **Deep learning frameworks**: PyTorch, TensorFlow, Keras
