<div align="center">

# 归一 · Guiyi Labs

**Kubernetes · DevOps · AIOps Engineering**

<p>
让复杂系统归一：可观测、可诊断、可控制。<br />
Converging complex systems into reliable operations.
</p>

[![GitHub](https://img.shields.io/badge/GitHub-guiyi--labs-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/guiyi-labs)
[![Followers](https://img.shields.io/github/followers/guiyi-labs?style=flat-square&label=Followers&color=326CE5)](https://github.com/guiyi-labs?tab=followers)
[![Profile Views](https://komarev.com/ghpvc/?username=guiyi-labs&style=flat-square&color=0E7490&label=Profile+Views)](https://github.com/guiyi-labs)

</div>

## 我们在做什么 / What We Build

我们专注于 Kubernetes、DevOps、AIOps 与自动化工程实践，构建可运行、可验证、可交付的系统，而不是停留在概念演示。

- **云原生运维**：多集群管理、资源工作台、可观测性与故障诊断。
- **受控自动化**：任务编排、确定性规则、权限校验、确认、幂等与审计。
- **可信 AI 工程**：RAG、知识图谱、可解释降级，以及 AI 增强但不越权的运维流程。
- **可复现交付**：容器化部署、真实集群验证、自动化测试与版本化归档。

## 旗舰项目 / Flagship Project

### [Kubernetes Multi-Cluster AIOps Platform](https://github.com/guiyi-labs/aiops-platform)

[![CI](https://github.com/guiyi-labs/aiops-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/guiyi-labs/aiops-platform/actions/workflows/ci.yml)
![Go](https://img.shields.io/badge/Go-1.25-00ADD8?style=flat-square&logo=go&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1.34-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

面向中小规模 Kubernetes 环境的多集群可观测、证据型故障诊断与受控运维平台。

[![Kubernetes AIOps dashboard](assets/aiops-dashboard.png)](https://github.com/guiyi-labs/aiops-platform)

| Capability | Engineering approach |
| :-- | :-- |
| Multi-cluster operations | Bounded concurrency, timeout, sampling limits, partial-failure reporting |
| Evidence-based diagnosis | Deterministic rules retain resource snapshots, events, and traceable evidence |
| Controlled remediation | Dry-run, typed diff, confirmation, idempotency, RBAC, and audit trail |
| Delivery verification | Go/Vitest tests, Docker Compose, Kustomize, real kind E2E, versioned artifacts |

## 项目矩阵 / Project Portfolio

| Project | Focus | Stack |
| :-- | :-- | :-- |
| [aiops-platform](https://github.com/guiyi-labs/aiops-platform) | Kubernetes 多集群可观测、诊断与受控运维 | Go · Vue · TypeScript · PostgreSQL |
| [XHZhishu](https://github.com/guiyi-labs/XHZhishu) | 可信 RAG、知识图谱与科研计算平台 | Python · Vue · PostgreSQL · Neo4j |
| [netcheck-platform](https://github.com/guiyi-labs/netcheck-platform) | 网络自动化巡检、故障诊断、报告与告警 | Python · FastAPI · JavaScript · Docker |
| [devops-automation](https://github.com/guiyi-labs/devops-automation) | 任务编排、资产管理、监控与 Kubernetes 部署 | Python · FastAPI · Vue · Redis |
| [kubernetes-cluster-bootstrap](https://github.com/guiyi-labs/kubernetes-cluster-bootstrap) | kubeadm 单节点、高可用与 Ansible 自动部署实践 | Kubernetes · kubeadm · Ansible · Linux |

## 技术栈 / Technology Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,ansible,prometheus,grafana,go,python,fastapi,vue,ts,postgres,redis,linux,git,githubactions&perline=15" alt="Kubernetes, Docker, Ansible, Prometheus, Grafana, Go, Python, FastAPI, Vue, TypeScript, PostgreSQL, Redis, Linux, Git, GitHub Actions" />
</p>

| Area | Technologies |
| :-- | :-- |
| Cloud Native | Kubernetes, client-go, kubeadm, kind, Kustomize, Docker Compose |
| Backend & Data | Go, Python, FastAPI, PostgreSQL, pgvector, Redis, Neo4j |
| Frontend | Vue 3, TypeScript, Vite, Lucide |
| Observability | Kubernetes Metrics API, Prometheus, Grafana, structured audit events |
| Delivery | GitHub Actions, automated tests, real-cluster E2E, OCI archives, SHA-256 manifests |

## 工程原则 / Engineering Principles

```text
Deterministic core        AI-assisted explanation
Least privilege          Explicit capability boundaries
Preview and confirmation Idempotent execution
Real environment tests   Retained delivery evidence
```

- 先建立确定、可复现的主链路，再引入 AI 增强能力。
- 高风险操作必须经过权限校验、预览、确认、幂等执行和审计。
- 用自动化测试、真实环境验证和归档证据支撑交付结论。
- AI 可以解释与辅助决策，但不直接获得不受限制的变更权限。

## 当前重点 / Current Focus

- Kubernetes 多集群健康比较、全局资源搜索与故障隔离。
- 基于真实 kind 集群的诊断、Metrics 和受控操作端到端验证。
- 可信 RAG、GraphRAG 与垂直领域科研工作流。
- 可审计的自动化平台与版本化交付体系。

## GitHub Activity

<p align="center">
  <a href="https://github.com/guiyi-labs">
    <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=guiyi-labs&theme=github" alt="Guiyi Labs GitHub statistics" />
  </a>
  <a href="https://github.com/guiyi-labs">
    <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=guiyi-labs&theme=github" alt="Guiyi Labs languages by repository" />
  </a>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=guiyi-labs&bg_color=ffffff&color=24292f&line=326CE5&point=0E7490&area=true&hide_border=true" alt="Guiyi Labs contribution activity" />
</p>

<div align="center">

<sub>Reproducibility · Observability · Controlled Delivery</sub>

</div>
