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

Hi, My name is Haobin Li. I'm a Ph.D. student from College of Computer Science, Sichuan Univerisity, fortunately advised by Prof. [Xi Peng](https://xlearning-lab.com/).

My research interests mainly focus on Robust Multi-modal Learning and MLLM Reasoning, especially the challenges encountered in open scenarios, such as missing modalities, noisy correspondence, distribution shift.


# 🔥 News
- *2026.01*: One papers was accepted by International Conference on Learning Representations (ICLR 2026).

# 📝 Publications 

<sup>*</sup> Equal contribution <sup>†</sup> Corresponding author


<div class='paper-box'>
<div class='paper-box-image'><div>
<div class="badge">arxiv 2025</div>
<img src='images/rest.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**arxiv'25**</em>] [Toward Robust and Harmonious Adaptation for Cross-modal Retrieval](https://arxiv.org/pdf/2511.14416) \\
**Haobin Li**, Mouxing Yang, Xi Peng

\|


- Extend query shift and tackle more challenging diverse shift scenarios.
- Establish more benchmarks across image-text, video–audio and composed image retrieval.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div>
<div class="badge">ICLR 2026</div>
<img src='images/rule.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**ICLR’26**</em>] [Learning with Dual-level Noisy Correspondence for Multi-modal Entity Alignment](https://openreview.net/pdf?id=mytIKuRsSE) \\
**Haobin Li**, Yijie Lin, Peng Hu, Mouxing Yang, Xi Peng

<a href="https://github.com/XLearning-SCU/RULE"><strong>Code</strong></a >
\|


- First reveal and study noisy and underlying correspondence in multi-modal knowledge graph.
- Pioneering exploration of test-time robustness.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div>
<div class="badge">TPAMI 2026</div>
<img src='images/camera.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**TPAMI'26**</em>] [Community-aware Multi-view Representation Learning with Incomplete Information](https://pengxi.me/wp-content/uploads/2025/11/Community-aware-Multi-view-Representation-Learning-with-Incomplete-Information.pdf) \\
**Haobin Li**, Yijie Lin, Peng Hu, Mouxing Yang, Xi Peng

<a href="https://github.com/XLearning-SCU/2025-TPAMI-CAMERA"><strong>Code</strong></a >
\|


- Leveraging sociological concepts to address missing modalities and correspondences.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div>
<div class="badge">ICLR 2025</div>
<img src='images/tcr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**ICLR’25 Spotlight**</em>] [Test-time Adaptation for Cross-modal Retrieval with Query Shift](https://pengxi.me/wp-content/uploads/2025/11/Community-aware-Multi-view-Representation-Learning-with-Incomplete-Information.pdf) \\
**Haobin Li**, Peng Hu, Qianjun Zhang, Xi Peng, Xiting Liu, Mouxing Yang

<a href="https://github.com/XLearning-SCU/2025-ICLR-TCR"><strong>Code</strong></a >
<a href="https://mp.weixin.qq.com/s/w3mp7j6_7ZIfcmNFAUJDRA"><strong>中文简介</strong></a >
\|


- First study the query shift problem in cross-modal retrieval.
- Reveal the underlying impacts of query shift on cross-modal retrieval

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div>
<div class="badge">IJCAI 2023</div>
<img src='images/proimp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**IJCAI'23**</em>] [Incomplete Multi-view Clustering via Prototype-based Imputation](https://www.ijcai.org/proceedings/2023/0435.pdf) \\
**Haobin Li**, Yunfan Li, Mouxing Yang, Peng Hu, Dezhong Peng, Xi Peng

<a href="https://github.com/XLearning-SCU/2023-IJCAI-ProImp"><strong>Code</strong></a >
\|


- Leveraging sample-prototype relationship to impute missing modality.

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
<div class="badge">Vicinage Earth 2024</div>
<img src='images/clustering.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**Vicinagearth'24**</em>] [A survey on deep clustering: from the prior perspective](https://link.springer.com/content/pdf/10.1007/s44336-024-00001-w.pdf) \\
Yiding Lu<sup>*</sup>, **Haobin Li**<sup>*</sup>, Yunfan Li, Yijie Lin, Xi Peng

<a href="https://zhuanlan.zhihu.com/p/12059278751"><strong>中文简介</strong></a >
\|


- A survey of deep clustering from a prior perspective.

</div>
</div>

# 📖 Service
- Journal Reviewer: IEEE TPAMI, IEEE TIP, and more.
- Conference Reviewer: ICLR, NeurIPS, ICML, CVPR, AAAI, and more.

<!-- <div class='paper-box'>
<div class='paper-box-image'><div> -->
<!-- <div class="badge">ICLR 2024</div> -->
<!-- < img src='assets/papers/llava-reid.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->


<!-- [<em>**ICML’25**</em>] [LLaVA-ReID: Selective Multi-image Questioner
for Interactive Person Re-Identification](https://arxiv.org/pdf/2504.10174) \\
Yiding Lu, Mouxing Yang, Dezhong Peng, Peng Hu, **Yijie Lin**<sup>†</sup>, Xi Peng<sup>†</sup> -->


<!-- <a href="https://mp.weixin.qq.com/s/j3VRGEH6nztfz-wpB8Z5tA?scene=1&click_id=35"><strong>中文简介</strong></a >
\|
<a href="https://github.com/XLearning-SCU/LLaVA-ReID"><strong>Code</strong></a > -->
<!-- \| -->
<!-- <a href="https://github.com/XLearning-SCU/2024-ICLR-Norton"><strong>Code</strong></a > -->
<!-- [![](https://img.shields.io/github/stars/XLearning-SCU/LLaVA-ReID?style=social&label=Stars)](https://github.com/XLearning-SCU/LLaVA-ReID)
\|
<a href="https://raw.githubusercontent.com/XLearning-SCU/LLaVA-ReID/main/img/poster-wo-wechat.png"><strong>Poster</strong></a > -->


<!-- <a href="https://mp.weixin.qq.com/s/yGieWt0s9jPPRX6sG03KDw"><strong>中文简介</strong></a > -->
<!-- \| -->
<!-- <a href="https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON"><strong>Code</strong></a > -->
<!-- [![](https://img.shields.io/github/stars/Lin-Yijie/Graph-Matching-Networks?style=social&label=Stars)](https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON) -->
<!-- <strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:Y0pCki6q_DkC'></span></strong> -->


<!-- - Introduce the first dialogue-based person re-identification task.

</div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
