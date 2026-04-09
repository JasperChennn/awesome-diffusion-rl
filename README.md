# Awesome Diffusion RL [![Awesome](https://raw.githubusercontent.com/sindresorhus/awesome/main/media/badge.svg)](https://github.com/sindresorhus/awesome)


#### Contributions are welcome! Please feel free to submit [pull requests](https://github.com/JasperChennn/awesome-diffusion-rl/blob/main/how_to_PR.md) or [open an issue](https://github.com/JasperChennn/awesome-diffusion-rl/issues) to add papers!<br>

# 🤗 Introduction

This list tracks **papers and open-source code** at the intersection of **diffusion models** and **reinforcement learning**.

# 💖 Citation 
If you find this repo is useful for your research, welcome to 🌟 this repo and cite our work using the following BibTeX:
```bibtex
@misc{awesome-diffusion-rl,
  title        = {Awesome Diffusion RL},
  author       = {JasperChennn and contributors},
  year         = {2026},
  howpublished = {\url{https://github.com/JasperChennn/awesome-diffusion-rl}},
  note         = {Curated list of papers on reinforcement learning for diffusion models},
}
```

---
## Overview

- [Introduction](#introduction)
- [Awesome Diffusion RL](#awesome-diffusion-rl-)
  - [Overview](#overview)
  - [Surveys](#surveys)
  - [Foundation Papers](#foundation-papers)
  - [Diffusion RL papers (T2I、T2V)](#diffusion-rl)
  - [Benchmarks \& Evaluation](#benchmarks--evaluation)
  - [Blog or Technical Report](#blog-or-technical-report)
  - [Related Awesome Lists](#related-awesome-lists)
  - [Citation](#citation)

---
## Surveys

<!-- Add survey papers here. -->

## Foundation Papers

+ **REINFORCE: Simple Statistical Gradient-Following Algorithms for Connectionist Reinforcement Learning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1992)<details><summary>Ronald J. Williams</summary>
        Ronald J. Williams</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/article/10.1007/BF00992696)

+ **TRPO: Trust Region Policy Optimization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2015)<details><summary>John Schulman, Sergey Levine, Philipp Moritz, Michael I. Jordan, et al.</summary>
        John Schulman, Sergey Levine, Philipp Moritz, Michael I. Jordan, et al.</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1502.05477)
[![Code](https://img.shields.io/github/stars/joschu/modular_rl.svg?style=social&label=Star)](https://github.com/joschu/modular_rl)

+ **PPO: Proximal Policy Optimization Algorithms** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (20 Jul 2017)<details><summary>John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, et al.</summary>
        John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, et al.</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1707.06347)
[![Code](https://img.shields.io/github/stars/openai/baselines.svg?style=social&label=Star)](https://github.com/openai/baselines)

+ **DPO: Direct Preference Optimization: Your Language Model is Secretly a Reward Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 May 2023)<details><summary>Eric Mitchell, Rafael Rafailov, Archit Sharma, Chelsea Finn, et al.</summary>
        Eric Mitchell, Rafael Rafailov, Archit Sharma, Chelsea Finn, et al.</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18290)
[![Code](https://img.shields.io/github/stars/eric-mitchell/direct-preference-optimization.svg?style=social&label=Star)](https://github.com/eric-mitchell/direct-preference-optimization)

+ **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models (GRPO)** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (05 Feb 2024)<details><summary>DeepSeek AI, Qihao Zhu, Bowen Chen, Zhanglin Yu</summary>
        DeepSeek AI, Qihao Zhu, Bowen Chen, Zhanglin Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03300)
[![Code](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-Math.svg?style=social&label=Star)](https://github.com/deepseek-ai/DeepSeek-Math)

<h2 id="diffusion-rl">Diffusion RL papers (T2I、T2V)</h2>

+ **Flow-GRPO: Training Flow Matching Models via Online RL** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 May 2025)<details><summary>Jie Liu, Gongye Liu, Jiajun Liang, Yangguang Li, et al.</summary>
        Jie Liu, Gongye Liu, Jiajun Liang, Yangguang Li, Jiaheng Liu, Xintao Wang, Pengfei Wan, Di Zhang, Wanli Ouyang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.05470)
[![Code](https://img.shields.io/github/stars/yifan123/flow_grpo.svg?style=social&label=Star)](https://github.com/yifan123/flow_grpo)

+ **DanceGRPO: Unleashing GRPO on Visual Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 May 2025)<details><summary>Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, et al.</summary>
        Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, Lingting Zhu, Mengzhao Chen, Zhiheng Liu, Wei Liu, Qiushan Guo, Weilin Huang, Ping Luo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.07818)
[![Code](https://img.shields.io/github/stars/XueZeyue/DanceGRPO.svg?style=social&label=Star)](https://github.com/XueZeyue/DanceGRPO)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dancegrpo.github.io/)

+ **SRPO: Directly Aligning the Full Diffusion Trajectory with Fine-Grained Human Preference** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Sep 2025)<details><summary>Xiangwei Shen, Qifeng Chen, Boyang Li, et al.</summary>
        Xiangwei Shen, Qifeng Chen, Boyang Li, Haoqiang Fan, Shuaicheng Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.06942)
[![Code](https://img.shields.io/github/stars/tencent/HunyuanDiT.svg?style=social&label=Star)](https://github.com/tencent/HunyuanDiT/tree/main/srpo)

+ **BranchGRPO: Stable and Efficient GRPO with Structured Branching in Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 Sep 2025)<details><summary>Yuming Li, Yikai Wang, Yuying Zhu, et al.</summary>
        Yuming Li, Yikai Wang, Yuying Zhu, Zhongyu Zhao, Ming Lu, Qi She, Shanghang Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.06040)
[![Code](https://img.shields.io/github/stars/Fredreic1849/BranchGRPO.svg?style=social&label=Star)](https://github.com/Fredreic1849/BranchGRPO)[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fredreic1849.github.io/BranchGRPO-Webpage/)

+ **diffu-GRPO: d1: Scaling Reasoning in Diffusion Large Language Models via Reinforcement Learning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Mar 2026)<details><summary>Hangjie Su, Omer Ofir, Lili Hao, et al.</summary>
        Hangjie Su, Omer Ofir, Lili Hao, Xingyao Zhang, Yunchao Liu, Kai-Wei Chang, Nanyun Peng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.12216)
[![Code](https://img.shields.io/github/stars/dllm-reasoning/d1.svg?style=social&label=Star)](https://github.com/dllm-reasoning/d1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dllm-reasoning.github.io/)

+ **StableDRL: Stabilizing Reinforcement Learning for Diffusion Language Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Mar 2026)<details><summary>Jianyuan Zhong, Kaibo Wang, Ding Ding, et al.</summary>
        Jianyuan Zhong, Kaibo Wang, Ding Ding, Zijin Feng, Haoli Bai, Yang Xiang, Jiacheng Sun, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.06743)

+ **DiffusionNFT: Online Diffusion Reinforcement with Forward Process** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (09 Sep 2025)<details><summary>Kaiwen Zheng, Haotian Ye, Jiashu Xu, et al.</summary>
        Kaiwen Zheng, Haotian Ye, Jiashu Xu, Puheng Li, Huayu Chen, Jiaqi Han, Sheng Liu, Zekun Hao, Ming-Yu Liu, James Zou, Stefano Ermon</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.05767)
[![Code](https://img.shields.io/github/stars/NVlabs/DiffusionNFT.svg?style=social&label=Star)](https://github.com/NVlabs/DiffusionNFT)

+ **GDRO: Group-level Reward Post-training for Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (02 Feb 2026)<details><summary>Hengshuang Zhao, et al. (The University of Hong Kong)</summary>
        Hengshuang Zhao, et al.</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.02036)

+ **DDRL: Data-regularized Reinforcement Learning for Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (04 Dec 2025)<details><summary>NVIDIA & Stanford University</summary>
        Haotian Ye, Kaiwen Zheng, Jiashu Xu, Puheng Li, Huayu Chen, Jiaqi Han, Sheng Liu, Zekun Hao, Ming-Yu Liu, James Zou, Stefano Ermon</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.04332)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://research.nvidia.com/labs/cosmos-lab/ddrl/)

+ **CRD: Diffusion Reinforcement Learning via Centered Reward Distillation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Mar 2026)<details><summary>Yuanzhi Zhu, Xi Wang, Stéphane Lathuilière, Vicky Kalogeiton</summary>
        Yuanzhi Zhu, Xi Wang, Stéphane Lathuilière, Vicky Kalogeiton</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.14128)

## Benchmarks & Evaluation

## Blog or Technical Report

## Related Awesome Lists


