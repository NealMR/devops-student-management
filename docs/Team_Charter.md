# Team Charter

## Roles

1. **S1 (Neal)** - Product Owner / Team Lead: Generate project documentation.
2. **S2 (Sagar)** - Developer 1 - Login: Write authentication module.
3. **S3 (Yash)** - Developer 2 - Registration: Write registration module.
4. **S4 (Harshwardhan)** - Developer 3 - Management: Write core CRUD API.
5. **S5 (Jyotiraditya)** - QA Engineer: Write tests using Pytest.
6. **S6 (Atharv)** - Git Engineer: Manage version control and branch protections.
7. **S7 (Omkar)** - Jenkins Engineer: Create Jenkins pipeline for CI/CD.
8. **S8 (Tanishq)** - Docker Engineer: Containerize the application.
9. **S9 (Siddhik)** - Kubernetes Engineer: Create K8s deployment and service manifests.
10. **S10 (Rushikesh)** - DevOps/SRE Engineer: Coordinate final documentation.

## GitFlow Strategy

- **main**: Production-ready code. Commits here should be tagged for releases.
- **feature/***: Individual feature branches for each team member (e.g., `feature/S1`). These should be merged into `main` via Pull Requests.
- Pull Requests require code review and passing CI pipeline before merging.
