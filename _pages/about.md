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

I am a Ph.D. candidate at Nanjing University of Science and Technology, under the supervision of <a href='https://teacher.njust.edu.cn/jsj/wy_14140/list.htm' target='_blank'>Prof. Ye Wu</a>.<br>
I focus on applications of artificial intelligence in healthcare, with in-depth research on disease onset prediction based on EEG signals.

My research interests include artificial intelligence and brain–computer interfaces. I have published some papers at the top international journal with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (<a href='https://scholar.google.com/citations?hl=zh-CN&user=rnYpjWYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

<!-- 
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📝 Publications 
<!-- 第二篇论文 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JBHI 2026</div><img src='images/JBHI1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Epileptic Seizure Prediction Using Multi-Strategy Data Augmentation and Hierarchical Contrastive Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11152518)

***IEEE Journal of Biomedical and Health Informatics (JBHI)*, 2026.**

**Longfei Qi**, Feng Li, Junliang Shang, Daohui Ge, Shihan Wang, Shasha Yuan*

[**GitHub**](https://github.com/BobbyQi/SeizurePrediction-MultiAug_HierContrast) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Propose EEG-specific data augmentation strategies, design a hierarchical contrastive loss function, and construct a lightweight SE-EEGNet framework for seizure prediction, achieving high-performance prediction with limited labeled data. 
</div>
</div>

<!-- 第一篇论文 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJNS 2025</div><img src='images/IJNS1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Contrastive Learning-Enhanced Residual Network for PredictingEpileptic Seizures Using EEG Signals](https://www.worldscientific.com/doi/epdf/10.1142/S0129065725500509)

***International journal of neural systems (IJNS)*, 2025.**

**Longfei Qi**, Shasha Yuan*, Feng Li, Junliang Shang, Juan Wang, Shihan Wang

[**GitHub**](https://github.com/BobbyQi/CLResNet) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Self-supervised contrastive learning was systematically introduced into seizure prediction for the first time, with the CLResNet framework proposed to address the scarcity of labeled data. 
</div>
</div>

- [Epileptic Seizure Detection Using ECA-EEGNet with Earth Mover's Distance-Based Metric Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11356229), Shihan Wang, Longfei Qi, Shasha Yuan*, et al. ***IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*, 2025**

- [Epileptic Seizure Detection Using Deep Adversarial Metric Learning](https://link.springer.com/chapter/10.1007/978-981-96-9955-1_14), Shihan Wang, Longfei Qi, Shasha Yuan*, et al. ***International Conference on Intelligent Computing (ICIC)*, 2025**

# 🎖 Honors and Awards
- *2026.01* Shandong Provincial Graduate Innovation Achievement Award, Shandong Provincial Department of Education
- *2025.12* China National Scholarship for Master Students, Ministry of Education of the People’s Republic of China

# 📖 Educations
<!-- - *2026.09 - 2030.06*, Nanjing University of Science and Technology, Ph.D. in Computer Science and Technology-->
- *2023.09 - 2026.06*, Qufu Normal University, M.S. in Computer Science and Technology, (Advisor: Assoc. Prof. Shasha Yuan)
- *2018.09 - 2022.06*, Shandong Jianzhu University, B.S. in Software Engineering, (Advisor: Prof. Ling Song)

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->