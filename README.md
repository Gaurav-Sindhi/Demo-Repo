# Demo-Repo

# 🚀 Python CI/CD Demo using AWS CodePipeline & CodeBuild

## 📌 Project Overview

This project demonstrates a simple Continuous Integration (CI) pipeline using **AWS CodePipeline** and **AWS CodeBuild** integrated with a GitHub repository.

Whenever code is pushed to the repository, the pipeline is automatically triggered to:

* Fetch the latest source code
* Install dependencies
* Run automated tests
* Generate build artifacts

---

## 🧩 Tech Stack

* **Python 3.11**
* **AWS CodePipeline**
* **AWS CodeBuild**
* **GitHub**
* **Pytest (for testing)**

---

## 📁 Project Structure

```
my-python-ci-demo/
│
├── app.py
├── requirements.txt
├── buildspec.yml
├── README.md
└── tests/
    └── test_app.py
```

---

## ⚙️ How It Works

1. Developer pushes code to GitHub
2. AWS CodePipeline detects changes via webhook
3. CodeBuild installs dependencies and runs tests
4. If tests pass → pipeline succeeds
5. If tests fail → pipeline stops

---

## ▶️ Running Locally

### Step 1: Install dependencies

```
pip install -r requirements.txt
```

### Step 2: Run the app

```
python app.py
```

### Step 3: Run tests

```
pytest
```

---

## ☁️ CI/CD Pipeline Flow

GitHub → CodePipeline → CodeBuild → (Optional Deployment)

---

## 🎯 Features

* Automated testing using Pytest
* Fully serverless CI pipeline
* Easy integration with AWS services
* Scalable and production-ready structure

---

## 🚀 Future Enhancements

* Add deployment stage (Elastic Beanstalk / EC2)
* Integrate linting (flake8)
* Add code coverage reports
* Use AWS CodeDeploy for full CI/CD

---

## 👨‍💻 Author

**Gaurav Narayani**
B.Tech CSE | AWS & DevOps Enthusiast

---

## ⭐ If you like this project

Give it a star on GitHub!
