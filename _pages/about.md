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

I am an first-year CS PhD student at [HKUST](https://hkust.edu.hk/), supervised by [Prof. Junxian He](https://jxhe.github.io/). I was a Master's student at [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/), under the supervision of [Prof. Hai Zhao](https://bcmi.sjtu.edu.cn/home/zhaohai/), majoring in computer science. Before that, I received my B.S. degree in the IEEE honor class at SJTU in 2022, majoring in computer science. I also collaborated with [Dr. Zhuosheng Zhang](https://bcmi.sjtu.edu.cn/~zhangzs/) during my undergraduate years.

I used to work as a research intern at Microsoft Research Asia (MSRA) in the [NLC group](https://www.microsoft.com/en-us/research/group/natural-language-computing/), guided by [Dr. Lei Cui](https://www.microsoft.com/en-us/research/people/lecu/). I worked on several interesting research topics related to Document AI, including webpage understanding and document Image foundation models. During May 2023 to Feb 2024, I worked closely with [Prof. Pengfei Liu](http://pfliu.com/) at [GAIR](https://plms.ai/) on various aspects of Large Language Models (LLMs), primarily focusing on the evaluation and alignment of LLMs. Before entering HKUST, I also spent some time on [DeepSeek](https://www.deepseek.com/) LLM Alignment Team as a research intern, conducting research on topics related to general reasoning under the supervision of [Dr. Yu Wu](https://sites.google.com/view/wuyu/home).

<!-- <a href='https://scholar.google.com/citations?user=UX7TpSYAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->

# Publications

(* indicates equal contribution)

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">The Tool Decathlon: Benchmarking Language Agents for Diverse, Realistic, and Long-Horizon Task Execution
</font>
**Junlong Li**\*, Wenshuo Zhao\*, Jian Zhao\*, Weihao Zeng\*, Haoze Wu\*, Xiaochen Wang, Rui Ge, Yuxuan Cao, Yuzhen Huang, Wei Liu, Junteng Liu, Zhaochen Su, Yiyang Guo, Fan Zhou, Lueyang Zhang, Juan Michelini, Xingyao Wang, Xiang Yue, Shuyan Zhou, Graham Neubig, Junxian He\\
**Preprint, 2025** |  [PDF](https://arxiv.org/abs/2510.25726) | [Code](https://github.com/hkust-nlp/Toolathlon) | [Page](https://toolathlon.xyz/) | [Dataset](https://huggingface.co/datasets/hkust-nlp/Toolathlon-Trajectories)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">CodeI/O: Condensing Reasoning Patterns via Code Input-Output Prediction
</font>
**Junlong Li**, Daya Guo, Dejian Yang, Runxin Xu, Yu Wu, Junxian He\\
**ICML 2025 Oral** |  [PDF](https://arxiv.org/abs/2502.07316v3) | [Code](https://github.com/hkust-nlp/CodeIO) | [Page](https://codei-o.github.io/) | [HF Repo](https://huggingface.co/collections/hkust-nlp/codei-o-67a978e28fd926b56a4f55a2)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Diving into Self-Evolving Training for Multimodal Reasoning
</font>
Wei Liu\*, **Junlong Li**\*, Xiwen Zhang, Fan Zhou, Yu Cheng, Junxian He\\
**ICML 2025** |  [PDF](https://arxiv.org/abs/2412.17451) | [Code](https://github.com/hkust-nlp/mstar) | [Page](https://mstar-lmm.github.io/) | [HF Repo](https://huggingface.co/collections/hkust-nlp/m-star-676bbf9f749dbf511e7c4a32)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Programming Every Example: Lifting Pre-training Data Quality like Experts at Scale
</font>
Fan Zhou\*, Zengzhi Wang\*, Qian Liu, **Junlong Li**, Pengfei Liu\\
**ICML 2025** |  [PDF](https://arxiv.org/abs/2409.17115) | [Code](https://github.com/GAIR-NLP/ProX) | [Page](https://gair-nlp.github.io/ProX) | [HF Repo](https://huggingface.co/gair-prox)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Dissecting Human and LLM Preferences
</font>
**Junlong Li**, Fan Zhou, Shichao Sun, Yikai Zhang, Hai Zhao, Pengfei Liu\\
**ACL 2024** |  [PDF](https://arxiv.org/abs/2402.11296) | [Demo](https://huggingface.co/spaces/GAIR/Preference-Dissection-Visualization) | [Code](https://github.com/GAIR-NLP/Preference-Dissection) | [Dataset](https://huggingface.co/datasets/GAIR/preference-dissection)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Reformatted Alignment
</font>
Run-Ze Fan, Xuefeng Li, Haoyang Zou, **Junlong Li**, Shwai He, Ethan Chern, Jiewen Hu, Pengfei Liu\\
**EMNLP 2024, Findings** |  [PDF](https://arxiv.org/abs/2402.12219) | [Code](https://github.com/GAIR-NLP/ReAlign) | [Page](https://gair-nlp.github.io/ReAlign/)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Extending LLMs' Context Window with 100 Samples
</font>
Yikai Zhang, **Junlong Li**, Pengfei Liu\\
**Preprint, 2024** |  [PDF](https://arxiv.org/abs/2401.07004) | [Code](https://github.com/GAIR-NLP/Entropy-ABF)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">The Critique of Critique
</font>
Shichao Sun, **Junlong Li**, Weizhe Yuan, Ruifeng Yuan, Wenjie Li, Pengfei Liu\\
**ACL 2024, Findings** |  [PDF](https://arxiv.org/abs/2401.04518) | [Code](https://github.com/GAIR-NLP/MetaCritique)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Generative Judge for Evaluating Alignment
</font>
**Junlong Li**, Shichao Sun, Weizhe Yuan, Run-Ze Fan, Hai Zhao, Pengfei Liu \\
**ICLR 2024** |  [PDF](https://arxiv.org/abs/2310.05470) | [Code](https://github.com/GAIR-NLP/auto-j) | [Page](https://gair-nlp.github.io/auto-j/)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Generative AI for Math: Abel</font>
Ethan Chern\*, Haoyang Zou\*, Xuefeng Li\*, Jiewen Hu\*, Kehua Feng, **Junlong Li**, Pengfei Liu \\
**Preprint, 2023** | [Code](https://github.com/GAIR-NLP/abel) | [Page](https://gair-nlp.github.io/abel/)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Self-prompted Chain-of-Thought on Large Language Models for
Open-domain Multi-hop Reasoning</font>
Jinyuan Wang, **Junlong Li**, Hai Zhao \\
**EMNLP 2023, Findings** | [PDF](http://arxiv.org/abs/2310.13552) |[Code](https://github.com/noewangjy/SP-CoT)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Self-Prompting Large Language Models for Zero-Shot Open-Domain QA</font>
**Junlong Li**, Jinyuan Wang, Zhuosheng Zhang, Hai Zhao \\
**NAACL 2024** |  [PDF](https://arxiv.org/abs/2212.08635) 
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Dialogue-adaptive language model pre-training from quality estimation
</font>
**Junlong Li**, Zhuosheng Zhang, Hai Zhao \\
**Neurocomputing, 2022** |  [PDF](https://arxiv.org/abs/2009.04984) | [Code](https://github.com/lockon-n/DAPO)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">DiT: Self-supervised pre-training for document image transformer
</font>
**Junlong Li**, Yiheng Xu, Tengchao Lv, Lei Cui, Cha Zhang, Furu Wei \\
**ACM Multimedia 2022** |  [PDF](https://arxiv.org/abs/2203.02378) | [Code](https://github.com/microsoft/unilm/tree/master/dit)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Markuplm: Pre-training of text and markup language for visually-rich document understanding
</font>
**Junlong Li**\*, Yiheng Xu\*, Lei Cui, Furu Wei \\
**ACL 2022** |  [PDF](https://arxiv.org/abs/2110.08518) | [Code](https://github.com/microsoft/unilm/tree/master/markuplm)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Multi-turn dialogue reading comprehension with pivot turns and knowledge
</font>
Zhuosheng Zhang, **Junlong Li**, Hai Zhao \\
**TASLP, 2021** |  [PDF](https://arxiv.org/abs/2102.05474) | [Code](https://github.com/lockon-n/KKT)
</div>

# Educations

- *2025.09 - 2028.6 (expected)*, Ph.D.@HKUST, Computer Science & Engineering
- *2022.09 - 2025.03*, M.S.@SJTU, Computer Science & Engineering
- *2018.09 - 2022.06*, B.S.@SJTU, IEEE honor class, Computer Science.

# Talks

- *2023.10*, Invited talk at CIKM 2023 Workshop on Document Intelligence and Understanding.

# Service

- Reviewer: ACM MM, ARR, ICLR

# Awards

- Hong Kong PhD Fellowship Scheme, 2025

- Yang Yuanqing Education Scholarship (top 0.3%), 2024

- MSRA Stars of Tomorrow (Award of Excellent Intern), 2022

- National Scholarship (top 2%), 2022

- SJTU Zhiyuan Honors Scholarship (top 5%), 2019-2021
