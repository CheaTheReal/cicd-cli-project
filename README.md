# CI/CD Pipeline with AWS CLI

This project demonstrates a fully automated CI/CD pipeline using AWS CodePipeline, CodeBuild, and S3 — deployed entirely via the AWS CLI.

## 🛠️ Tools Used
- AWS CodePipeline
- AWS CodeBuild
- Amazon S3 (Static Website Hosting + Artifact Storage)
- GitHub (Source Control)
- AWS CLI (Full Deployment from Terminal)

## 🚀 What It Does
- GitHub push triggers CodePipeline
- CodeBuild processes and copies `index.html`
- Artifacts stored in S3
- Project deployed entirely via the terminal

## 📁 File Structure
cicd-cli-project/
├── index.html # Static website content
├── buildspec.yml # CodeBuild build instructions
├── codepipeline-project.json
├── codebuild-project.json
├── codepipeline-trust-policy.json


## ✅ Outcome
CI/CD pipeline executes on every GitHub push. Build artifacts uploaded to S3 automatically.

## 👤 Author
Fernando Perez — [@CheaTheReal](https://github.com/CheaTheReal)

