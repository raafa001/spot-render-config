# Issues planejadas

## Dev
- **API Upload + CLI** – implementar FastAPI com endpoints, integração S3, métricas, CLI helper e testes.
- **Portal Next.js** – formulário de upload, listagem e integração com API.
- **Argo Scripts** – `convert_materials.py`, `render_blender.py`, workflow templated e Dockerfile worker.

## DevOps
- **Terraform Infra** – provisionar VPC, EKS, S3, Secrets, IRSA, ingress+WAF.
- **CI/CD template** – padronizar workflows (lint/test → Sonar → build → push → deploy) para todos os repositórios.
- **K8s Manifests** – Rollouts, HPAs, ServiceMonitors para API/Portal/Exporter.

## QA
- Plano de testes (unit, integração, E2E, workflow), cobertura >= 80%, pipeline gate.

## DBRE
- Naming/retention S3, custos, guidelines Secrets Manager e rotinas de rotação.

## SRE
- Exporter/Grafana/Alertas/Runbooks/SLOs para operações e canary.
