<!-- ══════════════════════════════════════════════════════════════════
     MANSI BHADANI — GitHub Profile README
     Copy everything below and paste into mansibhadani/mansibhadani/README.md
     ══════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- Animated header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Mansi%20Bhadani&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Engineer%20%7C%20ML%20Pipelines%20%7C%20Real-Time%20Systems&descAlignY=60&descSize=18" width="100%"/>

<!-- Typing animation -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+data+infrastructure+at+scale+%F0%9F%9A%80;Kafka+%E2%86%92+Spark+%E2%86%92+Redis+%E2%86%92+ML+Inference;Feature+Stores+%7C+Streaming+Pipelines+%7C+Cloud;Turning+raw+events+into+intelligent+decisions)](https://git.io/typing-svg)

<br/>

<!-- Social badges row -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mansi-bhadani)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mansibhadani)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://mansibhadani.github.io/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mansi.bhadani31@gmail.com)

<br/>

<!-- Profile views + followers -->
![Profile Views](https://komarev.com/ghpvc/?username=mansibhadani&label=Profile%20Views&color=58a6ff&style=flat-square)
&nbsp;&nbsp;
![GitHub followers](https://img.shields.io/github/followers/mansibhadani?label=Followers&style=flat-square&color=58a6ff)

</div>

---

## 🧠 About Me

```python
class MansiB:
    role        = "Data Engineer | MS Computer Science @ Pace University (GPA 3.82)"
    location    = "New York, NY 🗽"
    currently   = "Building production ML feature stores & streaming pipelines"
    interests   = ["Feature Stores", "Real-Time ML", "Search Ranking", "LLM Infra"]
    open_to     = ["Data Engineering", "ML Infra", "Senior DE roles (NYC / Remote)"]

    def what_i_build(self):
        return [
            "🔴 Online feature stores (Redis + SageMaker) with <2ms p99 latency",
            "🟡 Kafka + Spark Streaming near-line pipelines at millions of events/day",
            "🟢 Offline ETL jobs processing 10TB+ datasets with Iceberg + Parquet",
            "🔵 Semantic search engines using Faiss HNSW vector indexes",
            "⚡ End-to-end ML pipelines from raw events → model inference",
        ]
```

---

## ⚡ Tech Stack

<div align="center">

### 🔥 Core Data Engineering
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)

### 🏪 Feature Stores & ML Infra
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![AWS SageMaker](https://img.shields.io/badge/AWS%20SageMaker-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Faiss](https://img.shields.io/badge/Faiss-4267B2?style=for-the-badge&logo=meta&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)

### ☁️ Cloud & Warehouses
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazonaws&logoColor=white)

### 🔧 Orchestration & DevOps
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great%20Expectations-FF6C37?style=for-the-badge&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 🏪 [Real-Time ML Feature Store](https://github.com/mansibhadani/real-time-ml-feature-store)
> Production-pattern online feature store powering ML inference at sub-millisecond latency

```
Stack: Redis • FastAPI • Apache Spark • Apache Kafka • Docker
```
- **Offline pipeline**: Spark batch ETL → user/content feature aggregation → Parquet offline store
- **Near-line pipeline**: Kafka consumer → incremental Redis updates (atomic HINCRBY)
- **Online serving**: FastAPI SDK with TTL-based expiry, namespace isolation, point-in-time joins
- **Integrated**: ML inference endpoint returning relevance scores in <2ms

[![Redis](https://img.shields.io/badge/Redis-Online%20Store-DC382D?style=flat-square&logo=redis)](https://github.com/mansibhadani/real-time-ml-feature-store)
[![Spark](https://img.shields.io/badge/Spark-Offline%20ETL-E25A1C?style=flat-square&logo=apachespark)](https://github.com/mansibhadani/real-time-ml-feature-store)
[![Kafka](https://img.shields.io/badge/Kafka-Near--Line-231F20?style=flat-square&logo=apachekafka)](https://github.com/mansibhadani/real-time-ml-feature-store)

---

### 🔍 [Semantic Content Search — Faiss](https://github.com/mansibhadani/semantic-content-search-faiss)
> Embedding-based semantic retrieval engine using Faiss HNSW vector index

```
Stack: Faiss • Sentence-Transformers • Python • NumPy
```
- **HNSW index**: 99%+ recall with ~2ms query latency on CPU
- **Incremental updates**: Add new content without full index rebuild
- **L2 normalization**: Cosine similarity via inner product for semantic ranking
- Mirrors Disney+/Netflix search retrieval stage architecture

[![Faiss](https://img.shields.io/badge/Faiss-HNSW%20Index-4267B2?style=flat-square)](https://github.com/mansibhadani/semantic-content-search-faiss)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python)](https://github.com/mansibhadani/semantic-content-search-faiss)

---

### 📊 [E-Commerce Real-Time Analytics Platform](https://github.com/mansibhadani/ecommerce-realtime-platform)
> High-throughput streaming analytics pipeline processing millions of events/day

```
Stack: Kafka • PySpark Streaming • Apache Iceberg • Snowflake • dbt
```
- Kafka producer/consumer handling 1M+ daily events with exactly-once semantics
- Iceberg time-travel queries for point-in-time correct training data generation
- dbt transformations with automated data quality checks (Great Expectations)
- 60% storage cost reduction vs Parquet-on-S3 naive approach

[![Kafka](https://img.shields.io/badge/Kafka-Streaming-231F20?style=flat-square&logo=apachekafka)](https://github.com/mansibhadani/ecommerce-realtime-platform)
[![Iceberg](https://img.shields.io/badge/Iceberg-Data%20Lake-29B5E8?style=flat-square)](https://github.com/mansibhadani/ecommerce-realtime-platform)

---

### 🚌 [NJ Transit Smart Monitoring System](https://github.com/mansibhadani/nj-transit-smart-management)
> Real-time transit optimization with predictive ML analytics

```
Stack: Kafka • Spark Streaming • Snowflake • Great Expectations • OpenLineage
```
- Processing millions of transit events/day through Kafka → Spark Streaming → Snowflake
- Predictive delay/congestion forecasting — **30% improvement** in route optimization
- Full data lineage tracking (OpenLineage) with **50% reduction** in anomaly detection time
- Data quality framework achieving **99% accuracy** with automated alerting

[![Stars](https://img.shields.io/github/stars/mansibhadani/nj-transit-smart-management?style=flat-square&color=yellow)](https://github.com/mansibhadani/nj-transit-smart-management)

---

## 📈 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=mansibhadani&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mansibhadani&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff"/>

</div>

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=mansibhadani&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=ff6b6b&currStreakLabel=58a6ff)](https://github.com/mansibhadani)

</div>

---

## 🏆 Experience Highlights

| Company | Role | Impact |
|---------|------|--------|
| **NJ Transit** | Data Engineer | Kafka+Spark pipeline · 30% ops efficiency · 50% faster debugging |
| **Beats by Dre** | Data Analytics Extern | ETL pipelines · NLP feature engineering · cross-functional collab |
| **Techcolabs** | Data Scientist Intern | 92% ML accuracy · 10TB Iceberg migration · 60% cost reduction |
| **Innovative Research Labs** | Data Engineer Intern | 98% faster DB migrations · LLM-powered Airflow automation |

---

## 📊 Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=mansibhadani&theme=github-compact&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&hide_border=true)](https://github.com/mansibhadani)

</div>

---

## 🎯 Currently Building

```bash
$ git log --oneline -5

a3f2c1b  feat: add Kinesis near-line feature updater to feature store
7d8e9f2  perf: optimize Spark partition strategy (35% query speedup)  
c4a1b3e  feat: Faiss HNSW → IVFFlat migration for 10M+ vector scale
9e2d7f1  docs: add architecture diagram for offline→online pipeline
2b5c8d4  test: integration tests for Redis TTL expiry + cache invalidation
```

---

## 📫 Let's Connect

<div align="center">

I'm actively looking for **Data Engineering** and **ML Infrastructure** roles at tech companies. If you're building data systems at scale — let's talk.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mansi-bhadani)
[![Email](https://img.shields.io/badge/Send%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mansi.bhadani31@gmail.com)
[![Portfolio](https://img.shields.io/badge/View%20Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://mansibhadani.github.io/)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
