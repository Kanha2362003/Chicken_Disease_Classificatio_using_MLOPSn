🐔 Chicken Disease Classification — End-to-End Deep Learning Project with MLOps
This project presents a production-grade deep learning pipeline for image-based classification of chicken diseases, designed using modern MLOps best practices. It demonstrates the complete machine learning lifecycle — from data ingestion and preprocessing to model training, versioning, CI/CD automation, and cloud deployment. The pipeline is implemented using a modular and scalable architecture, leveraging tools like DVC, GitHub Actions, and Docker, with deployment on both Azure App Services and AWS EC2.

🚀 Project Overview
Problem Statement: Classify poultry diseases using deep learning to support real-time veterinary diagnostics.

Approach: Leveraged Transfer Learning with TensorFlow/Keras to build an efficient and high-accuracy image classification model.

MLOps Integration: Adopted DVC for tracking datasets, models, and pipeline stages, ensuring full reproducibility across environments.

CI/CD Workflow: Configured GitHub Actions for automating training, testing, and deployment pipelines.

Deployment: Containerized the FastAPI-based inference service using Docker, and deployed to production environments on Azure and AWS.

.

🧰 Tech Stack
Languages & Frameworks: Python, TensorFlow, FastAPI

MLOps Tools: DVC, Git, GitHub Actions, YAML

Deployment: Docker, Azure App Services, AWS EC2

Others: NumPy, OpenCV, Pandas, Pytest, Logging

🔁 MLOps Workflow Summary
Modular Design: Built with clean separation of concerns — config files, data loaders, model builders, and pipelines are independent and reusable.

DVC Tracking: Datasets, trained models, and metrics tracked with DVC for full reproducibility.

Remote Storage: DVC connected to cloud (e.g., AWS S3 or GDrive) for storing versioned assets.

CI/CD Automation: GitHub Actions workflow automates testing, DVC pull, model training, and deployment on push/merge.

Cloud-Native Deployment: Docker containers run on cloud services for scalable access to prediction APIs.

💡 Learning Outcomes
Applied full ML engineering lifecycle from data to deployment

Mastered real-world tools like DVC, Docker, and GitHub Actions

Gained practical experience in MLOps — bridging the gap between model development and production delivery

Developed skills in cloud deployment and scalable API design

