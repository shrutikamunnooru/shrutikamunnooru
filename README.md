<!--
  ┌────────────────────────────────────────────────────────────────────┐
  │  HOW TO USE THIS FILE                                               │
  │  1. Create a new PUBLIC repo named exactly: shrutikamunnooru        │
  │     (same as your username — this is what makes it your profile)    │
  │  2. Add a file named README.md                                     │
  │  3. Paste everything BELOW this comment block into it              │
  │  4. Delete this comment block, then commit                        │
  │  (All details are pre-filled from your resume — just review.)      │
  └────────────────────────────────────────────────────────────────────┘
-->

<h1 align="center">Hi, I'm Shrutika 👋</h1>

<p align="center">
  <b>Data Engineer · 4+ years</b> · Building cloud lakehouses, streaming systems, and GenAI data pipelines on <b>AWS</b> &amp; <b>Azure</b>.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shrutika-munnooru"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:munnoorushrutika@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/📍_Seattle,_WA-informational?style=flat" alt="Location"/>
</p>

---

### About me

I'm a Data Engineer with 4+ years building end-to-end data platforms — cloud lakehouses, event-driven and streaming systems, and legacy migrations at enterprise scale. Currently at **ArcBest Technologies** in Seattle, where I've cut a critical pipeline's runtime by 94%, led a 10TB+ DB2/SQL Server migration to Azure Synapse, and shipped near-real-time ingestion from 150+ logistics stations. I care about clean architecture, infrastructure automation, and pipelines that hold up in production — not just in a demo.

The repositories below are hands-on builds deployed on real AWS infrastructure, each with full architecture write-ups.
- 🎓 M.S. Information Systems, University of Utah (GPA 3.8)
- 📜 **Azure Data Engineer Associate (DP-203)** · Tableau Desktop Specialist

---

### 🧰 Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Data Processing**
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Iceberg](https://img.shields.io/badge/Apache_Iceberg-1D9BF0?style=flat&logo=apacheiceberg&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)

**Orchestration & ETL**
![Airflow](https://img.shields.io/badge/Airflow_(MWAA)-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Step Functions](https://img.shields.io/badge/Step_Functions-FF4F8B?style=flat&logo=amazonaws&logoColor=white)
![ADF](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Cloud — AWS**
![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazons3&logoColor=white)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat&logo=amazonredshift&logoColor=white)
![Glue](https://img.shields.io/badge/Glue-8C4FFF?style=flat&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![Kinesis](https://img.shields.io/badge/Kinesis-FF9900?style=flat&logo=amazonaws&logoColor=white)
![EMR](https://img.shields.io/badge/EMR_Serverless-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Athena](https://img.shields.io/badge/Athena-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Bedrock](https://img.shields.io/badge/Bedrock-232F3E?style=flat&logo=amazonaws&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat&logo=amazonaws&logoColor=white)

**Cloud — Azure**
![Synapse](https://img.shields.io/badge/Synapse-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![ADLS](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Functions](https://img.shields.io/badge/Azure_Functions-0062AD?style=flat&logo=azurefunctions&logoColor=white)
![Entra](https://img.shields.io/badge/Entra_ID-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**BI & Tooling**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)

---

### 🚀 Featured Projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[Bedrock Retail Support Intelligence](https://github.com/shrutikamunnooru/bedrock-retail-support-intelligence-pipeline)** | An AWS-native GenAI pipeline that turns unstructured support tickets into analytics-ready data using Amazon Bedrock (enrichment, embeddings, similarity) across a medallion architecture, orchestrated end-to-end by Step Functions. | Bedrock · Glue · Lambda · Athena · Step Functions |
| **[Real-Time Bookings & Payments Pipeline](https://github.com/shrutikamunnooru/aws-realtime-pipeline-bookings-and-payment)** | Near real-time stream-stream join of booking & payment events with event-time watermarks, DLQ handling, and a Redshift analytics warehouse — fully provisioned via CloudFormation. | Kinesis · Glue Streaming · Spark · Redshift · SQS |
| **[S3 → Lambda Order Reporting](https://github.com/shrutikamunnooru/s3-lambda-order-reporting)** | Serverless order-reporting pipeline: an S3 upload triggers a Lambda that transforms order data and writes reports back to S3. | Lambda · S3 · Python |

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shrutikamunnooru&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shrutikamunnooru&layout=compact&hide_border=true" alt="Top languages" height="160"/>
</p>

<!-- These cards are served by a free third-party service (github-readme-stats) and need no setup. Delete this section if you'd rather not use a third-party image. -->

---

<p align="center"><i>Always happy to talk data pipelines, cloud architecture, or a good debugging war story.</i></p>
