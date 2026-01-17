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


<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-3GCYPY09SM"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-3GCYPY09SM');
</script>

<span class='anchor' id='about-me'></span>

I am a research fellow in the PLSE Lab, [NUS](https://nus.edu.sg/), Singapore, advised by Prof. [Jin-Song Dong](https://www.comp.nus.edu.sg/cs/people/dongjs/). Previously, I was a research fellow in Cyber Security Lab (CSL), [NTU](https://www.ntu.edu.sg/Pages/home.aspx), Singapore, advised by Prof. [Yang Liu](https://personal.ntu.edu.sg/yangliu/). I got a Ph.D. from East China Normal University (ECNU), Shanghai, China (2017-2022), supervised by Prof. [Geguang Pu](https://scholar.google.com/citations?user=niQAGcQAAAAJ&hl=zh-CN) and Prof. [Weikai Miao](https://faculty.ecnu.edu.cn/_s43/mwk/main.psp). I also received my B.S. degree from ECNU (2013-2017). I also collaborate with Dr. [Qing Guo](https://tsingqguo.github.io/) and Dr. [Felix Juefei Xu](http://xujuefei.com/) closely.

My research interest includes Trustworthy AI, focusing on Adversarial Attacks/Defense, LLM, Embodied AI, etc. 
<p style="color: blue;">I am actively seeking highly self-motivated students who have a strong background and interests in my research topics (but are not limited). Please drop me an email with your CV if you are interested in working with me. Together, we have the chance to embark on a gratifying journey, confronting real-world problems and achieving substantial, tangible impacts.</p>

# 🔥 News

<ul>
  <li><em>2026.01</em>: 🎉 One paper is accepted to Usenix Security 2026.</li>
  <li><em>2025.12</em>: 🎉 One paper is accepted to FSE 2026.</li>
  <li><em>2025.12</em>: 🎉 One paper is accepted to ICSE 2026.</li>
  <li><em>2025.09</em>: 🎉 Two papers are accepted to NeurIPS 2025.</li>
  <li><em>2025.06</em>: 🎉 One paper is accepted to ICCV 2025.</li>
  <li><em>2025.06</em>: 🎉 One paper is accepted to CCS 2025.</li>
  <li><em>2025.06</em>: 🎉 One paper is accepted to Usenix Security 2025.</li>
  <li><em>2025.06</em>: 🎉 One paper is accepted to TPAMI 2025.</li>
  <li><em>2025.05</em>: 🎉 One paper is accepted to ACL 2025 (main).</li>
  <li><em>2025.04</em>: 🎉 One paper is accepted to SIGIR 2025.</li>
</ul>

<details>
  <summary>👉 Show earlier news</summary>
  <ul>
    <li><em>2025.03</em>: 🎉 One paper is accepted to TOSEM 2025.</li>
    <li><em>2025.02</em>: 🎉 One paper is accepted to TIFS 2025.</li>
    <li><em>2025.01</em>: 🎉 One paper is accepted to ICLR 2025.</li>
    <li><em>2025.01</em>: 🎉 One paper is accepted to ICSE 2025.</li>
    <li><em>2024.12</em>: 🎉 One paper is accepted to AAAI 2025 (oral).</li>
    <li><em>2024.06</em>: 🎉 One paper is accepted to TIFS 2024.</li>
    <li><em>2024.02</em>: 🎉 One paper is accepted to CVPR 2024.</li>
    <li><em>2023.12</em>: 🎉 One paper is accepted to ICSE 2024.</li>
    <li><em>2023.12</em>: 🎉 One paper is accepted to AAAI 2024.</li>
    <li><em>2023.12</em>: 🎉 One paper is accepted to ICDE 2024.</li>
    <li><em>2023.11</em>: 🎉 One paper is accepted to TMM.</li>
    <li><em>2023.10</em>: 🎉 One paper is accepted to TCSVT.</li>
    <li><em>2023.07</em>: 🎉 One paper is accepted to RTSS 2023.</li>
    <li><em>2023.07</em>: 🎉 One paper is accepted to ACM MM 2023.</li>
    <li><em>2023.02</em>: 🎉 One paper is accepted to CVPR 2023.</li>
    <li><em>2022.10</em>: 🎉 Best Paper Award [ECCV 2022 AROW workshop](https://eccv22-arow.github.io/).</li>
    <li><em>2022.02</em>: 🎉 I obtained the Outstanding Graduate of Shanghai 2022.</li>
    <li><em>2021.10</em>: 🎉 I obtained the National Graduate Fellowship 2022.</li>
  </ul>
</details>


# 📝 Publications 
("*" indicates corresponding author, "#" indicates co-first author.)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX Security 2026</div><img src='pub_images/2026USENIX_VSGsafe.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[VSG-Safe: Spotting NSFW Video through Cross-Frame Evidence]()\\
Yuyang Zhang, Xudong Jiang, Yuxuan Song, Yuxiang Sun, **Yihao Huang**, Run Wang, Shundi Xiao, Lina Wang\\
**USENIX Security Symposium 2026** (CCF-A)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FSE 2026</div><img src='pub_images/2026FSE_SPELL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Casting a SPELL: Sentence Pairing Exploration for LLM Limitation-breaking](https://arxiv.org/pdf/2512.21236)\\
Yifan Huang, Xiaojun Jia, Wenbo Guo, Yuqiang Sun, **Yihao Huang***, Chong Wang, Yang Liu\\
**ACM International Conference on the Foundations of Software Engineering 2026** (CCF-A)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE 2026</div><img src='pub_images/2026ICSE_ADA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ADARULE: LLM-Driven Natural Language to LTL Conversion via Pattern-Adaptive Rule Induction](https://conf.researchr.org/details/icse-2026/icse-2026-research-track/293/ADARULE-LLM-Driven-Natural-Language-to-LTL-Conversion-via-Pattern-Adaptive-Rule-Indu)\\
Jiayi Hu, Jingling Sun, Chong Wang, **Yihao Huang***, Jincao Feng, Yilongfei Xu, Yong Li, Kailong Wang, Weikai Miao, Jin Song Dong, Geguang Pu\\
**IEEE/ACM International Conference on Software Engineering 2026** (CCF-A)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='pub_images/2025NeurIPS_AMA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Analogy-based Multi-Turn Jailbreak against Large Language Models](https://openreview.net/pdf/90ec84387b8d7282640d625e2d28faef32f89000.pdf)\\
Mengjie Wu, **Yihao Huang#**, Zhenjun Lin, Kangjie Chen, Yuyang Zhang, Yuhan Huang, Run Wang, Lina Wang\\
**Annual Conference on Neural Information Processing Systems 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='pub_images/2025NeurIPS_FOA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Adversarial Attacks against Closed-Source MLLMs via Feature Optimal Alignment](https://neurips.cc/media/neurips-2025/Slides/116337_lbhqRMy.pdf)\\
Xiaojun Jia, Sensen Gao, Simeng Qin, Tianyu Pang, Chao Du, **Yihao Huang***, Xinfeng Li, Yiming Li, Bo Li, Yang Liu\\
**Annual Conference on Neural Information Processing Systems 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='pub_images/2025ICCV_HIMRD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Heuristic-Induced Multimodal Risk Distribution Jailbreak Attack for Multimodal Large Language Models](https://openaccess.thecvf.com/content/ICCV2025/papers/Ma_Heuristic-Induced_Multimodal_Risk_Distribution_Jailbreak_Attack_for_Multimodal_Large_Language_ICCV_2025_paper.pdf)\\
Teng Ma, Xiaojun Jia, Ranjie Duan, Xinfeng Li, **Yihao Huang**, Xiaoshuang Jia, Zhixuan Chu, Wenqi Ren\\
**International Conference on Computer Vision 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2025</div><img src='pub_images/2025CCS_FilterFL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[FilterFL: Knowledge Filtering-based Data-Free Backdoor Defense for Federated Learning](https://dl.acm.org/doi/10.1145/3719027.3744883)\\
Yanxin Yang, Ming Hu, Xiaofei Xie, Yue Cao, Pengyu Zhang, **Yihao Huang**, Mingsong Chen\\
**ACM Conference on Computer and Communications Security 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Usenix Security 2025</div><img src='pub_images/2025usenix_USD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[USD: NSFW Content Detection for Text-to-Image Models via Scene Graph](https://www.usenix.org/conference/usenixsecurity25/presentation/zhang-yuyang)\\
Yuyang Zhang, Kangjie Chen, Xudong Jiang, Jiahui Wen, Yihui Jin, Ziyou Liang, **Yihao Huang**, Run Wang, Lina Wang\\
**USENIX Security Symposium 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='pub_images/2025TPAMI_SAAET.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Semantic-Aligned Adversarial Evolution Triangle for High-Transferability Vision-Language Attack](https://arxiv.org/pdf/2411.02669)\\
Xiaojun Jia, Sensen Gao, Qing Guo, Simeng Qin, Ke Ma, **Yihao Huang**, Yang Liu, Ivor Tsang, Xiaochun Cao\\
**IEEE Transactions on Pattern Analysis and Machine Intelligence 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='pub_images/2025ACL_POUGH.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Efficient Universal Goal Hijacking with Semantics-guided Prompt Organization](https://arxiv.org/pdf/2405.14189v2)\\
**Yihao Huang**, Chong Wang, Xiaojun Jia, Qing Guo, Felix Juefei-Xu, Jian Zhang, Yang Liu, Geguang Pu\\
**Annual Meeting of the Association for Computational Linguistics 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2025</div><img src='pub_images/2025SIGIR_PATFinger.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[PATFinger: Prompt-Adapted Transferable Fingerprinting against Unauthorized Multimodal Dataset Usage](https://arxiv.org/pdf/2504.11509)\\
Wenyi Zhang, Ju Jia, Xiaojun Jia, **Yihao Huang**, Xinfeng Li, Cong Wu, and Lina Wang\\
**International ACM SIGIR Conference on Research and Development in Information Retrieval 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOSEM 2025</div><img src='pub_images/2025TOSEM_Jailguard.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[JailGuard: A Universal Detection Framework for LLM Prompt-based Attacks](https://arxiv.org/pdf/2312.10766)\\
Xiaoyu Zhang, Cen Zhang, Tianlin Li, **Yihao Huang**, Xiaojun Jia, Ming Hu, Jie Zhang, Yang Liu, Shiqing Ma, Chao Shen\\
**ACM Transactions on Software Engineering and Methodology 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2025</div><img src='pub_images/2025TIFS_SIAGT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Scale-Invariant Adversarial Attack against Arbitrary-scale Super-resolution](https://arxiv.org/pdf/2503.04385)\\
**Yihao Huang**, Xin Luo, Qing Guo, Felix Juefei-Xu, Xiaojun Jia, Weikai Miao, Geguang Pu, Yang Liu\\
**IEEE Transactions on Information Forensics and Security 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='pub_images/2025ICLR_IGCG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Improved Techniques for Optimization-Based Jailbreaking on Large Language Models](https://arxiv.org/pdf/2405.21018)\\
Xiaojun Jia, Tianyu Pang, Chao Du, **Yihao Huang**, Jindong Gu, Yang Liu, Xiaochun Cao, Min Lin \\
**International Conference on Learning Representations 2025**
</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE 2025</div><img src='pub_images/2025ICSE_CCLLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Understanding the Effectiveness of Coverage Criteria for Large Language Models: A Special Angle from Jailbreak Attacks](https://arxiv.org/pdf/2408.15207)\\
Shide Zhou, Tianlin Li, Kailong Wang, **Yihao Huang**, Ling Shi, Yang Liu, Haoyu Wang \\
**IEEE/ACM International Conference on Software Engineering 2025** (CCF-A)
</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025 (Oral)</div><img src='pub_images/2025AAAI_PGJ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Perception-guided Jailbreak against Text-to-Image Models](https://arxiv.org/pdf/2408.10848)\\
**Yihao Huang**, Le Liang, Tianlin Li, Xiaojun Jia, Run Wang, Weikai Miao, Geguang Pu, Yang Liu \\
**AAAI Conference on Artificial Intelligence 2025** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2024</div><img src='pub_images/2024TIFS_TSC_UAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Texture Re-scalable Universal Adversarial Perturbation](https://arxiv.org/pdf/2406.06089) \\
**Yihao Huang**, Qing Guo, Felix Juefei-Xu, Ming Hu, Xiaojun Jia, Xiaochun Cao, Geguang Pu, Yang Liu \\
**IEEE Transactions on Information Forensics and Security 2024** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='pub_images/2024CVPR_COSALPURE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[CosalPure: Learning Concept from Group Images for Robust Co-Saliency Detection](https://arxiv.org/pdf/2403.18554) \\
Jiayi Zhu, Qing Guo, Felix Juefei-Xu, **Yihao Huang**, Yang Liu, Geguang Pu \\
**Computer Vision and Pattern Recognition 2024** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE 2024</div><img src='pub_images/2024ICSE_RUNNER.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[RUNNER: Responsible UNfair NEuron Repair for Enhancing Deep Neural Network Fairness](https://dl.acm.org/doi/10.1145/3597503.3623334) \\
Tianlin Li, Yue Cao, Jian Zhang, Shiqian Zhao, **Yihao Huang**, Aishan Liu, Qing Guo, Yang Liu \\
**International Conference on Software Engineering 2024** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='pub_images/2024AAAI_PersonalizationBackdoor.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Personalization as a Shortcut for Few-Shot Backdoor Attack against Text-to-Image Diffusion Models](https://arxiv.org/pdf/2305.10701.pdf) \\
**Yihao Huang**, Felix Juefei-Xu, Qing Guo, Jie Zhang, Yutong Wu, Ming Hu, Tianlin Li, Geguang Pu, Yang Liu \\
**AAAI Conference on Artificial Intelligence 2024** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDE 2024</div><img src='pub_images/2024ICDE_FedCross.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[FedCross: Towards Accurate Federated Learning via Multi-Model Cross-Aggregation](https://arxiv.org/pdf/2210.08285.pdf) \\
Ming Hu, Peiheng Zhou, Zhihao Yue, Zhiwei Ling, **Yihao Huang**, Anran Li, Yang Liu, Xiang Lian, Mingsong Chen \\
**IEEE International Conference on Data Engineering 2024** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2023</div><img src='pub_images/2023TMM_AdvBokeh.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Natural & Adversarial Bokeh Rendering via Circle-of-Confusion Predictive Network](https://arxiv.org/pdf/2111.12971.pdf) \\
**Yihao Huang**, Felix Juefei-Xu, Qing Guo, Geguang Pu, Yang Liu \\
**IEEE Transactions on Multimedia 2023** (CCF-B)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2023</div><img src='pub_images/2023TCSVT_DeepNotch.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Dodging DeepFake Detection via Implicit Spatial-Domain Notch Filtering](https://arxiv.org/pdf/2009.09213.pdf) \\
**Yihao Huang**, Felix Juefei-Xu, Qing Guo, Yang Liu, Geguang Pu \\
**IEEE Transactions on Circuits and Systems for Video Technology 2023** (CCF-B)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RTSS 2023</div><img src='pub_images/2023RTSS_GitFL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[GitFL: Uncertainty-Aware Real-Time Asynchronous Federated Learning using Version Control](https://arxiv.org/pdf/2211.12049.pdf) \\
Ming Hu, Zeke Xia, DengKe Yan, Zhihao Yue, Jun Xia, **Yihao Huang**, Yang Liu, Mingsong Chen \\
**IEEE Real-Time Systems Symposium 2023** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='pub_images/2023ACMMM_ALA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ALA: Naturalness-aware Adversarial Lightness Attack](https://arxiv.org/pdf/2201.06070.pdf) \\
**Yihao Huang**, Liangru Sun, Qing Guo, Felix Juefei-Xu, Jiayi Zhu, Jincao Feng, Yang Liu, Geguang Pu \\
**ACM International Conference on Multimedia 2023** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='pub_images/2023CVPR_DeepFakeEvading.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Evading DeepFake Detectors via Adversarial Statistical Consistency](https://openaccess.thecvf.com/content/CVPR2023/papers/Hou_Evading_DeepFake_Detectors_via_Adversarial_Statistical_Consistency_CVPR_2023_paper.pdf) \\
Yang Hou, Qing Guo, **Yihao Huang**, Xiaofei Xie, Lei Ma, Jianjun Zhao \\
**IEEE/CVF Conference on Computer Vision and Pattern Recognition 2023** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2023</div><img src='pub_images/2022IJCV_DeepFakeSurvey.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Countering Malicious DeepFakes: Survey, Battleground, and Horizon](https://openaccess.thecvf.com/content/CVPR2023/papers/Hou_Evading_DeepFake_Detectors_via_Adversarial_Statistical_Consistency_CVPR_2023_paper.pdf) \\
Felix Juefei-Xu, Run Wang, **Yihao Huang**, Qing Guo, Lei Ma, Yang Liu  \\
**International Journal of Computer Vision 2023** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2022</div><img src='pub_images/2022TIFS_Fakelocator.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[FakeLocator: Robust Localization of GAN-Based Face Manipulations](https://ieeexplore.ieee.org/document/9673747) \\
**Yihao Huang**, Felix Juefei-Xu, Qing Guo, Yang Liu, Geguang Pu \\
**IEEE Transactions on Information Forensics and Security 2022** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2021</div><img src='pub_images/2021ACMMM_Advfilter.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[AdvFilter: Predictive Perturbation-aware Filtering against Adversarial Attack via Multi-domain Learning](https://dl.acm.org/doi/10.1145/3474085.3475171) \\
**Yihao Huang**, Qing Guo, Felix Juefei-Xu, Lei Ma, Weikai Miao, Yang Liu, Geguang Pu \\
**ACM International Conference on Multimedia 2021** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FSE 2020</div><img src='pub_images/2020FSE_Frepa.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[FREPA: an automated and formal approach to requirement modeling and analysis in aircraft control domain](https://dl.acm.org/doi/abs/10.1145/3368089.3417047) \\
Jincao Feng, Weikai Miao, Hanyue Zheng, **Yihao Huang**, Jianwen Li, Zheng Wang, Ting Su, Bin Gu, Geguang Pu, Mengfei Yang, Jifeng He \\
**Foundations of Software Engineering 2020** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2020 (Oral)</div><img src='pub_images/2020ACMMM_DeepSonar.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[DeepSonar: Towards Effective and Robust Detection of AI-Synthesized Fake Voices](https://dl.acm.org/doi/abs/10.1145/3394171.3413716) \\
Run Wang, Felix Juefei-Xu, **Yihao Huang**, Qing Guo, Xiaofei Xie, Lei Ma, Yang Liu \\
**ACM International Conference on Multimedia 2020** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2020 (Oral)</div><img src='pub_images/2020ACMMM_Amora.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Amora: Black-box adversarial morphing attack](https://dl.acm.org/doi/10.1145/3394171.3413544) \\
Run Wang, Felix Juefei-Xu, Xiaofei Xie, **Yihao Huang**, Yang Liu \\
**ACM International Conference on Multimedia 2020** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2020 (Oral)</div><img src='pub_images/2020ACMMM_FakePolisher.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[FakePolisher: Making DeepFakes More Detection-Evasive by Shallow Reconstruction](https://dl.acm.org/doi/10.1145/3394171.3413732) \\
**Yihao Huang**, Felix Juefei-Xu, Run Wang, Qing Guo, Lei Ma, Xiaofei Xie, Jianwen Li, Weikai Miao, Yang Liu, Geguang Pu \\
**ACM International Conference on Multimedia 2020** (CCF-A)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2020</div><img src='pub_images/2020IJCAI_Fakespotter.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[FakeSpotter: A Simple yet Robust Baseline for Spotting AI-Synthesized Fake Faces](https://www.ijcai.org/proceedings/2020/476) \\
Run Wang, Felix Juefei-Xu, Lei Ma, Xiaofei Xie, **Yihao Huang**, Jian Wang, Yang Liu \\
**International Joint Conference on Artificial Intelligence 2020** (CCF-A)
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASE 2019</div><img src='pub_images/2019ASE_Prema.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Prema: A Tool for Precise Requirements Editing, Modeling and Analysis ](https://ieeexplore.ieee.org/document/8952250) \\
**Yihao Huang**, Jincao Feng, Hanyue Zheng, Jiayi Zhu, Shang Wang, Siyuan Jiang, Weikai Miao, Geguang Pu  \\
**IEEE/ACM International Conference on Automated Software Engineering 2019** (Tool paper)
</div>
</div> 

# 💻 Service
Reviewer:
- Conference: NeurIPS, ICML, AAAI, CVPR, ICCV, IJCAI, ECCV, ACM MM, ICLR, WWW
- Journal: TCSVT, IJCV, TIP, TKDE, NN, CVIU, JCST, TMM

# 🎖 Honors and Awards
- *2022.10* Best Paper Award in [ECCV 2022 AROW workshop](https://eccv22-arow.github.io/)
- *2022.02* Outstanding Graduate of Shanghai. 
- *2021.10* National Graduate Fellowship, China. 

# 📖 Educations
- *2017.09 - 2022.06*, East China Normal University, Ph.D. 
- *2013.09 - 2017.06*, East China Normal University, Bachelor.
- *2010.09 - 2013.06*, Shanghai Gezhi High School.

# 💬 Invited Talks
- *2024.07*, [WAIC](https://english.shanghai.gov.cn/en-2024waic/index.html), China, Title "Academic Thinking and Future Prospects on DeepFake Detection and Adversarial Attack".
- *2023.09*, [UTOPILOT](http://utopilot.ai/), China, Title "Robustness Evaluation of Visual Perception Systems". \| [Slide](https://github.com/Huang-yihao/Huang-yihao.github.io/blob/main/blob/Invited_talk/UTOPILOT_2023_9_Robustness_Evaluation_of_Visual_Perception_Systems.pdf)
- *2021.10*, [Valse 2021](https://valser.org/2021/#/), China, Title "AdvFilter: Predictive Perturbation-aware Filtering against Adversarial Attack via Multi-domain Learning".

<div style="width: 200px; height: 100px; ">
  <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=ASpz8ZkQ2GWxGPubSejukEoQVn4Q8ScExdJ7d3yC5eM&cl=ffffff&w=a"></script>
</div>

