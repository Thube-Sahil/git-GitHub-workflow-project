# Git & GitHub Workflow Project

## Project Overview

This repository demonstrates a complete Git and GitHub workflow, covering fundamental to advanced version control concepts used in software development and DevOps environments.

## Objectives

* Learn Git Fundamentals
* Learn GitHub Repository Management
* Practice Branching Strategies
* Practice Pull Requests and Merging
* Resolve Merge Conflicts
* Learn Advanced Git Operations
* Understand Git Tags and Releases
* Explore CI/CD Integration

---

## Phase 1 – Git Repository Setup

### Topics Covered

* Project Directory Creation
* Git Installation and Configuration
* Git Repository Initialization
* Working Directory
* Staging Area
* First Commit Creation

### Commands Practiced

```bash
git init
git add .
git commit -m "Initial project setup"
git status
git log --oneline
```

---

## Phase 2 – GitHub Integration

### Topics Covered

* GitHub Repository Creation
* Connecting Local and Remote Repositories
* Pushing Code to GitHub
* Branch Renaming (master → main)

### Commands Practiced

```bash
git remote add origin <repository-url>
git branch -M main
git push -u origin main
```

---

## Phase 3 – Branching Workflow

This section was added from the feature/readme-update branch.

### Topics Covered

* Branch Creation
* Feature Development Workflow
* Git Commit Workflow
* GitHub Integration

### Commands Practiced

```bash
git checkout -b feature/readme-update
git add .
git commit -m "Update README from feature branch"
git push -u origin feature/readme-update
```

---

## Phase 4 – Pull Requests & Merge Conflict Resolution

### Topics Covered

* Feature Branch Workflow
* Pull Request Creation
* Merge Operations
* Merge Conflict Resolution
* Branch Cleanup

### Commands Practiced

```bash
git merge feature/login
git merge feature/profile
git add .
git commit -m "Resolved merge conflict"
```

---

## Phase 5 – Advanced Git Operations

### Topics Covered

* Git Stash
* Git Reset
* Git Revert
* Git Cherry-Pick

### Commands Practiced

```bash
git stash
git stash pop
git reset --soft HEAD~1
git revert <commit-id>
git cherry-pick <commit-id>
```

---

## Phase 6 – GitHub Collaboration Workflow

### Topics Covered

* Code Reviews
* Pull Requests
* Team Collaboration
* Branch Protection Concepts

---

## Phase 7 – GitHub Issues & Project Management

### Topics Covered

* Issue Tracking
* Bug Reporting
* Feature Requests
* Agile Workflow Basics

---

## Phase 8 – GitHub Actions & CI/CD

### Topics Covered

* Introduction to GitHub Actions
* Automated Workflows
* Continuous Integration
* Continuous Deployment Concepts

### Sample Workflow

```yaml
name: CI Pipeline

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - uses: actions/checkout@v4
    - name: Verify Repository
      run: echo "CI Pipeline Running"
```

---

## Phase 9 – Git Tags & Releases

### Topics Covered

* Lightweight Tags
* Annotated Tags
* Semantic Versioning
* GitHub Releases

### Commands Practiced

```bash
# Git & GitHub Workflow Project

## Project Overview

This repository demonstrates a complete Git and GitHub workflow, covering fundamental to advanced version control concepts used in software development and DevOps environments.

## Objectives

* Learn Git Fundamentals
* Learn GitHub Repository Management
* Practice Branching Strategies
* Practice Pull Requests and Merging
* Resolve Merge Conflicts
* Learn Advanced Git Operations
* Understand Git Tags and Releases
* Explore CI/CD Integration

---

### Topics Covered


