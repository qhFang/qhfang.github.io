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

<p>
  I am a master student at the <a 
            href="http://irc.cs.sdu.edu.cn/">Interdisciplinary Research Center (IRC)</a>, <a 
            href="https://www.sdu.edu.cn/">Shandong University</a>, where I am honored to be advised by <a 
            href="https://cfcs.pku.edu.cn/baoquan/">Prof. Baoquan Chen</a>. I am also an intern at <a 
            href="https://ai.tencent.com/">Tencent AI Lab</a> where I am advised by <a 
            href="https://fqnchina.github.io/">Dr. Qingnan Fan</a>
</p>

My research focus lies in computer graphics, 3D vision, especially human motion animation and camera localization.


# 🔥 News
- *2022.07*: Our paper [Towards Accurate Active Camera Localization](https://arxiv.org/abs/2012.04263) was accepted by ECCV 2022.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='../QihangFang_files/eccv_2022_localization.gif' alt="ActiveLocalization" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Towards Accurate Active Camera Localization

*Qihang Fang, *[Yingda Yin](https://yd-yin.github.io/), †[Qingnan Fan](https://fqnchina.github.io/), [Fei Xia](https://fxia22.github.io/), [Siyan Dong](https://scholar.google.com/citations?user=vtZMhssAAAAJ&hl=en/), Sheng Wang, [Jue Wang](https://juewang725.github.io/), [Leonidas Guibas](http://geometry.stanford.edu/member/guibas/index.html), †[Baoquan Chen](http://cfcs.pku.edu.cn/baoquan/)

[arXiv](https://arxiv.org/abs/2012.04263) [bibtex](../QihangFang_files/eccv_2022_localization.bib) [code](https://github.com/qhFang/AccurateACL) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this work, we explicitly model the camera and scene uncertainty components to solve the problem of active camera localization by reinforcement learning. Our algorithm improves over the state-of-the-art Markov Localization based approaches by a large margin on the fine-scale camera pose accuracy.
</div>
</div>



# 📖 Educations
- 2020.09 - Present, Master student, Interdisciplinary Research Center (IRC), Shandong University. 
  - Advisor:  [Prof. Baoquan Chen](https://cfcs.pku.edu.cn/baoquan/)
- 2016.09 - 2020.06, B.E., Computer science and technology, Shandong University. 

# 💻 Internships
- 2021.07 - Present, Research intern in Tencent AI Lab.
  - Collaborator:  [Qingnan Fan](https://fqnchina.github.io/),  [Jue Wang](https://juewang725.github.io/)
