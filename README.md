<p align="center">
  <img src="assets/guiyi-labs-banner.png" width="100%" alt="Guiyi Labs - Infrastructure Automation, Observability and AIOps" />
</p>

<p align="center">
  <strong>Converging complex infrastructure into reliable operations.</strong><br />
  Linux · Network Automation · Kubernetes · Observability · AIOps
</p>

<p align="center">
  <a href="https://github.com/guiyi-labs/aiops-platform">Flagship Project</a> ·
  <a href="https://github.com/guiyi-labs/aiops-platform/releases">Releases</a> ·
  <a href="https://github.com/guiyi-labs/aiops-platform/blob/main/docs/README.md">Engineering Docs</a> ·
  <a href="https://github.com/guiyi-labs/aiops-platform/blob/main/docs/thesis/README.md">Thesis Materials</a>
</p>

---

## Infrastructure, end to end

围绕系统、网络与 Kubernetes 三层基础设施，构建可观测、可诊断、可控制、可复现的运维工程系统。

- **Systems** · [devops-automation](https://github.com/guiyi-labs/devops-automation) — 主机管理、任务编排、监控与部署自动化
- **Networks** · [netcheck-platform](https://github.com/guiyi-labs/netcheck-platform) — 网络巡检、故障诊断、告警、拓扑与报告
- **Clusters** · [aiops-platform](https://github.com/guiyi-labs/aiops-platform) — Kubernetes 多集群、可观测、诊断与受控运维
- **Provisioning** · [kubernetes-cluster-bootstrap](https://github.com/guiyi-labs/kubernetes-cluster-bootstrap) — kubeadm、Ansible 与高可用集群部署实践

---

## Flagship · Kubernetes Multi-Cluster AIOps Platform

[CI status](https://github.com/guiyi-labs/aiops-platform/actions/workflows/ci.yml) ·
[Latest release](https://github.com/guiyi-labs/aiops-platform/releases) ·
[Apache-2.0](https://github.com/guiyi-labs/aiops-platform/blob/main/LICENSE)

<p align="center">
  <a href="https://github.com/guiyi-labs/aiops-platform">
    <img src="assets/aiops-dashboard.png" width="100%" alt="AIOps multi-cluster operations dashboard" />
  </a>
</p>

面向中小规模 Kubernetes 环境的多集群可观测、证据型故障诊断与受控运维平台。

- **Evidence-first diagnosis**：确定性规则保留资源状态、事件与引用证据，AI 仅作可选解释增强。
- **Controlled operations**：高风险动作统一经过权限校验、dry-run、确认、幂等执行与审计。
- **Multi-cluster isolation**：有界并发、故障隔离，以及 Cluster + Namespace 粒度授权。
- **Reproducible delivery**：真实 kind E2E、OpenAPI 契约、CI 门禁、SBOM、签名与版本化归档。

> **Observe → Diagnose → Explain → Preview → Confirm → Execute → Audit**

<details>
  <summary><strong>View diagnosis evidence interface</strong></summary>
  <br />
  <img src="assets/aiops-diagnosis.png" width="100%" alt="Evidence-based diagnosis interface" />
</details>

---

## Applied AI systems

- [**XHZhishu**](https://github.com/guiyi-labs/XHZhishu) — 可信 RAG、知识图谱与科研计算工作流
- [**zhijingtong**](https://github.com/guiyi-labs/zhijingtong) — 面向低资源服务器的轻量 RAG 工作台

---

## Engineering principles

- **Deterministic core** — AI-assisted explanation
- **Least privilege** — Explicit capability boundaries
- **Preview and confirmation** — Idempotent execution
- **Real environment tests** — Retained delivery evidence

<p align="center">
  <sub>Reproducibility · Observability · Controlled Delivery</sub>
</p>
