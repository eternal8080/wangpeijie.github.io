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
# 👋 About Me
I am currently a third-year Ph.D. student at [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/), supervised by Prof. [Cheng-Lin Liu](https://scholar.google.com/citations?hl=en&user=8r3y8IMAAAAJ). 

Before that, I obtained my B.Eng. degree from School of Artificial Intelligence and Automation [(AIA)](http://aia.hust.edu.cn/), Huazhong University of Science and Technology [(HUST)](https://english.hust.edu.cn/) in 2023, where I was supervised by Prof. [Dongrui Wu](https://scholar.google.com/citations?user=UYGzCPEAAAAJ).



I currently focus on the evaluation, reasoning, and formal mathematical reasoning of multimodal large language models.


# 📖 Educations
- **Ph.D.** @ [MAIS, Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/), 2025.02 - 2028.06 (expected)  
  Advisor: Prof. [Fei Yin](https://scholar.google.com/citations?user=CeWCYJYAAAAJ&hl) and Prof. [Cheng-Lin Liu](https://scholar.google.com/citations?hl=en&user=8r3y8IMAAAAJ)

- **M.S.** @ [MAIS, Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/), 2023.09 - 2025.02  
  Advisor: Prof. [Fei Yin](https://scholar.google.com/citations?user=CeWCYJYAAAAJ&hl) and Prof. [Cheng-Lin Liu](https://scholar.google.com/citations?hl=en&user=8r3y8IMAAAAJ)

- **B.E.** @ [AIA, Huazhong University of Science and Technology](http://aia.hust.edu.cn/), 2019-2023  
Advisor: Prof. [Dongrui Wu](https://scholar.google.com/citations?user=UYGzCPEAAAAJ).


# 🔥 News 
- *2026.01*: &nbsp;🎉🎉 One paper is accepted to [WWW 2026](https://www2026.thewebconf.org/). 
- *2025.12*: &nbsp;🎉🎉 Our survey is accepted to [IEEE TPAMI](https://www.computer.org/csdl/journal/tp). 
- *2025.09*: &nbsp;🎉🎉 Two papers are accepted to [NeurIPS 2025](https://neurips.cc/). 
- *2025.05*: &nbsp;🎉🎉 One paper is accepted to [ACL 2025](https://2025.aclweb.org/). 
- *2025.02*: &nbsp;🎉🎉 One paper is accepted to [CVPR 2025](https://cvpr.thecvf.com/Conferences/2025). 


<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Selected Publications & Preprints

<!-- Tab按钮 -->
<div class="pub-tabs">
  <button class="tab-btn" onclick="filterPubs('publications', this)">publications</button>
  <button class="tab-btn" onclick="filterPubs('preprints', this)">preprints</button>
</div>


<!-- 论文列表 -->
<div class="pub-item publications" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2025</div>
      <img src='images/mvmath.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[MV-MATH: Evaluating Multimodal Math Reasoning in Multi-Visual Contexts](https://eternal8080.github.io/MV-MATH.github.io/)

**Peijie Wang**, Zhong-Zhi Li, Fei Yin, Xin Yang, Dekang Ran, Cheng-Lin Liu

  </div>
</div>
</div>

<div class="pub-item publications" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025 (DB Track)</div>
      <img src='images/solidgeo.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[SOLIDGEO: Measuring Multimodal Spatial Math Reasoning in Solid Geometry](https://solidgeo.github.io/)

**Peijie Wang\***, Chao Yang\*, Zhong-Zhi Li, Fei Yin, Dekang Ran, Mi Tian, Zhilong Ji, Jinfeng Bai, Cheng-Lin Liu

  </div>
</div>
</div>

<div class="pub-item publications" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025</div>
      <img src='images/perl.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[PeRL: Permutation-Enhanced Reinforcement Learning for Interleaved Vision-Language Reasoning](https://github.com/alchemistyzz/PeRL)

Yizhen Zhang, Yang Ding, Shuoshuo Zhang, Xinchen Zhang, Haoling Li, Zhong-zhi Li, **Peijie Wang**, Jie Wu, Lei Ji, Yelong Shen, Yujiu Yang, Yeyun Gong

  </div>
</div>
</div>

<div class="pub-item publications" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACL 2025</div>
      <img src='images/longdocurl.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[LongDocURL: a Comprehensive Multimodal Long Document Benchmark Integrating Understanding, Reasoning, and Locating](https://longdocurl.github.io/)

Chao Deng, Jiale Yuan, Pi Bu, **Peijie Wang**, Zhong-Zhi Li, Jian Xu, Xiao-Hui Li, Yuan Gao, Jun Song, Bo Zheng, Cheng-Lin Liu

  </div>
</div>
</div>



<!-- <div class="pub-item preprints" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arxiv</div>
      <img src='images/vcif.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[VC-IF: Introducing Visual-Constraint Instruction Following for Multi-Turn, Multi-Constraint Vision-Language Models](https://eternal8080.github.io/MV-MATH.github.io/)

Jixiang Hong, Pi Bu, Yingyao Wang, Bo Peng, **Peijie Wang**, Chen Wang, Tengtao Song, Yang Yao, Jun Song, Rui Yan, YuCheng, Bo Zheng

  </div>
</div>
</div> -->

<div class="pub-item publications" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">WWW 2026</div>
      <img src='images/AnchorRAG.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Towards Open-World Retrieval-Augmented Generation on Knowledge Graph: A Multi-Agent Collaboration Framework](https://dl.acm.org/doi/epdf/10.1145/3774904.3792389)

Jiasheng Xu, Mingda Li, Yongqiang Tang, **Peijie Wang**, and Wensheng Zhang

  </div>
</div>
</div>


<div class="pub-item publications" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACL 2026</div>
      <img src='images/geoparsing.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Diagram Parsing for Plane and Solid Geometry with a Unified Formal Language](https://eternal8080.github.io/geoparsing.github.io/)

**Peijie Wang**, Ming-Liang Zhang, Jun Cao, CHAO DENG, Dekang Ran, Pi Bu, Hongda Sun, Xuan Zhang, Yingyao Wang, Jun Song, Bo Zheng, Fei Yin, Cheng-Lin Liu

  </div>
</div>
</div>


<div class="pub-item publications" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2026, Highlight</div>
      <img src='images/vlmloc.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[VLM-Loc: Localization in Point Cloud Maps via Vision-Language Models](https://arxiv.org/abs/2603.09826)

Shuhao Kang, Youqi Liao, **Peijie Wang**, Wenlong Liao, Qilin Zhang, Benjamin Busam, Xieyuanli Chen, Yun Liu

  </div>
</div>
</div>



<div class="pub-item preprints" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arxiv</div>
      <img src='images/mathspacial.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Do MLLMs Really Understand Space? A Mathematical Reasoning Evaluation](https://arxiv.org/abs/2602.11635)

Shuo Lu, Jianjie Cheng, Yinuo Xu, Yongcan Yu, Lijun Sheng, **Peijie Wang**, Siru Jiang, Yongguan Hu, Run Ling, Yihua Shao, Ao Ma, Wei Feng, Lingxiao He, Meng Wang, Qianlong Xie, Xingxing Wang, Nicu Sebe, Ran He, Jian Liang
  </div>
</div>
</div> 

<!-- <div class="pub-item preprints" markdown="1">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">IEEE TAI</div>
      <img src='images/mvapi_1.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Multi-Visual Attention Prompting for Multimodal Mathematical Reasoning](https://eternal8080.github.io/MV-MATH.github.io/)

**Peijie Wang**, Mingda Li, Zhong-Zhi Li, Dekang Ran, Fei Yin, Cheng-Lin Liu

  </div>
</div>
</div>  -->

<!-- Tab样式和交互JS -->
<style>
.pub-tabs {
  margin: 20px 0;
  display: flex;
  gap: 12px;
}

.tab-btn {
  background-color: #2979ff;
  color: white;
  border: none;
  border-radius: 25px;
  padding: 8px 24px;
  font-size: 16px;
  font-weight: 500;
  cursor: pointer;
  transition: background-color 0.2s, opacity 0.2s;
}

.tab-btn:hover {
  background-color: #1565c0;
}

.tab-btn.active {
  background-color: #2979ff;
  opacity: 1;
}

.tab-btn:not(.active) {
  background-color: #90beff;
  opacity: 0.8;
}

.pub-item {
  display: none;
}

.pub-item.visible {
  display: block;
}
</style>

<script>
function filterPubs(type, clickedBtn) {
  // 更新按钮状态
  document.querySelectorAll('.tab-btn').forEach(function(btn) {
    btn.classList.remove('active');
  });
  if (clickedBtn) {
    clickedBtn.classList.add('active');
  }

  // 显示/隐藏对应论文
  document.querySelectorAll('.pub-item').forEach(function(item) {
    if (item.classList.contains(type)) {
      item.classList.add('visible');
    } else {
      item.classList.remove('visible');
    }
  });
}

// ⭐ 立即执行，不依赖DOMContentLoaded
(function() {
  // 等待DOM就绪的轮询方式
  var timer = setInterval(function() {
    var items = document.querySelectorAll('.pub-item');
    var btns  = document.querySelectorAll('.tab-btn');
    if (items.length > 0 && btns.length > 0) {
      clearInterval(timer);
      // 默认激活publications按钮
      btns[0].classList.add('active');
      // 默认显示publications
      items.forEach(function(item) {
        if (item.classList.contains('publications')) {
          item.classList.add('visible');
        }
      });
    }
  }, 50);
})();
</script>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2026*, Merit Student, Chinese Academy of Sciences
- *2025*, ICDAR 2025 Competition on Understanding Chinese College Entrance Exam Papers. Second Place.
- *2025*, Academic Scholarship, Chinese Academy of Sciences
- *2023*, Freshmen Scholarship, Chinese Academy of Sciences
- *2023*, Outstanding Graduate, HUST
- *2020*, Academic Scholarship, HUST



<!-- # 💬 Invited Talks -->
<!-- - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.09 - Now*, [Future Living Lab, Alibaba](), China.