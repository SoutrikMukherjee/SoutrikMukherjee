<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,35:0e2a47,70:134e4a,100:0d2137&height=190&section=header&text=Soutrik%20Mukherjee&fontSize=54&fontColor=58a6ff&fontAlignY=36&desc=Data%20Engineering%20%C2%B7%20Machine%20Learning%20%C2%B7%20Analytics&descSize=18&descAlignY=60&descColor=8b949e&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=720&lines=raw+data+%E2%86%92+pipelines+%E2%86%92+models+%E2%86%92+decisions;Airflow+%C2%B7+dbt+%C2%B7+Snowflake+%C2%B7+Spark+%C2%B7+PyTorch;I+measure+before+I+ship.+The+number+is+the+argument." />

<br/>

**I build the full data lifecycle — ingestion to insight to inference.**

<br/>

<a href="https://www.soutrikm.com/"><img src="https://img.shields.io/badge/Portfolio-soutrikm.com-58a6ff?style=flat-square&labelColor=0d1117"/></a>
<a href="https://linkedin.com/in/soutrik-mukherjee"><img src="https://img.shields.io/badge/LinkedIn-soutrik--mukherjee-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0d1117"/></a>
<a href="mailto:soutrik.viratech@gmail.com"><img src="https://img.shields.io/badge/Email-soutrik.viratech-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0d1117"/></a>
<a href="https://doi.org/10.48550/arXiv.2603.28708"><img src="https://img.shields.io/badge/arXiv-2603.28708-b31b1b?style=flat-square&logo=arxiv&logoColor=white&labelColor=0d1117"/></a>
<img src="https://img.shields.io/badge/📍-Philadelphia,_PA-8b949e?style=flat-square&labelColor=0d1117"/>

</div>

---

## `> whoami`

```text
Data + ML engineer with a physics/mechanical foundation.

  ingest → model → serve   :  I own every stage of the pipeline
  schema over chaos        :  tested tables, documented models, data contracts
  metric over vibe         :  numbers in every claim below

Open to: Data Engineer · Data Scientist · Data Analyst · ML Engineer
```

---

## 🔄 How I Think About Data

```mermaid
flowchart LR
    subgraph INGEST["📥 INGEST"]
        A1[Kafka / Pub-Sub]
        A2[Airbyte / APIs]
        A3[Batch files]
    end
    subgraph TRANSFORM["⚙️ TRANSFORM"]
        B1[Spark / Ray]
        B2[dbt models<br/>tested + documented]
    end
    subgraph STORE["🗄️ WAREHOUSE"]
        C1[(Snowflake)]
        C2[(BigQuery)]
    end
    subgraph SERVE["📊 SERVE"]
        D1[Dashboards / EDA]
        D2[ML training]
        D3[Real-time inference<br/>TensorRT &lt;10ms]
    end
    A1 --> B1
    A2 --> B1
    A3 --> B1
    B1 --> B2
    B2 --> C1
    B2 --> C2
    C1 --> D1
    C1 --> D2
    C2 --> D2
    D2 --> D3
    style INGEST fill:#0d1117,stroke:#58a6ff
    style TRANSFORM fill:#0d1117,stroke:#3fb950
    style STORE fill:#0d1117,stroke:#d29922
    style SERVE fill:#0d1117,stroke:#bc8cff
```

```text
   ORCHESTRATION ──────  Airflow · Dagster · Cloud Composer  ──────  (the conductor)
   QUALITY GATES ──────  dbt tests · schema contracts · CI   ──────  (the bouncer)
   OBSERVABILITY ──────  latency profiles · SLOs · lineage   ──────  (the witness)
```

---

## ⚡ Currently

> **AI Fellow @ Handshake AI** — Designing adversarial benchmarks (Project Helix, Project Axis): golden solutions, fail-to-pass test pipelines, and reasoning evals that systematically expose frontier-model failure modes. Eval design is data engineering — sampling, labeling pipelines, and quality control at scale.

> **Recent**: Published [arXiv:2603.28708](https://doi.org/10.48550/arXiv.2603.28708) — GPU-accelerated transformer inference: **64.4× CPU speedup**, **<10ms latency**, **63% memory reduction** across **360+ benchmarked configurations**.

---

## 🚀 Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🛠️ Compliance ETL Platform
**BlueRidge Compliance Partners · Data Engineering**

Scheduled batch pipeline reconciling thousands of compliance documents per run against client databases.

```text
flow:    docs ──▶ Airflow DAGs ──▶ dbt
         (staging → marts, fully tested)
         ──▶ Snowflake ──▶ analysts

wins:    schema contracts at every layer
         tested, documented, idempotent
```

`Airflow` `dbt` `Snowflake` `SQL` `Python`

</td>
<td width="50%" valign="top">

### 📚 Multi-Agent RAG Pipeline
**BlueRidge · Retrieval Infrastructure**

LangChain-orchestrated retrieval over compliance corpus: FAISS vector search, semantic chunking, reranking, Ray-distributed embeddings.

```text
95%     recall on regulatory queries
70%     end-to-end latency reduction
1000s   of documents ingested
```

`LangChain` `FAISS` `Ray` `AWS` `RAG`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Distributed Sensor Pipeline
**UPenn GRASP Lab · Big Data Processing**

Multi-sensor pipeline fusing C++ solver outputs with high-frequency streams. Spark + Ray distribution, CUDA parallelization, Docker + K8s on GCP. Plus scikit-learn predictive models for an autonomous excavator.

```text
3.4×      throughput speedup
40%       memory reduction
85%       lower latency
10,000+   GPU-hours saved / year
```

`Spark` `Ray` `CUDA` `K8s` `GCP` `scikit-learn`

</td>
<td width="50%" valign="top">

### 🔥 GPU-Accelerated Inference
**arXiv:2603.28708 · First Author**

TensorRT-optimized BERT-base & GPT-2, FP16/FP32 hybrid precision. Systematic sweep to find the latency/memory Pareto frontier — a 360-point experiment, analyzed like a dataset.

```text
64.4×    CPU speedup
<10ms    end-to-end latency
63%      memory reduction
360+     configs benchmarked
```

`TensorRT` `CUDA` `PyTorch` `Mixed-Precision`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎯 Adversarial LLM Evaluation
**Handshake AI · Projects Helix + Axis**

Benchmarks that surface model failure modes: golden solutions, fail-to-pass test suites, rubric-based pairwise scoring — labeled-data pipelines with QC at every stage.

```text
pipeline:  arXiv → QC → adversarial
           question design → eval
output:    training-quality eval data
```

`LLM Eval` `Benchmark Design` `Docker` `CI`

</td>
<td width="50%" valign="top">

### 🧠 Character-Level LLM Self-Play
**Harrisburg University · Applied DS**

Pre-trained Google's CANINE on a 380k-word corpus with Biased Random Sampling; self-play fine-tuning loop beat human-level performance.

```text
56%    base accuracy (≈ human)
63%    self-play (6 guesses)
87%    self-play (10 guesses)
```

`CANINE` `Self-Play` `RL Fine-tuning` `HF`

</td>
</tr>
</table>

---

## 📐 The Stack, As a Pipeline

```text
 ┌─────────────┐   ┌──────────────┐   ┌──────────────┐   ┌──────────────┐   ┌─────────────┐
 │   SOURCES   │   │   INGEST     │   │  TRANSFORM   │   │  WAREHOUSE   │   │   CONSUME   │
 │             │──▶│ Kafka        │──▶│ Spark · Ray  │──▶│ Snowflake    │──▶│ EDA · Viz   │
 │ APIs · logs │   │ Airbyte      │   │ dbt (tested) │   │ BigQuery     │   │ ML training │
 │ docs · IoT  │   │ Pub/Sub      │   │ Pandas/NumPy │   │ Postgres     │   │ TensorRT    │
 └─────────────┘   └──────────────┘   └──────────────┘   └──────────────┘   └─────────────┘
        ▲                  ▲                  ▲                  ▲                  ▲
        └──────────────────┴────────── Airflow · Dagster ───────┴──────────────────┘
                              Docker · K8s · CI/CD · GCP · AWS
```

#### Languages & Querying
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

#### Data Engineering
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Dagster](https://img.shields.io/badge/Dagster-654FF0?style=flat-square)
![Airbyte](https://img.shields.io/badge/Airbyte-615EFF?style=flat-square)

#### Data Science & Analytics
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Statistics](https://img.shields.io/badge/Stats_&_A%2FB-Hypothesis_Testing-2C3E50?style=flat-square)

#### ML & LLM Systems
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=flat-square)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![LangChain](https://img.shields.io/badge/🦜_LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

#### Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Ray](https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

---

## 📊 GitHub Pulse

<div align="center">

<a href="https://github.com/SoutrikMukherjee">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SoutrikMukherjee&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SoutrikMukherjee&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&langs_count=8" />
</a>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SoutrikMukherjee&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=58a6ff&line=3fb950&point=bc8cff&area=true&area_color=134e4a" width="95%"/>

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

<sub>The mechanical engineering foundation isn't filler — pipelines are physical systems with throughput limits, backpressure, and failure modes. I treat data infrastructure the same way.</sub>

---

## 🤝 Beyond the Code

**MANAV** — founded 2019. Teaching math, engineering, and technology to 200+ students across 12+ government schools in India. Bridging what industry needs vs. what school teaches.

---

<div align="center">

### Let's build pipelines that don't break and models that ship.

<a href="mailto:soutrik.viratech@gmail.com">
  <img src="https://img.shields.io/badge/📬_Reach_out-soutrik.viratech@gmail.com-58a6ff?style=for-the-badge&labelColor=0d1117" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=SoutrikMukherjee&color=58a6ff&style=flat-square&label=Profile+Views" />

<br/>

<sub><i>"Measure before you ship. The number is the argument."</i></sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,40:134e4a,100:0d2137&height=100&section=footer" width="100%"/>
