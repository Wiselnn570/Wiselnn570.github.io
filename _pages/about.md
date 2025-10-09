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

I am currently pursuing a PhD at <a href='https://www.fudan.edu.cn/en/'>Fudan University</a> under the supervision of Prof. <a href='http://dahua.site'>Dahua Lin</a>. Additionally, I am an intern at the <a href='https://www.shlab.org.cn/'>Shanghai AI Laboratory</a>, where I am mentored by <a href='https://yuhangzang.github.io'>Yuhang Zang</a>.

My research interests lie in **multimodal large language models (MLLMs)**, **video understanding**, and **efficient reasoning**. I am passionate about contributing to impactful and meaningful research. If you're interested in my work, please feel free to reach out to me via email or WeChat (Wiselnn570o0) for **potential collaboration**.



# 🔥 News
- [2025-05-01] One paper, VideoRoPE, is accepted by ICML 2025 as **oral presentation**.
- [2024-09-28] Two papers, ShareGPT4Video and MMDU, are accepted by NeurIPS2024.


# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/videorope.png' alt="VideoRoPE" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VideoRoPE: What Makes for Good Video Rotary Position Embedding?](https://github.com/Wiselnn570/VideoRoPE)***[Accepted by ICML2025 as Oral Presentation!]***

***Xilin Wei****, Xiaoran Liu*, Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Jian Tong, Haodong Duan, Qipeng Guo, Jiaqi Wang, Xipeng Qiu, Dahua Lin

<span> This work introduces VideoRoPE, which addresses four key properties essential for RoPE in video applications. By incorporating Low-frequency Temporal Allocation (LTA), Diagonal Layout (DL), and Adjustable Temporal Spacing (ATS), VideoRoPE effectively meets these requirements. We also present the V-NIAH-D retrieval task to expose the limitations of current position embedding designs, especially in frequency allocation. Our findings show that existing Video LLMs are prone to frequency-based distractors. Extensive experiments demonstrate that VideoRoPE consistently outperforms other RoPE variants.</span>

[**Github** ![](https://img.shields.io/github/stars/Wiselnn570/VideoRoPE)](https://github.com/Wiselnn570/VideoRoPE)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/Visual-RFT.png' alt="Visual-RFT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visual-RFT: Visual Reinforcement Fine-Tuning](https://github.com/Liuziyu77/Visual-RFT)***[Accepted by ICCV2025!]***

***Ziyu Liu***, Zeyi Sun, Yuhang Zang, Xiaoyi Dong, Yuhang Cao, Haodong Duan, Dahua Lin, Jiaqi Wang

<span> We introduce Visual Reinforcement Fine-tuning (Visual-RFT), the first comprehensive adaptation of Deepseek-R1's RL strategy to the multimodal field. We use the Qwen2-VL-2/7B model as our base model and design a rule-based verifiable reward, which is integrated into a GRPO-based reinforcement fine-tuning framework to enhance the performance of LVLMs across various visual perception tasks.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT)](https://github.com/Liuziyu77/Visual-RFT)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MIA-DPO.png' alt="MIA-DPO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large Vision-Language Models](https://arxiv.org/abs/2410.17637)***[Accepted by ICLR2025!]***

***Ziyu Liu***, Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Haodong Duan, Conghui He, Yuanjun Xiong, Dahua Lin, Jiaqi Wang

<span> We present Multi-Image Augmented Direct Preference Optimization (MIA-DPO), a visual preference alignment approach that effectively handles multi-image inputs. We use attention values to identify and filter out rejected responses the model may have mistakenly focused on...</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/MIA-DPO)](https://github.com/Liuziyu77/MIA-DPO)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MMDU.png' alt="MMDU" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs](https://arxiv.org/abs/2406.11833) ***[Accepted by NeurIPS2024!]***

***Ziyu Liu***, Tao Chu, Yuhang Zang, Xilin Wei, Xiaoyi Dong, Pan Zhang, Zijian Liang, Yuanjun Xiong, Yu Qiao, Dahua Lin, Jiaqi Wang

<span> We introduce MMDU, a comprehensive benchmark, and MMDU-45k, a large-scale instruction tuning dataset, designed to evaluate and improve LVLMs' abilities in multi-turn and multi-image conversations.Our benchmark showcases a conversational setting with a maximum of 20 images and 17 turns. With a maximum of 18k text+image tokens, MMDU evaluates the capacity of LVLMs to process and comprehend extended contextual information with a long context history.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/MMDU)](https://github.com/Liuziyu77/MMDU)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/V3Det_challenge.png' alt="V3Det_challenge" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[V3Det Challenge 2024 on Vast Vocabulary and Open Vocabulary Object Detection: Methods and Results](https://arxiv.org/abs/2406.11739)

Jiaqi Wang, Yuhang Zang, Pan Zhang, Tao Chu, Yuhang Cao, Zeyi Sun, ***Ziyu Liu***, Xiaoyi Dong, Tong Wu, Dahua Lin, Zeming Chen, Zhi Wang, Lingchen Meng, Wenhao Yao, Jianwei Yang, Sihong Wu, Zhineng Chen, Zuxuan Wu, Yu-Gang Jiang, Peixi Wu, Bosong Chai, Xuan Nie, Longquan Yan, Zeyu Wang, Qifan Zhou, Boning Wang, Jiaqi Huang, Zunnan Xu, Xiu Li, Kehong Yuan, Yanyan Zu, Jiayao Ha, Qiong Gao, Licheng Jiao

[**Homepage**](https://v3det.openxlab.org.cn/challenge)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/RAR.png' alt="RAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RAR:Retrieving And Ranking Augmented MLLMs for Visual Recognition](https://arxiv.org/abs/2403.13805)

***Ziyu Liu***, Zeyi Sun, Yuhang Zang, Wei Li, Pan Zhang, Xiaoyi Dong, Yuanjun Xiong, Dahua Lin, Jiaqi Wang

<span> Combining retrieving and ranking with multi-modal large language models to revolutionize perception tasks such as fine-grained recognition, zero-shot image recognition, and few-shot object recognition. Our method opens up new avenues for research in augmenting the MLLM’s abilities with the retrieving-augmented solution and could be beneficial for other tasks such as reasoning and generation in future works.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/RAR)](https://github.com/Liuziyu77/RAR)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MMlong.png' alt="RAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMLONGBENCH-DOC: Benchmarking Long-context Document Understanding with Visualizations](https://arxiv.org/abs/2407.01523) ***[Accepted by NeurIPS2024!(Spotlight)]***

Yubo Ma, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, ***Ziyu Liu***, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-Gang Jiang, Jiaqi Wang, Yixin Cao, Aixin Sun

[**Github** ![](https://img.shields.io/github/stars/mayubo2333/MMLongBench-Doc)](https://github.com/mayubo2333/MMLongBench-Doc)
</div>
</div>


# 🎖 Honors and Awards
- *2024.06*, Excellent Bachelor's Thesis，Outstanding Undergraduate Graduate.
- *2023.07*, Meritorious Award, Mathematical Contest in Modeling and Interdisciplinary Contest in Modeling (MCM/ICM), COMAP.
- *2022.05*, National Second Prize, China Undergraduate Mathematical Contest in Modeling(CUMCM), China Society for Industrial and Applied Mathematics(CSIAM).
- *2022.05*, Finalist Award, Mathematical Contest in Modeling and Interdisciplinary Contest in Modeling (MCM/ICM), COMAP.

# 📖 Educations
- *2024.09 - until now*, PHD, Shanghai Jiao Tong University.

# 📌 Activities
- Conference reviewer of ICLR, Neurips.