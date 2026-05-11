<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1b2838,100:0d2137&height=180&section=header&text=Soutrik%20Mukherjee&fontSize=54&fontColor=58a6ff&fontAlignY=38&desc=ML%20Systems%20%C2%B7%20GPU%20Inference%20%C2%B7%20LLM%20Evaluation&descSize=18&descAlignY=62&descColor=8b949e&animation=fadeIn" width="100%"/>

<br/>

**I build and benchmark ML systems.**
GPU inference performance · adversarial LLM evaluation · retrieval infrastructure

<br/>

<a href="https://www.soutrikm.com/"><img src="https://img.shields.io/badge/Portfolio-soutrikm.com-58a6ff?style=flat-square&labelColor=0d1117"/></a>
<a href="https://linkedin.com/in/soutrik-mukherjee"><img src="https://img.shields.io/badge/LinkedIn-soutrik--mukherjee-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0d1117"/></a>
<a href="mailto:soutrik.viratech@gmail.com"><img src="https://img.shields.io/badge/Email-soutrik.viratech-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0d1117"/></a>
<a href="https://doi.org/10.48550/arXiv.2603.28708"><img src="https://img.shields.io/badge/arXiv-2603.28708-b31b1b?style=flat-square&logo=arxiv&logoColor=white&labelColor=0d1117"/></a>
<img src="https://img.shields.io/badge/📍-Philadelphia,_PA-8b949e?style=flat-square&labelColor=0d1117"/>

</div>

---

## `> whoami`

```
ML systems engineer with a physics/mechanical foundation.
I care about inference latency, eval rigor, and the layer where
models meet hardware.

  research → production : I optimize the path between them
  built → benchmarked   : I measure before I ship
  metric over vibe      : numbers in every claim below
```

---

## ⚡ Currently

> **AI Fellow @ Handshake AI** — Designing adversarial benchmarks (Project Helix, Project Axis): golden solutions, fail-to-pass test pipelines, and hard reasoning questions that systematically expose frontier model failure modes across code generation and reasoning domains.

> **Recent**: Published [arXiv:2603.28708](https://doi.org/10.48550/arXiv.2603.28708) — GPU-accelerated transformer inference with TensorRT achieving **64.4× CPU speedup**, **<10ms latency**, **63% memory reduction** across 360+ configurations.

> **Open to**: ML Engineer · Inference Optimization · Model Evaluation · Applied ML Research

---

## 🛠 What I Actually Work On

```
   ┌──────────────────────────────────────────────────────────────────────┐
   │                                                                      │
   │   MODELS                  INFERENCE                EVALUATION        │
   │   ──────                  ─────────                ──────────        │
   │   PyTorch ┐               TensorRT ┐               LLM-as-Judge ┐    │
   │   HF      ├──train──▶     FP16/32  ├──serve──▶     Adversarial  ├──▶ │
   │   CANINE  ┘               CUDA     │               Fail-to-pass ┘    │
   │                           Kernels  ┘               Golden tests     │
   │                                                                      │
   │   RETRIEVAL               DISTRIBUTED              INSTRUMENTATION   │
   │   ─────────               ───────────              ───────────────   │
   │   FAISS ┐                 Ray      ┐               Latency profile ┐ │
   │   RAG   ├──ground──▶      Spark    ├──scale──▶     Memory tracing  ┤ │
   │   Embed ┘                 K8s/Docker┘              Throughput SLOs ┘ │
   │                                                                      │
   └──────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🔥 GPU-Accelerated Transformer Inference
**`arXiv:2603.28708`** · *First author*

TensorRT-optimized BERT-base & GPT-2 with FP16/FP32 hybrid precision on RTX 3090. Systematic sweep over 360+ configurations to find the latency/memory Pareto frontier.

```
64.4×    CPU speedup
<10ms    end-to-end latency
63%      memory reduction
360+     benchmarked configs
```

`TensorRT` `CUDA` `PyTorch` `Mixed-Precision`

</td>
<td width="50%" valign="top">

### 🎯 Adversarial LLM Evaluation
**Handshake AI · Project Helix + Axis**

Building benchmarks that surface model failure modes. Golden solutions, fail-to-pass test suites, and hard reasoning questions derived from recent arXiv papers — designed to stump frontier models.

```
Pipeline: arXiv → QC → adversarial
         question design → eval

Output:  training-quality eval data
         + escalated invalid tasks
```

`LLM Eval` `Benchmark Design` `Code Gen` `Reasoning`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📚 Multi-Agent RAG Pipeline
**BlueRidge Compliance Partners**

LangChain-orchestrated retrieval over compliance corpus. FAISS vector search + semantic chunking + retrieval reranking. Scaled with Ray-distributed embeddings, CUDA-accelerated indexing.

```
95%    recall on regulatory queries
70%    end-to-end latency reduction
1000s  of documents ingested
```

`LangChain` `FAISS` `Ray` `AWS` `RAG`

</td>
<td width="50%" valign="top">

### 🤖 LLM → Robot Manipulation
**Harrisburg University · MS Thesis**

Multi-modal pipeline integrating camera streams with ROS 2 manipulation. DeepSeek R1 grounds natural language commands into closed-loop manipulator actions.

```
92%    instruction-following accuracy
<1s    end-to-end inference latency
50     test cases evaluated
```

`DeepSeek R1` `ROS 2` `Multi-modal` `VLM`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Distributed Sensor Processing
**UPenn GRASP Lab**

Multi-sensor data pipeline integrating C++ solver outputs with high-frequency streams. Spark + Ray distribution, CUDA parallelization, Docker + Kubernetes on GCP.

```
3.4×       throughput speedup
40%        memory reduction
85%        lower latency
10,000+    GPU-hours saved annually
```

`Spark` `Ray` `CUDA` `K8s` `GCP`

</td>
<td width="50%" valign="top">

### 🧠 Character-Level LLM Self-Play
**Harrisburg University**

Pre-trained Google's CANINE on 380k-word corpus with Biased Random Sampling. Self-play fine-tuning loop surpassed human-level performance on the target task.

```
56%    base accuracy (human-level)
63%    self-play fine-tuned (6 guesses)
87%    self-play fine-tuned (10 guesses)
```

`CANINE` `Self-Play` `RL Fine-tuning` `HF`

</td>
</tr>
</table>

---

## 🧱 Stack

#### Core
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

#### ML / Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

#### Inference & GPU Performance
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Mixed Precision](https://img.shields.io/badge/Mixed_Precision-FP16%2FFP32-2C3E50?style=flat-square)
![NVIDIA](https://img.shields.io/badge/RTX_3090_%2F_A100-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Intel MKL](https://img.shields.io/badge/Intel_MKL-0071C5?style=flat-square&logo=intel&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-183A61?style=flat-square)

#### LLM Infrastructure
![LangChain](https://img.shields.io/badge/🦜_LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-58a6ff?style=flat-square)
![Eval](https://img.shields.io/badge/LLM--as--Judge-purple?style=flat-square)

#### Distributed Systems
![Ray](https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

#### Robotics & Perception *(secondary stack)*
![ROS2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-orange?style=flat-square)

---

## 📊 GitHub Pulse

<div align="center">

<a href="https://github.com/SoutrikMukherjee">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SoutrikMukherjee&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SoutrikMukherjee&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&langs_count=8" />
</a>

</div>

---

## 📄 Publications

| | Title | Venue | Domain |
|---|---|---|---|
| **1** | **GPU-Accelerated Optimization of Transformer-Based Neural Networks for Real-Time Inference** | [arXiv:2603.28708](https://doi.org/10.48550/arXiv.2603.28708) | `ML Systems` `GPU` `TensorRT` |
| 2 | Structural Optimization Using Topology Optimization (CNN-driven generative design) | [IJRTE](https://doi.org/10.35940/ijrte.F7462.0712223) | `Deep Learning` `Computational Design` |
| 3 | Bi-Directional Drone Path Planning for Agriculture | [IJRTE](https://doi.org/10.35940/ijrte.B6393.0910321) | `Robotics` `Path Planning` |
| 4 | Automatic Rotating System for Industrial De-scaling | [IJRTE](https://doi.org/10.35940/ijrte.B6395.0910321) | `Systems Design` |

---

## 🎓 Background

<table>
<tr>
<td width="34%" align="center">

**Harrisburg University**  
MS Computer Science  
*Scientific Computing*

`3.7 / 4.0` · `Mar 2024 – Feb 2026`  
🏆 Best Master's Thesis Award

</td>
<td width="33%" align="center">

**UPenn**  
MS Mechanical Engineering  
*Robotics & Intelligent Systems*

`Aug 2022 – Jan 2024`  
GRASP Lab

</td>
<td width="33%" align="center">

**NIT Rourkela**  
BTech Industrial Design  
*Minor: Mechanical Engineering*

`9.09 / 10` · 🥇 #1 of 120  
`Jun 2018 – May 2022`

</td>
</tr>
</table>

<sub>The mechanical engineering foundation isn't filler — it's why I think about ML systems as physical systems with latency budgets, memory hierarchies, and thermal envelopes, not abstract graphs.</sub>

---

## 🤝 Beyond the Code

**MANAV** — founded 2019. Teaching math, engineering, and technology to 200+ students across 12+ government schools in India. Bridging what industry needs vs. what school teaches.

---

<div align="center">

### Let's build inference systems that ship.

<a href="mailto:soutrik.viratech@gmail.com">
  <img src="https://img.shields.io/badge/📬_Reach_out-soutrik.viratech@gmail.com-58a6ff?style=for-the-badge&labelColor=0d1117" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=SoutrikMukherjee&color=58a6ff&style=flat-square&label=Profile+Views" />

<br/>

<sub><i>"Measure before you ship. The number is the argument."</i></sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1b2838,100:0d2137&height=100&section=footer" width="100%"/>
