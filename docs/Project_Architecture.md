# Project Architecture & DevOps Lifecycle

## 1. High-Level System Architecture

The application is a stateless REST API built with Python and FastAPI. It receives HTTP requests, processes student data, and returns JSON responses.

```mermaid
flowchart LR
    Client([Client/Browser]) <-->|HTTP/REST| K8sService[Kubernetes Service\nLoadBalancer]
    K8sService <--> Pod1[Pod: FastAPI App]
    K8sService <--> Pod2[Pod: FastAPI App]
```

## 2. CI/CD DevOps Pipeline Architecture

```mermaid
flowchart TD
    A[Developers\nWrite Python Code] -->|Push Code| B(Git & GitHub\nVersion Control)
    B -->|Trigger Webhook| C{Jenkins CI/CD\nPipeline}
    
    C -->|Stage 1: Checkout| D[Git Checkout]
    D -->|Stage 2: Install & Test| E[Pytest Execution]
    E -->|Stage 3: Package| F[Build Docker Image]
    F -->|Stage 4: Deploy| G[Deploy to Kubernetes]
    
    G --> H((Running Application\nMonitored by SRE))
```
