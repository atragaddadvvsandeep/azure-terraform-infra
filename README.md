# Azure Terraform CI/CD Project

## 📌 Overview
This project demonstrates automated Azure infrastructure deployment using Terraform and GitHub Actions.

## 🚀 What this project does
- Creates Azure Resource Group, Virtual Network, and Subnet
- Uses Terraform for Infrastructure as Code
- Automates deployment using GitHub Actions (CI/CD)
- Uses Service Principal for secure authentication

## ⚙️ Tech Stack
- Terraform
- Azure
- GitHub Actions

## 🔄 Workflow
1. Push code to GitHub
2. GitHub Actions runs pipeline
3. Terraform Init → Plan → Apply
4. Infrastructure created automatically

## 🧠 Key Learning
- Terraform lifecycle (init, plan, apply, destroy)
- CI/CD automation for cloud infra
- Secret management using GitHub Actions