---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[Download my CV (PDF)]({{ base_path }}/assets/Christian_Lourido_CV.pdf)

Work Experience
======
<ul>{% for post in site.teaching reversed %}
  <li><b>{{ post.type }}</b>, {{ post.title }} – {{ post.location }} ({{ post.period }}){{ post.content }}</li>
{% endfor %}</ul>

Education
======
* Ph.D. in Mechanical Engineering, NYU Tandon School of Engineering (2020–2026)
  * Dissertation: *Exploring Extended Reality Technologies for Human-Centered Interaction: From Rehabilitation to Human-Robot Collaboration*
  * Advisor: Prof. Vikram Kapila
* M.S. in Mechatronics and Robotics, NYU Tandon School of Engineering (2018–2020)
* B.S. in Mechatronics Engineering, Tecnológico de Monterrey (ITESM-CEM), Mexico (2007–2011)

Awards and Honors
======
* GEM Fellowship – Employer Fellow, Apple Inc. (2022)
* High-Performance Academic Scholarship, Tecnológico de Monterrey (2007–2011)

Skills
======
* **Programming:** C/C++, Python, Swift, C#, LaTeX
* **Version control:** Git, GitHub
* **Robotics middleware:** ROS, ROS 2, rosbridge, rosbag, MATLAB Robotics Toolbox
* **Motion planning:** MoveIt 2, OMPL, Pilz, NVIDIA cuRobo, OctoMap, nvblox
* **Robotic arms:** Universal Robots, FANUC CRX
* **AI / ML:** PyTorch, TensorFlow, Ultralytics YOLO11 (detection and instance segmentation), synthetic data generation (Unity Perception), Core ML on-device deployment, dataset curation and annotation
* **Perception & vision:** OpenCV, Open3D, point-cloud processing (PCA, ICP), pose estimation
* **Simulation:** RViz, Gazebo
* **Software / OS:** MATLAB-Simulink, Linux, macOS, Windows
* **CAD:** Autodesk Fusion, SolidWorks
* **App development:** Unity, Xcode (iOS, ARKit)
* **PLC / HMI:** Studio 5000 Logix Designer, FactoryTalk, Ignition
* **Languages:** English (fluent), Spanish (native)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Mentorship
======
* [Kishan Reddy Raghunath](https://www.linkedin.com/in/kishanreddy6/) – M.S. student in Mechatronics and Robotics (2021–2023)
* [Pavan Cherukuri](https://www.linkedin.com/in/pc3088/) – M.S. student in Mechatronics and Robotics (2021–2023)
