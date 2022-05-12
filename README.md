<h1 align="center">selec. Prod</h1>

> Developed as a part of CS 816 - Software Production Engineering course.

This repository contains files which are required for production.

Architecture Diagram

![Architecture Diagram for prod](https://github.com/DaKeiser/review-portal-prod/blob/main/assets/arch.png)

Files included
- kubernetes infra
    - `./infra/k8s/frontend-deployment-service.yml`
    - `./infra/k8s/backend-deployment-service.yml`
- Monitoring using Loki and Grafana
    - `./docker-compose.yaml`