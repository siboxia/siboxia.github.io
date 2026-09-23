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

I am a Ph.D. student in the College of Software at Nankai University and a member of the AIOps@NKU group led by Prof. [Shenglin Zhang](https://nkcs.iops.ai/shenglinzhang/) and Associate Prof. [Yongqian Sun](https://nkcs.iops.ai/yongqiansun/). I received my B.E. degree from Nankai University. My Ph.D. research is supervised by Prof. [Shenglin Zhang](https://nkcs.iops.ai/shenglinzhang/), and my M.S. research was supervised by Associate Prof. [Yongqian Sun](https://nkcs.iops.ai/yongqiansun/).

---

My research focuses on AIOps for microservice systems, supercomputing, and intelligent computing, aiming to automate failure prediction, detection, and diagnosis for large-scale infrastructure. I have published 12 papers in leading international conferences and journals, including IEEE/ACM SC, IEEE/ACM ASE, ACM FSE, ACM WWW, ACM TOSEM, IEEE TSC, and IEEE IOTJ, and I have served as a reviewer for IEEE TR.


# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Our paper "Why Transformers?" is accepted by ACM TOSEM (CCF A).
- *2026.08*: &nbsp;🎉🎉 Our paper "FSLog" is accepted by IEEE IOTJ (JCR Q1).
- *2026.07*: &nbsp;🎉🎉 I start my internship as an Algorithm Engineer at Jingdong Digits Technology Holding Co., Ltd.
- *2026.06*: &nbsp;🎉🎉 Our paper "LagRCA" wins the Distinguished Paper Award in FSE 2026 Industry Track!
- *2026.03*: &nbsp;🎉🎉 Our paper "LagRCA" is accepted by FSE 2025 (CCF A).
- *2025.07*: &nbsp;🎉🎉 We get two posters accepted by APNet 2025 (CCF C).
- *2025.06*: &nbsp;🎉🎉 Our paper "NodeSentry" is accepted by SC 2025 (CCF A).
- *2025.01*: &nbsp;🎉🎉 Our paper "Failure Diagnosis Survey" is accepted by ACM TOSEM (CCF A).
- *2024.10*: &nbsp;🎉🎉 Our paper "UniDiag" is accepted by IEEE TSC (CCF A).
- *2024.08*: &nbsp;🎉🎉 I start my internship as a Technical Research Engineer at 2012 Laboratories, Huawei Technologies Co., Ltd.
- *2024.08*: &nbsp;🎉🎉 Our paper "ART" is accepted by ASE 2024 (CCF A).
- *2024.04*: &nbsp;🎉🎉 Our paper "Miner" is accepted by Journal of Computer Research and Development (CCF T1 in Chinese).
- *2023.06*: &nbsp;🎉🎉 Our paper "DiagFusion" is accepted by IEEE TSC (CCF A).
- *2023.02*: &nbsp;🎉🎉 I start my internship as a Research and Development Engineer at National Supercomputer Center in Tianjin.
- *2022.01*: &nbsp;🎉🎉 Our paper "OmniCluster" is accepted by WWW 2022 (CCF A).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">SC 2025</div><a href="https://dl.acm.org/doi/10.1145/3712285.3759794"><img src='images/nodesentry.png' alt="The overall framework of Nodesentry" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Effective Node-Level Anomaly Detection in HPC Systems via Coarse-Grained Clustering and Fine-Grained Model Sharing](https://dl.acm.org/doi/10.1145/3712285.3759794)

**Sibo Xia**, Yongqian Sun, Xijie Pan, Yuan Yuan, Shenglin Zhang, Shaoyu Hu, Lei Tao, Yuqi Li, and Jinghua Feng

- High-performance computing (HPC) systems are crucial for scientific advancement and engineering breakthroughs. Unexpected performance degradation or system failures can severely impact these endeavors. This paper introduces NodeSentry, a novel unsupervised anomaly detection framework tailored for compute nodes of large-scale HPC systems. NodeSentry leverages a combined approach of coarse-grained clustering and fine-grained model sharing to effectively address the challenges posed by the massive node scales, frequent job transitions, and complex patterns characteristic of modern HPC deployments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">APNet 2025</div><a href="https://dl.acm.org/doi/full/10.1145/3735358.3737815"><img src='images/optprophet.png' alt="The overall framework of OptProphet" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Forewarned is Forearmed: Joint Prediction and Classification of Optical Transceiver Failures in Large-Scale LLM Training Clusters](https://dl.acm.org/doi/full/10.1145/3735358.3737815)

**Sibo Xia**, Long Ma, Junhua Kuang, Shenglin Zhang, Qitong Xie, and Yongqian Sun

- The reliable operation of Large Language Model (LLM) training clusters critically depends on optical transceivers, which face frequent failures with severe operational impacts. We propose OptProphet, a joint failure prediction and classification framework. By modeling temporal dependencies and physical couplings via feature aggregation and automatically addressing imbalanced data distributions, OptProphet significantly enhances prediction sensitivity and classification specificity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">TOSEM 2025</div><a href="https://dl.acm.org/doi/full/10.1145/3715005"><img src='images/survey.png' alt="The overall framework of Survey" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Failure Diagnosis in Microservice Systems: A Comprehensive Survey and Analysis](https://dl.acm.org/doi/full/10.1145/3715005)

Shenglin Zhang, **Sibo Xia**, Wenzhao Fan, Binpeng Shi, Xiao Xiong, Zhenyu Zhong, Minghua Ma, Yongqian Sun, and Dan Pei

- Microservice systems, widely adopted for their scalability and flexibility, pose unique failure diagnosis challenges due to independent deployment and dynamic interactions, which can lead to cascading failures that degrade operational efficiency and user experience. This survey reviews 98 papers from 2003 to the present, covering fundamental concepts, system architecture, problem formulation, and qualitative analyses of best practices and future directions, and additionally compiles publicly available datasets, toolkits, and evaluation metrics for practitioners.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">CRAD 2024</div><a href="https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.202330054"><img src='images/miner.png' alt="The overall framework of Miner" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Response Time Anomaly Diagnosis for Search Service](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.202330054)

**Sibo Xia**, Minghua Ma, Pengxiang Jin, Liyue Cui, Shenglin Zhang, Wa Jin, Yongqian Sun, and Dan Pei

- Timely response is crucial to the user experience of network services. To optimize effectively, service providers must identify the rules—combinations of these attributes—that cause high response time. Existing work faces three challenges: large and unevenly distributed search logs, and the need for rules with high generality. We propose Miner, a framework for multi-dimensional extraction of rules, which employs self-paced sampling to address the first two challenges and Corels to generate rules with high generality and recall.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">FSE 2026 (Distinguished Paper Award)</div><a href="https://dl.acm.org/doi/abs/10.1145/3803437.3805219"><img src='images/lagrca.png' alt="The overall framework of LagRCA" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Bridging the Delay: Lag-Aware Spatio-Temporal Causal Inference for Microservice Root Cause Analysis](https://dl.acm.org/doi/abs/10.1145/3803437.3805219)

Shenglin Zhang, Junhua Kuang, Yimeng Zhang, **Sibo Xia**, Jintao Feng, Jingyu Wang, Wenwei Gu, Yongqian Sun, Wei Li, Liping Zhang, and Dan Pei

- Timely root cause analysis (RCA) is essential for stable microservice operations. Yet, most existing methods analyze service interactions synchronously and fail to account for multi-lag failure propagation, where downstream symptoms emerge seconds or minutes after upstream causes—diluting true culprits and over-ranking victims. We present LagRCA, a lag-aware spatio-temporal causal inference framework that models failure propagation with heterogeneous time lags, aligning upstream causes with lagged downstream symptoms. It further disentangles causal dependence from metric co-fluctuation to avoid misreading shared state changes as direct causality, and produces interpretable propagation paths.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">TOSEM 2026</div><a href="https://dl.acm.org/doi/abs/10.1145/3840387"><img src='images/transformer.png' alt="The overall framework of Transformer" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Why Transformers? A Comprehensive Overview of Transformers in Artificial Intelligence for IT Operations](https://dl.acm.org/doi/abs/10.1145/3840387)

Binpeng Shi, Shenglin Zhang, Jingya Wang, Bowen Hao, Minyi Shao, Yu Luo, Wenwei Gu, Yongqian Sun, **Sibo Xia**, Yongxin Zhao, and Dan Pei

- Transformers are driving advances in AIOps. Yet, prior reviews fail to explain why they trigger a major paradigm shift, covering multimodal data, structural connections, capabilities, and evaluation only partially. To bridge this gap, we decompose "Why Transformers" into three questions—the roles Transformers assume in AIOps across 70 representative papers, why they excel (a capability framework of two basic and four advanced capabilities), and how to evaluate them (offline datasets, standardized questions, and real-time simulations)—along with distilled best practices for real-world adoption.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">TSC 2024</div><a href="https://ieeexplore.ieee.org/abstract/document/10740010"><img src='images/unidiag.png' alt="The overall framework of UniDiag" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[No More Data Silos: Unified Microservice Failure Diagnosis With Temporal Knowledge Graph](https://ieeexplore.ieee.org/abstract/document/10740010)

Shenglin Zhang, Yongxin Zhao, **Sibo Xia**, Shirui Wei, Yongqian Sun, Chenyu Zhao, Shiyu Ma, Junhua Kuang, Bolin Zhu, Lemeng Pan, Yicheng Guo, and Dan Pei

- Microservice systems demand efficient failure diagnosis—detection and triage—yet existing methods relying on single-modal data miss failures and neglect multimodal interconnections, and recent fusion studies lack deep integration. We propose UniDiag, which uses temporal knowledge graphs to fuse multimodal data, combining stream-based anomaly detection with a microservice-oriented graph embedding method for comprehensive, low-cost diagnosis.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">ASE 2024</div><a href="https://dl.acm.org/doi/abs/10.1145/3691620.3695495"><img src='images/art.png' alt="The overall framework of ART" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[ART: A Unified Unsupervised Framework for Incident Management in Microservice Systems](https://dl.acm.org/doi/abs/10.1145/3691620.3695495)

Yongqian Sun, Binpeng Shi, Mingyu Mao, Minghua Ma, **Sibo Xia**, Shenglin Zhang, and Dan Pei

- Most incident management techniques for microservice systems tackle anomaly detection, failure triage, and root cause localization in isolation, overlooking shared knowledge and causing inefficiency and delayed responses. We propose ART, an unsupervised framework that unifies the three tasks by extracting shared knowledge—modeling channel, temporal, and call dependencies with Transformer Encoder, GRU, and GraphSAGE—to produce interpretable, semantically explicit failure representations for multitask solutions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">TSC 2023</div><a href="https://ieeexplore.ieee.org/abstract/document/10165686"><img src='images/diagfusion.png' alt="The overall framework of DiagFusion" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Robust Failure Diagnosis of Microservice System Through Multimodal Data](https://ieeexplore.ieee.org/abstract/document/10165686)

Shenglin Zhang, Pengxiang Jin, Zihan Lin, Yongqian Sun, Bicheng Zhang, **Sibo Xia**, Zhengdan Li, Zhenyu Zhong, Minghua Ma, Wa Jin, Dai Zhang, Zhenyu Zhu, and Dan Pei

- Automatic failure diagnosis is crucial for large microservice systems, yet most existing methods rely solely on single-modal data. Through an empirical study on real-world failure cases, we show that combining these data sources yields more accurate diagnosis, though effectively representing multimodal data and addressing imbalanced failures remain challenging. We propose DiagFusion, which uses embedding techniques and data augmentation to represent multimodal data of service instances, builds a dependency graph from deployment data and traces, and employs a graph neural network to localize the root cause instance and determine the failure type.
</div>
</div>

# 🎖 Honors and Awards
- *2026.09* 🎓 Merit Student Award at Nankai University
- *2026.07* 🎓 FSE 2026 Industry Track Distinguished Paper Award (The Only Recipient)
- *2026.06* 🎓 Outstanding Communist Party Member at Nankai University 
- *2025.12* 🎓 Young Science and Technology Scientists Sponsorship Program by CAST - Doctoral Student Special Plan
- *2025.10* 🎓 National Scholarship
- *2025.10* 🎓 Shiing-Shen Chern Academic Newcomer Scholarship of Nankai University
- *2025.10* 🎓 First prize of the Gongneng Scholarship of Nankai University for Graduate Students
- *2024.10* 🎓 Third prize of the Gongneng Scholarship of Nankai University for Graduate Students 
- *2023.10* 🎓 First prize of the Gongneng Scholarship of Nankai University for Graduate Students
- *2023.09* 🎓 Outstanding Undergraduate Teaching Assistant
- *2022.10* 🎓 Second prize of the Gongneng Scholarship of Nankai University for Graduate Students
- *2022.10* 🎓 Scholarship of Nankai University for Postgraduate Recommendation

# 📖 Educations
- *2024.09 - Now*, Ph.D., Software Engineering, Nankai University, China, advisor [Shenglin Zhang](https://nkcs.iops.ai/shenglinzhang/)
- *2022.09 - 2024.06*, M.S. (Successive Postgraduate and Doctoral Programs), Software Engineering, Nankai University, China, advisor [Yongqian Sun](https://nkcs.iops.ai/yongqiansun/)
- *2018.09 - 2022.06*, B.E., Software Engineering, Nankai University, China

# 💻 Internships
- *2026.07 - Now*, Algorithm Engineer, Jingdong Digits Technology Holding Co., Ltd.
- *2024.08 - 2026.07*, Technical Research Engineer, Huawei Technologies Co., Ltd.
- *2023.02 - 2023.11*, Research and Development Engineer, National Supercomputer Center in Tianjin

# 💬 Invited Talks
- *2025.11*, Effective Node-Level Anomaly Detection in HPC Systems via Coarse-Grained Clustering and Fine-Grained Model Sharing, SC 2025, [Link](https://sc25.conference-program.com/presentation/?id=pap259&sess=sess178)
- *2025.08*, Delivered a speech at the Exchange Forum (Phase 2) organized by Huawei Technologies Co., Ltd.
