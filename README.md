# MLOps & Production Engineering

This repository covers the complete end-to-end lifecycle of machine learning models — from training and tracking to deployment, monitoring, and scaling in production. MLOps bridges the gap between data science and software engineering to ensure reliability, reproducibility, and continuous delivery of ML systems.

---

## 🧠 Topics Covered

### 📦 ML Pipeline Essentials
- Data Ingestion & Validation
- Data Versioning (DVC, LakeFS)
- Feature Store Basics
- Model Training & Validation
- Model Packaging (ONNX, Pickle, TorchScript)

### 🔍 Experiment Tracking & Versioning
- MLflow, Weights & Biases (wandb)
- TensorBoard
- Git for code versioning
- DVC / Delta Lake / Feast for dataset and feature versioning

### ⚙️ Model Deployment
- Batch vs Online vs Streaming inference
- REST APIs with FastAPI / Flask / Django
- gRPC vs REST for model serving
- TorchServe, Triton Inference Server
- Model Containerization (Docker)
- Deployment Strategies: Blue-Green, Canary, A/B Testing

### ☁️ Cloud & Infra
- AWS Sagemaker / Lambda / EC2
- GCP Vertex AI
- Azure ML
- Kubernetes, Helm Charts
- Terraform for Infra-as-Code (IaC)

### 🔄 CI/CD for ML
- GitHub Actions / GitLab CI
- Jenkins Pipelines
- Triggering retraining jobs
- Reproducibility & model checksum validation
- MLflow + Jenkins + Docker + Kubernetes Pipeline

### 📈 Monitoring & Logging
- Model Drift / Data Drift Detection
- Feature Distribution Tracking
- Concept Drift (using Evidently.ai / Alibi Detect)
- Logging: Prometheus + Grafana + Loki
- Alerting on Performance Drops

### 🔒 Responsible & Secure MLOps
- Model Explainability (SHAP, LIME, Captum)
- Fairness metrics
- PII scrubbing, encrypted pipelines
- Role-based access (IAM)
- Bias detection and audit logs

### 🔧 Tools & Platforms
- MLflow, DVC, Kedro, Kubeflow
- TFX (TensorFlow Extended), Airflow, Prefect
- BentoML, Seldon Core, KFServing
- Great Expectations for data validation
- Ray for scalable training and inference

---

## 📁 Folder Structure

- `notes/`  
  📚 High-level summaries, tool comparisons, CI/CD best practices, infrastructure diagrams, and process checklists.

- `projects/`  
  ⚙️ End-to-end MLOps pipelines including:
  - Model deployment using FastAPI + Docker
  - MLflow training + tracking + registry setup
  - Jenkins + Docker + Kubernetes mini CI/CD project

- `diagrams/`  
  🧠 Visuals of ML architecture, deployment flows, pipeline DAGs, and CI/CD integration (draw.io / PlantUML / Excalidraw).

---

## 🚀 Project Ideas
- Build a complete pipeline: data prep → train → log → deploy → monitor
- Model deployment on AWS Lambda vs Docker + EC2
- CI/CD pipeline with MLflow + Jenkins + Kubernetes
- Compare model drift detection tools (e.g., Alibi vs Evidently)
- Create a mock-up MLOps platform for managing 10+ models

---

**Train hard. Deploy smart. Monitor forever.**  
That’s the MLOps mantra.

Let your models not only learn,  
but thrive in production.
