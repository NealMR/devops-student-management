# DevOps Team Charter

## Project Title
**DevOps-Based Student Management Web Application (FastAPI)**

## Purpose
To implement the complete DevOps lifecycle through a unified mini-project. The goal is to build, test, containerize, deploy, and monitor a Student Management application using modern DevOps practices and tools.

## Team Members & Responsibilities
| Role | Assigned Student | Core Responsibility | Key Technologies |
| :--- | :--- | :--- | :--- |
| **Product Owner / Team Lead** | S1 Neal | Requirements gathering, team coordination, project architecture | Agile, System Design |
| **Developer 1 (Login)** | S2 Sagar | Implement the authentication and login module | Python, FastAPI |
| **Developer 2 (Registration)** | S3 Yash | Implement the student registration module | Python, FastAPI |
| **Developer 3 (Management)** | S4 Harshwardhan | Implement core student management (CRUD operations) | Python, FastAPI |
| **QA Engineer** | S5 Jyotiraditya | Write and execute automated test cases | Pytest |
| **Git/GitHub Engineer** | S6 Atharv | Manage version control, pull requests, and GitFlow branching | Git, GitHub |
| **Jenkins Engineer** | S7 Omkar | Design and maintain the CI/CD pipeline jobs | Jenkins |
| **Docker Engineer** | S8 Tanishq | Containerize the application and manage images | Docker |
| **Kubernetes Engineer** | S9 Siddhik | Orchestrate deployment to the cluster | Kubernetes |
| **DevOps/SRE Engineer** | S10 Rushikesh | Final end-to-end integration, monitoring, and documentation | Full Pipeline, Metrics |

## Workflow / GitFlow Strategy
1. **Main Branch:** Production-ready code (`main`).
2. **Feature Branches:** Developers work on `feature/<role-id>` and submit Pull Requests.
3. **CI/CD Integration:** Merges into `main` automatically trigger the Jenkins CI/CD pipeline.
