---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. candidate at the School of Computer Science, the University of Auckland. My supervisors are [Dr. Meng-Fen Chiang](https://ankechiang.github.io/), [Dr. Kaiqi Zhao](https://kaiqi.blogs.auckland.ac.nz/) and [Prof. Sebastian Link](https://profiles.auckland.ac.nz/s-link).

I received the Master of Science degree in computer science (First Class) from the University of Auckland in 2022. During my Master's study, I researched multi-hop logical query reasoning over hierarchical knowledge graphs supervised by Dr. Meng-Fen Chiang and [Assoc.Prof. Wang-Chien Lee](https://sites.psu.edu/wlee/) (Penn State University). 

My research interests include:
* Knowledge Graph Representation Learning
* Knowledge Graph Query Answering
* Retrieval-augmented generation
* Natural Language Processing

<!--
<a href='https://scholar.google.com/citations?user=CG6rNcwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
-->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2022</div><img src='images/line.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LinE: Logical Query Reasoning over Hierarchical Knowledge Graph](https://www.researchgate.net/publication/362279679_LinE_Logical_Query_Reasoning_over_Hierarchical_Knowledge_Graph
)

**Zijian Huang**, Meng-Fen Chiang, Wang-Chien Lee.

The 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining

[**Project**](https://github.com/nelsonhuangzijian/LinE) <strong><span class='show_paper_citations' data='CG6rNcwAAAAJ:IjCSPb-OGe4C'></span></strong>
- [WN18RR Hierarchical KG benchmark](https://github.com/nelsonhuangzijian/WN18RR-QA)
</div>
</div>

- `ACL Findings 2024` [SKGSum: Structured Knowledge-Guiding Document Summarization](https://aclanthology.org/2024.findings-acl.110.pdf) <br>
Qiqi Wang, Ruofan Wang, Kaiqi Zhao, Robert Amor, Benjamin Liu, Jiamou Liu, Xianda Zheng, **Zijian Huang**.<br>
Findings of The 62nd Annual Meeting of the Association for Computational Linguistics
- `ECAI 2023` [Towards Legal Judgment Summarization: A Structure-Enhanced Approach](https://www.researchgate.net/publication/374305915_Towards_Legal_Judgment_Summarization_A_Structure-Enhanced_Approach) <br>
Qiqi Wang, Ruofan Wang, Kaiqi Zhao, Robert Amor, Benjamin Liu, Xianda Zheng, Zeyu Zhang, **Zijian Huang**.<br>
The 26th European Conference on Artificial Intelligence


# 🎓 Educations
- Ph.D. candidate in Computer Science, The University of Auckland, New Zealand, *2023 - Now* <br>
  (Supervised by Meng-Fen Chiang, Kaiqi Zhao and Sebastian Link)
- M.Sc. (First Class Honours) in Computer Science, The University of Auckland, New Zealand, *2021 - 2022* <br>
  (Supervised by Meng-Fen Chiang)
- B.Sc. in Computer Science, The University of Auckland, New Zealand, *2016 - 2019*

# 💼 Work Experience
- Intern, Guangzhou Urban Planning & Design Survey Research Institute, China, *2022.03 - 2022.08*

# 📖 Teaching
- Algorithms for Massive Data (COMPSCI 753), Teaching Assistant, S2 2024, The University of Auckland

# 🎖 Honors and Awards
- University of Auckland Doctoral Scholarships, *2023*

# 💻 Professional Services
- Program Committee Member: ECAI 2023, EMNLP 2023
- Journal Reviewer: TOIS
- External Reviewer: PAKDD 2022, WWW 2025
