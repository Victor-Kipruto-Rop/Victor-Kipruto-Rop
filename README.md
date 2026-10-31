<div align="center">

# Victor Kipruto Rop

<a href="https://victorkipruto.com">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1400&color=0E75B6&center=true&vCenter=true&width=720&height=40&lines=Data+Engineer;FinTech+Infrastructure+Builder;Real-Time+Streaming+%26+Pipeline+Architect" alt="Data Engineer · FinTech Infrastructure Builder · Real-Time Streaming & Pipeline Architect" />
</a>

I design reliable data pipelines, real-time transaction streaming systems, and
lakehouse platforms, with a focus on East African fintech infrastructure.

<p>
  <a href="https://victorkipruto.com"><img src="https://img.shields.io/badge/Website-victorkipruto.com-0E75B6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/victor-kipruto-rop"><img src="https://img.shields.io/badge/LinkedIn-Victor_Kipruto_Rop-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hello@victorkipruto.com"><img src="https://img.shields.io/badge/Email-hello@victorkipruto.com-D14836?style=for-the-badge" alt="Email" /></a>
</p>

<img src="https://komarev.com/ghpvc/?username=Victor-Kipruto-Rop&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views" />

</div>

---

## 👋 About

- 🏗️ I build **batch and streaming pipelines** for transaction data: ingestion, transformation, quality checks, and observability
- 💳 Deep interest in **M-Pesa / Daraja** data: reconciliation, fraud signals, and careful transaction-state handling
- 🧱 I care about systems that are **dependable, observable, and easy to hand over**, built so the next person can understand them

### ✨ Interests

<table>
  <tr>
    <td valign="top" width="50%">
      💸 Fintech &amp; mobile money<br />
      🌍 Technology for Africa<br />
      🧠 Machine learning &amp; AI<br />
      🚀 Building products from scratch
    </td>
    <td valign="top" width="50%">
      ✍️ Writing &amp; sharing what I learn<br />
      🤝 Open source &amp; collaboration<br />
      📚 Continuous learning<br />
      🎬 Film &amp; tech culture
    </td>
  </tr>
</table>

---

## 🧭 How I Build Pipelines

```mermaid
flowchart LR
    A[Sources<br/>M-Pesa · APIs · DBs] --> B[Kafka<br/>event streams]
    B --> C[Flink / Spark<br/>stream + batch]
    C --> D[(Bronze → Silver → Gold<br/>lakehouse)]
    D --> E[dbt<br/>models + tests]
    E --> F[Dashboards & APIs<br/>Streamlit · Grafana]
    G[Airflow<br/>orchestration] -.-> C
    G -.-> E
```

---

## ⚙️ What I Do

| Area | What it looks like in practice |
| :-- | :-- |
| **ETL / ELT** | Reliable workflows for structured and semi-structured data, with batch loading and validation |
| **Real-time streaming** | Event-driven ingestion and processing with Apache Kafka, Flink, and Spark |
| **Modeling & transformation** | Dimensional models, incremental dbt transformations, and data-quality checks |
| **Orchestration** | Airflow DAG design, dependency management, retries, and backfills |
| **Financial data** | Reconciliation-oriented workflows and fraud/anomaly signals on transaction data |
| **Storage & lakehouse** | PostgreSQL, Cassandra, Redis, and Delta Lake |
| **Reliability** | Pipeline metrics, logs, alerts, and data-freshness checks |
| **Platform & DevOps** | Containerized environments, Terraform, Kubernetes, and cloud deployment on AWS |

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td valign="top" width="50%">
      <b>Languages</b><br />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/SQL-CC292B?style=flat-square&logo=sqlite&logoColor=white" alt="SQL" />
      <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
    </td>
    <td valign="top" width="50%">
      <b>Streaming & Orchestration</b><br />
      <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka" />
      <img src="https://img.shields.io/badge/Apache_Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white" alt="Flink" />
      <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark" />
      <img src="https://img.shields.io/badge/Airflow-017CE1?style=flat-square&logo=apache-airflow&logoColor=white" alt="Airflow" />
      <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <b>Databases & Storage</b><br />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white" alt="Cassandra" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      <img src="https://img.shields.io/badge/Delta_Lake-003366?style=flat-square&logoColor=white" alt="Delta Lake" />
    </td>
    <td valign="top" width="50%">
      <b>Analytics & Observability</b><br />
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
      <img src="https://img.shields.io/badge/Metabase-509EE3?style=flat-square&logo=metabase&logoColor=white" alt="Metabase" />
      <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
      <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" alt="Sentry" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <b>Infrastructure & DevOps</b><br />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
      <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
    </td>
    <td valign="top" width="50%">
      <b>Data Quality</b><br />
      <img src="https://img.shields.io/badge/Great_Expectations-FF6B35?style=flat-square&logoColor=white" alt="Great Expectations" />
      <img src="https://img.shields.io/badge/dbt_Tests-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt tests" />
      <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logoColor=white" alt="Pydantic" />
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td valign="top" width="50%">
      <h4><a href="https://github.com/Victor-Kipruto-Rop/TELIXO">TELIXO</a></h4>
      Real-time M-Pesa transaction streaming pipeline: ingest, process, stream, and analyze events end to end.<br /><br />
      <sub><code>Kafka</code> · <code>Spark</code> · <code>PostgreSQL</code> · <code>Docker</code></sub>
    </td>
    <td valign="top" width="50%">
      <h4><a href="https://github.com/Victor-Kipruto-Rop/mpesa_safaricom-fraud_anomaly_detection">M-Pesa Fraud &amp; Anomaly Detection</a></h4>
      Streaming fraud engine with ML risk scoring and explainable signals (velocity, SIM-swap correlation, mule networks) feeding a decision engine.<br /><br />
      <sub><code>Kafka</code> · <code>Flink</code> · <code>dbt</code> · <code>PyTorch</code></sub>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4><a href="https://github.com/Victor-Kipruto-Rop/cloud-etl-pipeline">Cloud ETL Pipeline</a></h4>
      Fault-tolerant batch pipeline that cleans, validates, and loads 1.6M+ records with automated data checks.<br /><br />
      <sub><code>Python</code> · <code>PostgreSQL</code> · <code>Docker</code> · <code>Terraform</code> · <code>AWS</code></sub>
    </td>
    <td valign="top" width="50%">
      <h4><a href="https://github.com/Victor-Kipruto-Rop/knbs-cbk-pipeline">KNBS &amp; CBK Indicators Pipeline</a></h4>
      Ingests public economic indicators, models them with dbt, and serves query and CSV APIs with signed cursor pagination, Redis ETag caching, and rate limiting.<br /><br />
      <sub><code>dbt</code> · <code>PostgreSQL</code> · <code>Redis</code> · <code>Python</code></sub>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4><a href="https://github.com/Victor-Kipruto-Rop/aws-streaming-fraud-detection">AWS Streaming Fraud Detection</a></h4>
      Real-time transaction monitoring with rule-based anomaly scoring, runnable locally or on AWS.<br /><br />
      <sub><code>Python</code> · <code>S3</code> · <code>Kinesis</code></sub>
    </td>
    <td valign="top" width="50%">
      <h4><a href="https://github.com/Victor-Kipruto-Rop/victor-kipruto-rop-portfolio">Data Engineering Portfolio</a></h4>
      ETL, streaming, fraud detection, and financial analytics across Kenyan fintech and banking data, with live dashboards.<br /><br />
      <sub><code>Python</code> · <code>Spark</code> · <code>Streamlit</code> · <code>Grafana</code></sub>
    </td>
  </tr>
</table>

<div align="center">
  <a href="https://github.com/Victor-Kipruto-Rop?tab=repositories">👉 Browse all repositories</a>
</div>

---

## 📊 GitHub Activity

<div align="center">

<a href="https://github.com/Victor-Kipruto-Rop">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Victor-Kipruto-Rop&show_icons=true&include_all_commits=true&count_private=true&rank_icon=github&theme=tokyonight&hide_border=true&cache_seconds=86400" />
    <img src="https://github-readme-stats.vercel.app/api?username=Victor-Kipruto-Rop&show_icons=true&include_all_commits=true&count_private=true&rank_icon=github&theme=default&hide_border=true&cache_seconds=86400" alt="GitHub stats" height="170" />
  </picture>
</a>

<br /><br />

<a href="https://github.com/Victor-Kipruto-Rop">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=Victor-Kipruto-Rop&theme=tokyonight&hide_border=true" />
    <img src="https://streak-stats.demolab.com/?user=Victor-Kipruto-Rop&hide_border=true" alt="GitHub streak" width="85%" />
  </picture>
</a>

</div>

---

<div align="center">

### 📬 Let's connect

Have a pipeline problem, a collaboration idea, or an opportunity? Reach out.

<a href="mailto:hello@victorkipruto.com">hello@victorkipruto.com</a> ·
<a href="https://victorkipruto.com">victorkipruto.com</a> ·
<a href="https://www.linkedin.com/in/victor-kipruto-rop">LinkedIn</a>

</div>
