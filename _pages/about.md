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

I am a third-year graduate student in the Biomedical Engineering program at [Dalian University of Technology](https://www.dlut.edu.cn/)’s Faculty of Medicine. I’m working on medical imaging AI (computational pathology) under the supervision of [Associate Professor Hongming Xu](https://xhm1014.github.io/index.html). Before coming to Dalian University of Technology, I studied Electronic Information Engineering at the School of Information Science and Engineering, [Yanshan University](https://www.ysu.edu.cn/). Currently, I am focused on computational pathology and deep learning, particularly in multiple instance learning, generative adversarial networks, and multimodal fusion, to advance scientific discovery. 

My Chinese given name is 桐 (Tong), pronounced as 桐/tʊŋ/. My Chinese surname is 王 (Wang), pronounced as 王/wɑːŋ/. It’s also fine to call me Tong.

**<span style="color:red">I am seeking PhD positions for Fall 2025. If you know of any exciting opportunities, please feel free to contact me!</span>**


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News
- *2024.11*: Our paper on KG-based Retrieval-Augmented Generation is released on [arXiv](https://arxiv.org/pdf/2410.20724).
- *2024.09*: Our paper [GeSS](https://arxiv.org/abs/2310.08677) on benchmarking OOD performance in geometric deep learning is accepted to NeurIPS 2024 D&B Track.
- *2024.07*: Our paper on explainable geometric deep learning is released on [arXiv](https://arxiv.org/abs/2407.00849).
- *2024.06*: Our paper on graph state space model (GSSC) is released on [arXiv](https://arxiv.org/abs/2406.05815).
- *2024.05*: Our paper [HEPT](https://arxiv.org/abs/2402.12535) is accepted to ICML 2024 and selected for oral presentation! See you in Vienna!
- *2024.03*: Gave a talk at [A3D3](https://a3d3.ai/) institute HEP group on [HEPT](https://arxiv.org/abs/2402.12535).
- *2024.02*: Our paper on efficient point transformer (HEPT) is released on [arXiv](https://arxiv.org/abs/2402.12535).


# 📝 Publications


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/SubgraphRAG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Simple is Effective: The Roles of Graphs and LLMs in KG-Based Retrieval-Augmented Generation](https://arxiv.org/pdf/2410.20724) \\
Mufei Li\*, <u><strong>Siqi Miao*</strong></u>, Pan Li. **Preprint 2024**\\
(\*Equal contribution)\\
<a href="https://arxiv.org/pdf/2410.20724"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/SubgraphRAG"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/GSSC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[What Can We Learn from State Space Models for Machine Learning on Graphs?](https://arxiv.org/pdf/2406.05815) \\
Yinan Huang\*, <u><strong>Siqi Miao*</strong></u>, Pan Li. **Preprint 2024**\\
(\*Equal contribution, listed in alphabetical order)\\
<a href="https://arxiv.org/pdf/2406.05815"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/GSSC"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/HEPT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LSH-Based Efficient Point Transformer with Applications in High-Energy Physics](https://arxiv.org/abs/2402.12535) \\
<u><strong>Siqi Miao</strong></u>, Zhiyuan Lu, Mia Liu, Javier Duarte, Pan Li. **ICML 2024 <span style="color:red">(Oral, Top 1.5%)</span>**\\
<a href="https://arxiv.org/abs/2402.12535"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/HEPT"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<a href="https://arxiv.org/abs/2402.12535"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2724&color=blue"></a>

</div>
</div>








<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>
</div> -->



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2022</div><img src='images/GSAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interpretable and Generalizable Graph Learning via Stochastic Attention Mechanism](https://arxiv.org/abs/2201.12987) \\
**Siqi Miao**, Miaoyuan Liu, Pan Li, **ICML 2022**

<a href="https://github.com/Graph-COM/GSAT"><img src="https://img.shields.io/github/stars/Graph-COM/GSAT?style=social&label=Code+Stars" alt=""></a>
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/LRI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interpretable Geometric Deep Learning via Learnable Randomness Injection](https://openreview.net/forum?id=6u7mf9s2A9) \\
<u><strong>Siqi Miao</strong></u>, Yunan Luo, Mia Liu, Pan Li. **ICLR 2023 <span style="color:red">(Review Score 7, Top 7.1%)</span>**\\
<a href="https://arxiv.org/abs/2210.16966"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/LRI"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<a href="https://openreview.net/forum?id=6u7mf9s2A9"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICLR%2723&color=blue"> </a>
<!-- <a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> -->
<!-- <a href="https://proceedings.mlr.press/v162/miao22a.html"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2722&color=blue"> </a> -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2022</div><img src='images/GSAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interpretable and Generalizable Graph Learning via Stochastic Attention Mechanism](https://arxiv.org/abs/2201.12987) \\
<u><strong>Siqi Miao</strong></u>, Mia Liu, Pan Li. **ICML 2022 <span style="color:red">(Spotlight)</span>**\\
<!-- <a href="https://arxiv.org/abs/2201.12987"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/GSAT"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://img.shields.io/badge/-Colab-grey?logo=googlecolab&logoColor=white" alt="Colab"></a>
<a> <img src="https://img.shields.io/badge/Video-grey?logo=airplayvideo&logoColor=white" alt="Video"></a>
<a> <img src="https://img.shields.io/badge/Slides-grey?&logo=MicrosoftPowerPoint&logoColor=white" alt="Slides"></a> -->
<a href="https://arxiv.org/abs/2201.12987"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/GSAT"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<a href="https://proceedings.mlr.press/v162/miao22a.html"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2722&color=blue"></a>
<a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a>
<a href="https://github.com/Graph-COM/GSAT"><img src="https://img.shields.io/github/stars/Graph-COM/GSAT?style=social" alt="Github"></a>


**Blogs ([English](https://towardsdatascience.com/graph-machine-learning-icml-2022-252f39865c70#be75:~:text=and%20inductive%20settings.-,%E2%9E%A1%EF%B8%8F%20Miao%20et%20al,-take%20another%20perspective) - [中文](https://mp.weixin.qq.com/s/aP-XBqFLV0x8h9rtOKU_yg))** |
**[Slides](https://icml.cc/media/icml-2022/Slides/17430.pdf)** |
**[Poster](https://icml.cc/media/PosterPDFs/ICML%202022/a8acc28734d4fe90ea24353d901ae678.png)**

</div>
</div>





- <a href="https://arxiv.org/abs/2407.00849"><img src="https://img.shields.io/badge/-Preprint 2024-grey?logo=&logoColor=white" alt="Paper"></a> [Towards Understanding Sensitive and Decisive Patterns in Explainable AI: A Case Study of Model Interpretation in Geometric Deep Learning](https://arxiv.org/abs/2407.00849), Jiajun Zhu, <u><strong>Siqi Miao</strong></u>, Rex Ying, Pan Li.



- <a href="https://arxiv.org/abs/2310.08677"><img src="https://img.shields.io/badge/-NeurIPS 2024-grey?logo=&logoColor=white" alt="Paper"></a> [GeSS: Benchmarking Geometric Deep Learning under Scientific Applications with Distribution Shifts](https://arxiv.org/abs/2310.08677), Deyu Zou\*, Shikun Liu\*, <u><strong>Siqi Miao</strong></u>, Victor Fung, Shiyu Chang, Pan Li.

- <a href="https://arxiv.org/abs/2312.03823"><img src="https://img.shields.io/badge/-CTD 2023-grey?logo=&logoColor=white" alt="Paper"></a> [High Pileup Particle Tracking with Object Condensation](https://arxiv.org/abs/2312.03823), Kilian Lieret, Gage DeZoort, Devdoot Chatterjee, Jian Park, <u><strong>Siqi Miao</strong></u>, Pan Li.

<!-- https://img.shields.io/badge/Video-grey?style=plastic&logo=airplayvideo&logoColor=white -->
<!-- https://img.shields.io/badge/Slides-grey?&logo=GoogleSheets&logoColor=white -->



<!-- - [Interpretable and Generalizable Graph Learning via Stochastic Attention Mechanism](https://arxiv.org/abs/2201.12987), **Siqi Miao**, Miaoyuan Liu, Pan Li, **ICML 2022** ([codes](https://github.com/Graph-COM/GSAT)) -->

# 🎖 Honors and Awards
- *2023.03* ICLR’23 Travel Award
- *2022.07* ICML’22 Travel Award
- *2022.07* Purdue Graduate Travel Grant
- *2020.03* Tencent Innovation Award
- *2020.01* Tencent Outstanding Employee (Top 10%)

# 💬 Invited Talks
- *2024.03*, A3D3 Institute HEP Group
- *2022.11*, Inter-Experimental LHC Machine Learning Working Group, CERN
- *2022.10*, Department of Physics, Purdue University
- *2022.08*, AI Time
- *2022.07*, Fast Machine Learning Lab


<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experience
- *2023.01 - Present*, Georgia Tech, Research Assistant, Atlanta, USA
- *2021.08 - 2022.12*, Purdue University, Research Assistant, West Lafayette, USA
- *2019.07 - 2020.05*, Tencent, Machine Learning Engineer, Guangzhou, China
- *2018.05 - 2018.08*, Tencent, Machine Learning Intern, Guangzhou, China

<script type="text/javascript" src="assets/js/LastUpdateDate.js"></script>
<a href='https://clustrmaps.com/site/1bgz9'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=70&t=n&d=a6iAb7ez3Wz6FmyA2Dk7WnttgXxsBmp_weXKt76zhWU&co=2d78ad&ct=ffffff' style="display: none;"/></a>

# 📖 Academic Services
- Conference Reviewer: ICML, ICLR, NeurIPS, AAAI, AISTATS, LOG, WWW
- Journal Reviewer: TMLR, IEEE Transactions on Signal Processing

# 🎮 Misc
- *The Legend of Zelda: Breath of the Wild* and *The Witcher 3: Wild Hunt* are the best games ever. *Genshin Impact* is also awesome!
- I'm a big fan of *Lego Technic*. I once combined them with RC cars to build a few cool Lego cars that could drift and climb!
- I have 4.5k+ followers on [Zhihu](https://www.zhihu.com/people/miao-si-qi), a Quora-like platform in China.
- I built my own PC and home automation system. I also liked to play with Jetson TX2 and Raspberry Pi.
