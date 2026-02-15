# Kaggle_Assignment_Lab4

# 🧪 ML Lab 4 – Branching, Merging and Team Workflow using GitHub (Kaggle Environment)

## 📌 Aim

To implement and demonstrate GitHub team workflow using branching, committing, pull requests, and merging operations through a cloud-based development environment (Kaggle).

---

## 🎯 Objectives

* Create and manage multiple branches
* Work on independent features in separate branches
* Push branches to remote repository
* Create and merge Pull Requests
* Synchronize local and remote repositories
* Simulate real-world collaborative development workflow

---

## 🛠️ Tools & Technologies Used

* Git
* GitHub
* Kaggle Notebook (Linux environment)

---

## 📂 Repository Structure

```
Kaggle_Assignment_Lab4/
│── feature1.txt
│── feature2.txt
│── README.md
```

---

## ⚙️ Workflow Steps

### 1️⃣ Repository Creation

* Created a new repository on GitHub
* Cloned the repository into Kaggle environment

```bash
git clone <repo-url>
cd Kaggle_Assignment_Lab4
```

---

### 2️⃣ Initial Commit

* Added initial project files
* Pushed to main branch

```bash
git add .
git commit -m "Initial commit"
git push origin main
```

---

### 3️⃣ Branch Creation & Feature Development

#### 🔹 Feature 1 Branch

```bash
git checkout -b feature-1
```

* Created `feature1.txt`
* Committed and pushed

```bash
git add .
git commit -m "Added feature 1"
git push origin feature-1
```

---

#### 🔹 Feature 2 Branch

```bash
git checkout main
git checkout -b feature-2
```

* Created `feature2.txt`
* Committed and pushed

```bash
git add .
git commit -m "Added feature 2"
git push origin feature-2
```

---

### 4️⃣ Pull Request Creation

* Created Pull Requests for:

  * `feature-1 → main`
  * `feature-2 → main`
* Reviewed changes
* Merged both branches into main

---

### 5️⃣ Synchronization with Local Repository

```bash
git checkout main
git pull origin main
```

---

## 🔁 Team Workflow Demonstrated

✔ Parallel development using branches
✔ Independent feature implementation
✔ Code integration using Pull Requests
✔ Version control and history tracking
✔ Cloud-based development using Kaggle

---

## 📊 Result

Successfully implemented branching, merging, and collaborative workflow using GitHub.
All feature branches were merged into the main branch using Pull Requests, demonstrating a real-world team development process.

---

## 🌍 Real-World Application

This workflow is used in:

* Machine Learning projects
* Software product development
* Open-source collaboration
* MLOps pipelines

---

## 👨‍💻 Author

**Pratik Nagdeve**
M.Tech Artificial Intelligence – MANIT Bhopal

---

## 🔗 Repository Link

https://github.com/PratikNagdeve/Kaggle_Assignment_Lab4
