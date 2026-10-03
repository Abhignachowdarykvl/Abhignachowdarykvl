# Hi, I'm Abhigna Chowdary 👋

**Data Engineer | AI Data Pipelines | Analytics Engineering**

I build end-to-end data pipelines and AI-powered data systems — from API ingestion and cloud warehousing to RAG pipelines with vector databases.

---

## 🛠 Tech Stack

**Languages & Querying**
`Python` `SQL` `Bash`

**Data Engineering**
`dbt` `Apache Airflow` `Docker` `GitHub Actions`

**Databases & Storage**
`PostgreSQL` `pgvector` `Google BigQuery` `AWS S3` `ChromaDB`

**AI & ML**
`RAG Pipelines` `sentence-transformers` `pgvector` `FastAPI` `Anthropic Claude API`

**Visualization**
`Tableau` `Power BI`

---

## 🚀 Projects

### 🏥 [Hospital Pricing & Quality Warehouse](https://github.com/Abhignachowdarykvl/hospital-pricing-warehouse)
End-to-end healthcare data pipeline: CMS Medicare API → AWS S3 → PostgreSQL → dbt → Tableau

- 145,000+ rows ingested from the CMS API with pagination and retry logic
- Star schema with SCD Type 2, 21/21 dbt tests passing
- Orchestrated with Apache Airflow, CI/CD with GitHub Actions
- **Finding:** CAR T-Cell procedures show a $6.8M national price spread

🔗 [Live Dashboard](https://public.tableau.com/app/profile/abhigna.chowdary/viz/HospitalPricingQualityAnalysis/HospitalPricingQualityAnalysis)

---

### 📊 [Product & Funnel Analytics](https://github.com/Abhignachowdarykvl/product-funnel-analytics)
GA4 e-commerce event pipeline: BigQuery → dbt → funnel, retention & attribution → Tableau

- Sessionized raw clickstream events using window functions and UNNEST
- Built conversion funnels, weekly retention cohorts, and first-touch attribution
- 241,752 sessions analyzed, 1.54% overall conversion rate
- **Finding:** Google Organic drove $83,033 in revenue; desktop converts best

🔗 [Live Dashboard](https://public.tableau.com/app/profile/abhigna.chowdary/viz/ProductFunnelAnalytics/Dashboard1)

---

### 🤖 [Earnings Call RAG Knowledge Base](https://github.com/Abhignachowdarykvl/sec-rag-knowledge-base)
AI Data Engineering pipeline: earnings call transcripts → embeddings → pgvector + Chroma → FastAPI Q&A

- 35 transcripts across Apple, Microsoft, Google, Amazon, Meta, NVIDIA, TSMC
- 800-token chunking with section metadata, dual vector store (pgvector + Chroma)
- FastAPI Q&A endpoint with citations and LLM-as-judge evaluation harness
- **Result:** 92% retrieval hit rate, 0.82 faithfulness score across 25 questions

---

## 📈 GitHub Stats

![Abhigna's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Abhignachowdarykvl&show_icons=true&theme=default&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Abhignachowdarykvl&layout=compact&theme=default&hide_border=true)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abhigna_Chowdary-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/abhigna-chowdary-564148290/)
[![Tableau](https://img.shields.io/badge/Tableau-Public_Profile-orange?style=flat&logo=tableau)](https://public.tableau.com/app/profile/abhigna.chowdary)

---

*Open to Data Engineer, Analytics Engineer, and AI Data Engineer roles.*
