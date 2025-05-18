# ☁️ Google Cloud Platform (GCP) Learning Roadmap for Software & AI Engineers

Lộ trình học GCP trong **4 tuần** – dành cho Software Engineers, Backend Developers, AI/NLP Engineers muốn triển khai ứng dụng, sử dụng ML services, và hiểu rõ hạ tầng cloud hiện đại.

---

## 📅 Weekly Breakdown

### ✅ Tuần 1: GCP Fundamentals + gcloud CLI

**Nội dung:**
- Làm quen với GCP Console
- Projects, Billing Accounts
- Identity & Access Management (IAM)
- Service Accounts & Role Permissions
- Cài đặt và sử dụng `gcloud CLI`

**Thực hành:**
- Tạo Project mới trên GCP
- Bật API cần thiết
- Tạo Cloud Storage Bucket và thử thao tác với `gsutil`

---

### ✅ Tuần 2: Deploy App + Cloud Storage

**Nội dung:**
- Giới thiệu Cloud Run (serverless container)
- App Engine: chạy web app không cần quản lý server
- Cloud Storage: lưu trữ file, ảnh, checkpoints ML

**Thực hành:**
- Deploy một app Python (Flask/FastAPI) lên Cloud Run
- Upload & truy xuất file từ Cloud Storage
- So sánh Cloud Run vs App Engine

---

### ✅ Tuần 3: Databases + BigQuery

**Nội dung:**
- Cloud SQL (MySQL/PostgreSQL managed)
- Firestore: NoSQL cho web/mobile app
- BigQuery: phân tích dữ liệu lớn bằng SQL

**Thực hành:**
- Tạo Cloud SQL instance và kết nối từ Python app
- Tạo Firestore collection, thực hiện CRUD
- Dùng BigQuery để query file CSV hoặc JSON lớn

---

### ✅ Tuần 4: AI, CI/CD, Monitoring & Security

**Nội dung:**
- Vertex AI: dùng pretrained NLP model (Text Classification, Sentiment)
- Cloud Build: tạo pipeline CI/CD deploy từ GitHub
- Cloud Logging & Monitoring
- Bảo mật: IAM Roles, tránh lộ API Key, quản lý quyền truy cập

**Thực hành:**
- Deploy mô hình NLP lên Vertex AI
- Build CI/CD pipeline cho app Python
- Xem logs, tạo alert với Cloud Monitoring
- Audit quyền và service account access

---

## 🔧 Công cụ & Tài nguyên khuyên dùng:

- [Google Cloud Skills Boost (Qwiklabs)](https://www.cloudskillsboost.google/) – học thực chiến miễn phí
- [Coursera: GCP Fundamentals](https://www.coursera.org/learn/gcp-fundamentals)
- [gcloud CLI docs](https://cloud.google.com/sdk/gcloud)
- [Cloud Run Quickstart](https://cloud.google.com/run/docs/quickstarts)
- [Vertex AI NLP Demo](https://cloud.google.com/vertex-ai/docs/nlp)

---

## 🧠 Gợi ý mini project

> Tạo 1 Python web app (Flask hoặc FastAPI) có:
> - Giao diện upload file (Cloud Storage)
> - Lưu metadata vào Firestore
> - Phân tích nội dung văn bản bằng Vertex AI NLP
> - Triển khai bằng Cloud Run và CI/CD với Cloud Build

---

## 👨‍💻 Tác giả

**Long** – AI/NLP Engineer | Passionate about Cloud, MLOps & Open Source  
_“Deploy less, automate more, think bigger.”_ 🚀

---

