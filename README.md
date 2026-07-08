# Gunwoo Kim

**Platform Engineer / DevOps**

I focus on making deployment, runtime, and observability workflows measurable, repeatable, and reviewable.

## Current Focus

- **CI/CD measurement and optimization**  
  Jenkins stage metrics, Docker layer/cache structure, image size, image digest, build/deploy agent separation

- **Runtime provisioning**  
  Ansible-based tenant runtime server preparation, config repo driven deploy targets, Docker Compose runtime setup

- **Kubernetes GitOps**  
  RKE2, Argo CD, GitHub Actions, GHCR, promotion PR, tag@sha256 digest pinning, rollout/readiness troubleshooting

- **Observability**  
  OpenTelemetry Collector agent/gateway pattern, Grafana LGTM, log/trace/metric collection path standardization

- **AI-assisted workflow**  
  Codex/Claude based task harnesses for repeatable DB change drafts, checklist-based review, and team handoff

## Selected Work

| Area | What I worked on |
| --- | --- |
| Jenkins / Docker CI/CD | Measured stage-level bottlenecks and improved Docker build/push flow with layer/cache and runtime image changes |
| Ansible Provisioning | Standardized tenant runtime server preparation for IDC Demo/PoC environments |
| RKE2 GitOps | Built and troubleshot a personal Kubernetes GitOps flow with Argo CD, GHCR, and image digest pinning |
| Observability Platform | Configured OpenTelemetry Collector and Grafana LGTM to separate collection, export, storage, and query responsibilities |
| DB Change Workflow | Used Liquibase changelog templates and AI-assisted review harnesses to make DB change requests easier to review |

## Public Projects

- [FQS - Flexible Queue Service](https://github.com/kimgunwooo/FQS-flexible-queue-service)  
  B2B queue management service experiment with Docker-based dynamic instances and Spring Cloud Gateway routing.

- [FQS SDK](https://github.com/kimgunwooo/FQS-sdk)  
  Java SDK for integrating queue functionality with less application-side boilerplate.

- [Fizz Backend](https://github.com/kimgunwooo/fizz-challenge-backend)  
  AWS S3, Lambda, MediaConvert, CloudFront based media upload and encoding pipeline project.

## Tech Stack

**Platform / Container**  
Docker, Docker Compose, Harbor, Kubernetes(RKE2), Argo CD, GitHub Actions, GHCR

**Automation / CI/CD**  
Jenkins, Ansible, Shell, Linux

**Observability**  
OpenTelemetry, Grafana, Loki, Tempo, Mimir, Prometheus

**Backend / Database**  
Java, Spring Boot, Spring Security, PostgreSQL, MySQL, Redis, Liquibase

## Links

- Blog: [velog.io/@kimgunwooo](https://velog.io/@kimgunwooo/posts)
- Email: [kw4u1223@gmail.com](mailto:kw4u1223@gmail.com)
