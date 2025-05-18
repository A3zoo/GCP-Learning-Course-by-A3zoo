# ☁️ Google Cloud Platform (GCP) Learning Roadmap for Software & AI Engineers

This is a **4-week roadmap** to help Software Engineers, Backend Developers, and AI/NLP Engineers get hands-on with GCP services — from fundamentals to deploying applications, managing data, and leveraging ML services.

---

## 📅 Weekly Plan

### ✅ Week 1: GCP Fundamentals + gcloud CLI

**Topics:**
- Introduction to GCP Console & Projects
- Billing accounts and quotas
- IAM (Identity & Access Management)
- Service Accounts & Roles
- Install and use `gcloud CLI`

**Hands-on:**
- Create a new GCP Project
- Enable necessary APIs
- Create a Cloud Storage bucket and interact with it using `gsutil`

---

### ✅ Week 2: Deploying Apps + Cloud Storage

**Topics:**
- Cloud Run (serverless containers)
- App Engine (PaaS for Python/web apps)
- Cloud Storage (store files, images, ML checkpoints)

**Hands-on:**
- Deploy a Python (Flask/FastAPI) app to Cloud Run
- Upload & retrieve files using Cloud Storage
- Compare Cloud Run vs App Engine

---

### ✅ Week 3: Databases + BigQuery

**Topics:**
- Cloud SQL (managed MySQL/PostgreSQL)
- Firestore (NoSQL database)
- BigQuery (large-scale analytics with SQL)

**Hands-on:**
- Set up Cloud SQL and connect it to your app
- Perform CRUD operations with Firestore
- Run queries on large CSV/JSON datasets using BigQuery

---

### ✅ Week 4: Vertex AI, CI/CD, Monitoring & Security

**Topics:**
- Vertex AI (use pretrained NLP models)
- Cloud Build (CI/CD pipelines)
- Cloud Monitoring & Logging
- Security basics: IAM roles, service account keys, access control

**Hands-on:**
- Run NLP tasks (e.g., sentiment analysis) with Vertex AI
- Set up CI/CD pipeline with GitHub + Cloud Build
- Explore logging, create alerts and metrics dashboards
- Audit service accounts and apply least-privilege access

---

## 🔧 Recommended Tools & Resources

- [Google Cloud Skills Boost (Qwiklabs)](https://www.cloudskillsboost.google/) – hands-on GCP labs
- [Coursera: Google Cloud Fundamentals](https://www.coursera.org/learn/gcp-fundamentals)
- [gcloud CLI Documentation](https://cloud.google.com/sdk/gcloud)
- [Cloud Run Quickstart](https://cloud.google.com/run/docs/quickstarts)
- [Vertex AI NLP Docs](https://cloud.google.com/vertex-ai/docs/nlp)

---

## 💡 Suggested Final Project

> Build a small Python web app (Flask/FastAPI) that:
> - Lets users upload files (stored in Cloud Storage)
> - Saves file metadata to Firestore
> - Runs text analysis using Vertex AI NLP
> - Is deployed with Cloud Run and auto-deployed via Cloud Build

---

## 👨‍💻 Author

**Duy** – SE/NLP Engineer | Passionate about Cloud, MLOps & Open Source  
_“Deploy less, automate more, think bigger.”_ 🚀

---

