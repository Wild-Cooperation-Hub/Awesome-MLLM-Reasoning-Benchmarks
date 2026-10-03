# Awesome MLLM Reasoning Benchmarks

A Comprehensive Survey on Evaluating Reasoning Capabilities in Multimodal Large Language Models.

<p align="left">
  <b>Authors: <a href="https://scholar.google.com/citations?user=dqLvhvIAAAAJ&hl=zh-CN">Yaya Shi</a> and <a href="https://scholar.google.com/citations?user=qtdueToAAAAJ&hl=en">Zongyang Ma</a></b>
</p>



### Table of Contents
- [Awesome MLLM Reasoning Benchmarks](#awesome-mllm-reasoning-benchmarks)
    - [Mathematical Reasoning](#mathematical-reasoning)
    - [Chart reasoning](#chart-reasoning)
    - [Scientific Reasoning](#scientific-reasoning)
    - [Code Generation](#code-generation)
    - [Multi-Image Based Inductive Reasoning](#multi-image-based-inductive-reasoning)
    - [Social and Cultural Knowledge Reasoning](#social-and-cultural-knowledge-reasoning)
    - [Algorithmic Problem](#algorithmic-problem)
    - [Action Prediction](#action-prediction)
    - [Spatial Reasoning](#spatial-reasoning)
    - [Other Comprehensive MM Reasoning Benchmarks](#other-comprehensive-mm-reasoning-benchmarks)


### Mathematical Reasoning
- WE-MATH: Does Your Large Multimodal Model Achieve Human-like Mathematical Reasoning?
  - 📜 Paper: https://arxiv.org/pdf/2407.01284
  - 🤗 Dataset: https://huggingface.co/datasets/We-Math/We-Math

- (ICLR 2024 Oral) Mathvista: Evaluating math reasoning in visual contexts with gpt-4v, bard, and other large multimodal models
  - 📜 Paper: https://arxiv.org/pdf/2310.02255
  - 📚 Project: https://mathvista.github.io
  - 💻 Code: https://github.com/lupantech/MathVista
  - 🤗 Dataset: https://huggingface.co/datasets/AI4Math/MathVista
  - 🏆 LeaderBoard: https://mathvista.github.io/#leaderboard
  
- (ECCV 2024) MathVerse: Does Your Multi-modal LLM Truly See the Diagrams in Visual Math Problems
  - 📜 Paper: https://arxiv.org/pdf/2403.14624
  - 📚 Project: https://mathverse-cuhk.github.io
  - 💻 Code: https://github.com/ZrrSkywalker/MathVerse
  - 🤗 Dataset: https://huggingface.co/datasets/AI4Math/MathVerse
  - 🏆 LeaderBoard: https://mathverse-cuhk.github.io/#leaderboard

- (NeurIPS DB Track 2024) MATH-Vision: Measuring Multimodal Mathematical Reasoning with MATH-Vision Dataset
  - 📜 Paper: https://arxiv.org/pdf/2402.14804
  - 📚 Project: https://mathllm.github.io/mathvision
  - 💻 Code: https://github.com/mathllm/MATH-V
  - 🤗 Dataset: https://huggingface.co/datasets/MathLLMs/MathVision
  - 🏆 LeaderBoard: https://mathllm.github.io/mathvision/#leaderboard

- MathScape: Evaluating MLLMs in multimodal Math Scenarios through a Hierarchical Benchmark 【中文】
  - 📜 Paper: https://arxiv.org/pdf/2408.07543
  - 💻 Code: https://github.com/PKU-Baichuan-MLSystemLab/MathScape?tab=readme-ov-file
  - 🤗 Dataset: https://drive.google.com/file/d/1Y3cnKPyryM0_m5QJQIOkF09KjDO9Q_QH/view

- CMM-Math: A Chinese Multimodal Math Dataset To Evaluate and Enhance the Mathematics Reasoning of LMMs 【中文】
  - 📜 Paper: https://arxiv.org/pdf/2409.02834
  - 💻 Code: https://github.com/ECNU-ICALK/EduChat-Math/

- OlympiadBench: A Challenging Benchmark for Promoting AGI with Olympiad-Level Bilingual Multimodal Scientific Problems
  - 📜 Paper: https://arxiv.org/pdf/2402.14008
  - 🤗 Dataset: https://huggingface.co/datasets/Hothan/OlympiadBench

- MV-MATH: Evaluating Multimodal Math Reasoning in Multi-Visual Contexts
- 📜 Paper: https://arxiv.org/pdf/2502.20808
- 📚 Project: https://eternal8080.github.io/MV-MATH.github.io/
- 💻 Code: https://github.com/eternal8080/MV-MATH
- 🤗 Dataset: https://huggingface.co/datasets/PeijieWang/MV-MATH

### Chart Reasoning
- When Does an Image Determine the Answer? Benchmarking Visual Answerability across Charts and Scenes
  - 📜 Paper: https://arxiv.org/abs/2609.34480

- ChartBench: A Benchmark for Complex Visual Reasoning in Charts
  - 📜 Paper: https://arxiv.org/pdf/2312.15915
  - 📚 Project: https://chartbench.github.io/
  - 🤗 Dataset: https://huggingface.co/datasets/SincereX/ChartBench
  
- MultiChartQA: Benchmarking Vision-Language Models on Multi-Chart Problems
  - 📜 Paper: https://arxiv.org/pdf/2410.14179v2
  - 💻 Code: https://github.com/Zivenzhu/Multi-chart-QA

- (Neurips DB Track 2024) Chartxiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs
  - 📜 Paper: https://arxiv.org/pdf/2406.18521
  - 📚 Project: https://charxiv.github.io/
  - 🤗 Dataset: https://huggingface.co/datasets/princeton-nlp/CharXiv


### Scientific Reasoning

- M4U: Evaluating Multilingual Understanding and Reasoning for Large Multimodal Models
  - 📜 Paper: https://arxiv.org/pdf/2405.15638
  - 📚 Project: https://m4u-benchmark.github.io/m4u.github.io/
  - 🤗 Dataset: https://huggingface.co/datasets/M4U-Benchmark/M4U
  
- MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI
  - 📜 Paper: https://arxiv.org/pdf/2311.16502
  - 🤗 Dataset: https://huggingface.co/datasets/MMMU/MMMU
  
- MMMU-Pro: A More Robust Multi-discipline Multimodal Understanding Benchmark
  - 📜 Paper: https://arxiv.org/pdf/2409.02813
  - 🤗 Dataset: https://huggingface.co/datasets/MMMU/MMMU_Pro
  
- Science qa : Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering
  - 📜 Paper: https://arxiv.org/pdf/2209.09513
  - 🤗 Dataset: https://huggingface.co/datasets/derek-thomas/ScienceQA

- TheoremQA: A Theorem-driven Question Answering Dataset
  - 📜 Paper: https://arxiv.org/pdf/2305.12524
  - 🤗 Dataset: https://huggingface.co/datasets/TIGER-Lab/TheoremQA

- Can MLLMs Reason in Multimodality? EMMA: An Enhanced MultiModal ReAsoning Benchmark
  - 📜 Paper: https://arxiv.org/pdf/2501.05444v1
  - 🤗 Dataset: https://huggingface.co/datasets/luckychao/EMMA

- GAOKAO-MM: A Chinese Human-Level Benchmark for Multimodal Models Evaluation
  - 📜 Paper: https://arxiv.org/pdf/2402.15745
  - 💻 Code: https://github.com/OpenMOSS/GAOKAO-MM

- OlympiadBench: A Challenging Benchmark for Promoting AGI with Olympiad-Level Bilingual Multimodal Scientific Problems [中英文]
  - 📜 Paper: https://arxiv.org/pdf/2402.14008
  - 🤗 Dataset: https://huggingface.co/datasets/Hothan/OlympiadBench

- CMMMU: A Chinese Massive Multi-discipline Multimodal Understanding Benchmark [中文]
  - 📜 Paper: https://arxiv.org/pdf/2401.11944
  - 🤗 Dataset: https://huggingface.co/datasets/m-a-p/CMMMU

### Code Generation

- ChartMimic: Evaluating LMM’s Cross-Modal Reasoning Capability via Chart-to-Code Generation
  - 📜 Paper: https://arxiv.org/pdf/2406.09961
  - 💻 Code: https://github.com/ChartMimic/ChartMimic
  - 🤗 Dataset: https://huggingface.co/datasets/ChartMimic/ChartMimic

- Plot2Code: A Comprehensive Benchmark for Evaluating Multi-modal Large Language Models in Code Generation from Scientific Plots 
  - 📜 Paper: https://arxiv.org/pdf/2405.07990
  - 🤗 Dataset: https://huggingface.co/datasets/TencentARC/Plot2Code

- HumanEval-V: Evaluating Visual Understanding and Reasoning Abilities of Large Multimodal Models Through Coding Tasks
  - 📜 Paper: https://arxiv.org/pdf/2410.12381
  - 💻 Code: https://github.com/HumanEval-V/HumanEval-V-Benchmark
  - 🤗 Dataset: https://huggingface.co/datasets/HumanEval-V/HumanEval-V-Benchmark
  - 🏆 LeaderBoard: https://humaneval-v.github.io/#leaderboard


### Multi-Image Based Inductive Reasoning
- MM-IQ: Benchmarking Human-Like Abstraction and Reasoning in Multimodal Models
  - 📜 Paper: https://arxiv.org/pdf/2502.00698
  - 🤗 Dataset: https://huggingface.co/datasets/huanqia/MM-IQ
  
- LogicVista: Multimodal LLM Logical Reasoning Benchmark in Visual Contexts
  - 📜 Paper: https://arxiv.org/pdf/2407.04973
  - 💻 Code: https://github.com/Yijia-Xiao/LogicVista

- The Jumping Reasoning Curve? Tracking the Evolution of Reasoning Performance in GPT-[n] and o-[n] Models on Multimodal Puzzles
  - 📜 Paper: https://arxiv.org/pdf/2502.01081
  - 💻 Code: https://github.com/declare-lab/LLM-PuzzleTest/


### Social and Cultural Knowledge Reasoning
- Computational Meme Understanding: A Survey
  - 📜 Paper: https://aclanthology.org/2024.emnlp-main.1184.pdf
  
- II-Bench: An Image Implication Understanding Benchmark for Multimodal Large Language Models
  - 📜 Paper: https://arxiv.org/pdf/2406.05862
  - 🤗 Dataset: https://huggingface.co/datasets/m-a-p/II-Bench

- Can MLLMs Understand the Deep Implication Behind Chinese Images? [中文]
  - 📜 Paper: https://arxiv.org/pdf/2410.13854
  - 📚 Project: https://cii-bench.github.io/
  - 🤗 Dataset: https://huggingface.co/datasets/m-a-p/CII-Bench
  - 🏆 LeaderBoard: https://cii-bench.github.io/#leaderboard

- PunchBench: Benchmarking MLLMs in Multimodal Punchline Comprehension
  - 📜 Paper: https://arxiv.org/pdf/2412.11906
  
- GPT-4V(ision) as A Social Media Analysis Engine
  - 📜 Paper: https://arxiv.org/pdf/2311.07547
  - 💻 Code: https://github.com/VIStA-H/GPT-4V_Social_Media
  
- Geolocation with Real Human Gameplay Data:A Large-Scale Dataset and Human-Like Reasoning Framework
  - 📜 Paper: https://arxiv.org/pdf/2502.13759


### Algorithmic Problem
- NPHardEval4V: A Dynamic Reasoning Benchmark of Multimodal Large Language Models
  - 📜 Paper: https://arxiv.org/pdf/2403.01777
  - 💻 Code: https://github.com/lizhouf/NPHardEval4V



### Action Prediction

- Autonomous Driving
  - Exploring the Potential of Multi-Modal AI for Driving Hazard Prediction
      - 📜 Paper: https://arxiv.org/pdf/2310.04671v4
      - 💻 Code: https://github.com/DHPR-dataset/DHPR-dataset
      - 🤗 Dataset: https://huggingface.co/datasets/DHPR/Driving-Hazard-Prediction-and-Reasoning
      
- Robot Manipulation
  - A Real-to-Sim-to-Real Approach to Robotic Manipulation with VLM-Generated Iterative Keypoint Rewards
      - 📜 Paper: https://arxiv.org/pdf/2502.08643
      - 💻 Code: https://github.com/shivanshpatel35/IKER
      - 📚 Project: https://iker-robot.github.io/
      - 📚 Project: https://simpler-env.github.io/

- Gui Agent
  - InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection
      - 📜 Paper: https://arxiv.org/pdf/2501.04575
      - 💻 Code: https://github.com/Reallm-Labs/InfiGUIAgent
      - 🤗 Dataset: https://huggingface.co/datasets/Reallm-Labs/InfiGUIAgent-Data

  - Mind2Web: Towards a Generalist Agent for the Web
      - 📜 Paper: https://arxiv.org/abs/2306.06070
      - 📚 Project: https://osu-nlp-group.github.io/Mind2Web/
      - 💻 Code: https://github.com/OSU-NLP-Group/Mind2Web
      - 🤗 Dataset: https://huggingface.co/datasets/osunlp/Mind2Web

  - SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents
      - 📜 Paper: https://arxiv.org/pdf/2401.10935



### Spatial Reasoning
- Spatial Planing
    - Imagine while Reasoning in Space: Multimodal Visualization-of-Thought
        - 📜 Paper: https://arxiv.org/pdf/2501.07542
    
    - iVISPAR — An Interactive Visual-Spatial Reasoning Benchmark for VLMs 
        - 📜 Paper: https://arxiv.org/pdf/2502.03214v1
        - 💻 Code: https://github.com/SharkyBamboozle/iVISPAR

- Spatial Relationship
    - PulseCheck457: A Diagnostic Benchmark for Comprehensive Spatial Reasoning of Large Multimodal Models
        - 📜 Paper: https://www.arxiv.org/pdf/2502.08636
    
    - Defining and Evaluating Visual Language Models’ Basic Spatial Abilities:A Perspective from Psychometrics
        - 📜 Paper: https://arxiv.org/pdf/2502.11859


### Other Comprehensive MM Reasoning Benchmarks
- M3CoT: A Novel Benchmark for Multi-Domain Multi-step Multi-modal Chain-of-Thought
  - 📜 Paper: https://arxiv.org/pdf/2405.16473
  - 🤗 Dataset: https://huggingface.co/datasets/LightChen2333/M3CoT

- MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action
  - 📜 Paper: https://arxiv.org/pdf/2303.11381
  - 💻 Code: https://github.com/microsoft/MM-REACT

- MME-CoT: Benchmarking Chain-of-Thought in Large Multimodal Models for Reasoning Quality, Robustness, and Efficiency
  - 📜 Paper: https://arxiv.org/pdf/2502.09621
  - 📚 Project: https://mmecot.github.io/
  - 🤗 Dataset: https://huggingface.co/datasets/CaraJ/MME-CoT

- LlamaV-o1: Rethinking Step-by-step Visual Reasoning in LLMs
  - 📜 Paper: https://arxiv.org/pdf/2501.06186
  - 🤗 Dataset: https://huggingface.co/datasets/omkarthawakar/VRC-Bench

- (Neurips DB Track 2024) MLLM-CompBench: A Comparative Reasoning Benchmark for Multimodal LLMs
  - 📜 Paper: https://arxiv.org/pdf/2407.16837
  - 📚 Project: https://compbench.github.io/


- ZeroBench: An Impossible* Visual Benchmark for Contemporary Large Multimodal Models
  - 📜 Paper: https://arxiv.org/pdf/2502.09696
  - 📚 Project: https://zerobench.github.io/

- R1-onevision
  - 📚 Project: https://yangyi-vai.notion.site/r1-onevision
  - 🤗 Dataset: https://huggingface.co/datasets/Fancy-MLLM/R1-Onevision-Bench

- LRMBench: A Comprehensive and Challenging Benchmark for Vision-Language Reward Models
  - 📜 Paper: https://arxiv.org/pdf/2411.17451
  - 📚 Project: https://vl-rewardbench.github.io/
  - 💻 Code: https://github.com/vl-rewardbench/VL_RewardBench
  - 🤗 Dataset: https://huggingface.co/datasets/MMInstruction/VL-RewardBench
  - 🏆 LeaderBoard: https://huggingface.co/spaces/MMInstruction/VL-RewardBench
 
### TODO
- ☑️☑️☑️ Based on the aforementioned research, we are currently in the process of writing a survey paper and developing a benchmark. 
- 🤝🤝🤝 We warmly invite everyone to join this collaborative project. Please feel free to reach out to us or submit pull requests—your contributions are highly valued!

  
