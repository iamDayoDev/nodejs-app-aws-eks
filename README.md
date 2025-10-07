# 🌀 Deploying a Simple Node.js App on AWS EKS

### A Beginner-Friendly and Cost-Effective Guide

This project demonstrates how to deploy a simple Node.js application on **Amazon Elastic Kubernetes Service (EKS)** — without overspending.  
The goal is to help beginners and developers learn **EKS deployment** while keeping costs under **$2** using minimal AWS resources.

## 🧠 Introduction

Most tutorials on Kubernetes jump straight into complex setups and assume deep prior knowledge.  
But in the real world, **cost matters** — especially for learners, small teams, and startups.

This guide shows how to:
- Deploy a simple Node.js app with a `/health` endpoint
- Configure **EKS** efficiently without overspending
- Test, scale, and clean up resources after use

By the end, you’ll not only know how to deploy to AWS EKS but also learn how to **think like a cost-conscious cloud engineer**.

---

## 🧰 Prerequisites

You’ll need the following tools:

- **AWS Account:** To create and manage cloud resources (EKS, EC2, etc.)
- **AWS CLI:** Command-line interface to manage AWS services  
- **kubectl:** Tool to manage Kubernetes clusters and deployments  
- **eksctl:** Simplifies EKS cluster creation and management  
- **Docker:** To containerize your Node.js app  
- **Node.js & npm:** Required to build and run the sample app  
- **VS Code (or any IDE):** To write and edit your code  
- **(Optional) Docker Hub account:** To store your Docker images

---


