# MLOps Project: Iris Classifier API 🌸

This project demonstrates a complete MLOps pipeline for training, versioning, and deploying a machine learning model using MLflow, DVC, Docker, and Flask.

## 🏛️ Architecture Overview

* **Code Versioning**: **Git**
* **Data Versioning**: **DVC**
* **Experiment Tracking & Model Registry**: **MLflow**
* **API Service**: **Flask**
* **Containerization**: **Docker**
* **CI/CD**: **GitHub Actions**

---

## 🚀 Local Setup Instructions

Follow these steps to get the project running on your local machine.

### Prerequisites

Make sure you have the following tools installed:
* Python 3.8+
* Git
* [DVC](https://dvc.org/doc/install)
* [Docker](https://docs.docker.com/get-docker/)

### Step 1: Clone the Repository
```bash
git clone <your-repository-url>
cd mlops-assignment
```

### Step 2: Configure Multiple GitHub Users (Optional)

If you're working with multiple GitHub accounts, follow these steps:

```bash
# Configure user for this repository only
git config user.name "Your Name"
git config user.email "your-email@example.com"

# Or set up SSH keys for different accounts
# 1. Generate SSH key: ssh-keygen -t ed25519 -C "your-email@example.com"
# 2. Add to SSH agent: ssh-add ~/.ssh/id_ed25519
# 3. Add public key to your GitHub account
# 4. Update .ssh/config with host configurations
```

### Step 3: Set Up Environment
