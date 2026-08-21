# ☁️ AWS Static Website Hosting

A responsive personal portfolio website deployed using **Amazon S3 Static Website Hosting**.

This project demonstrates the complete process of creating a static website, hosting it on AWS, configuring access permissions, and documenting the deployment using GitHub.

---

## 🎯 Project Overview

The goal of this project was to build and deploy a simple professional portfolio website using AWS cloud infrastructure.

The website contains:

- Personal introduction
- Cybersecurity background
- Technical skills
- AWS project information
- GitHub profile

The website is hosted using **Amazon S3** without requiring an EC2 server.

---

## 🏗️ Architecture

```text
                    Internet
                       │
                       ▼
                ┌─────────────┐
                │    User     │
                │   Browser   │
                └──────┬──────┘
                       │
                       ▼
              ┌─────────────────┐
              │    Amazon S3    │
              │                 │
              │  index.html     │
              │  style.css      │
              └────────┬────────┘
                       │
                       ▼
                Static Website
