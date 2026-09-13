<div align="center">
  <img src="assets/header.svg" width="100%" alt="wenmou — Go / Rust · Cloud Native · Agent Runtime" />

  <p><strong>Building reliable services, from runtime to infrastructure.</strong></p>

  <a href="https://wenmou.site/"><img src="https://img.shields.io/badge/Blog-wenmou.site-245B78?style=flat-square" alt="Blog: wenmou.site" /></a>
  <a href="mailto:wenmou.me@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_talk-1F6FEB?style=flat-square" alt="Email: wenmou.me@gmail.com" /></a>
</div>

### 👋 About Me

你好，我是 **wenmou / 孟德红**，浙江工业大学计算机硕士，2027 届。目前在拓数派担任基础架构开发实习生，关注 **Go 后端、Rust 开发、Agent Runtime 与云原生平台**。

我喜欢把服务研发和基础设施实践连起来：从沙箱生命周期、并发执行与故障恢复，到 Kubernetes、GitOps 交付和可观测性；也会把实际使用中发现的问题修复贡献到开源上游。

*CS master's student at ZJUT, building Go services and cloud-native infrastructure, exploring Rust, and contributing fixes upstream.*

### ⚙️ Engineering Focus

| 方向 | 实践 |
| :--- | :--- |
| **Go / Agent Runtime** | 基于 Go、PostgreSQL 与 OpenSandbox 开发沙箱运行服务，管理创建、续期、恢复与回收，解耦计算资源和项目存储。 |
| **Reliability & Performance** | 持久化任务、幂等重试、租约与版本校验；优化 Worker 并发、SQL 和数据库连接预算，通过调用链与压测验证。 |
| **Cloud Native & DevOps** | 使用 Ansible 建设裸金属 Kubernetes 集群，结合 Concourse、Harbor 与 Argo CD 完成跨环境制品交付、版本校验与回滚。 |
| **Observability** | 使用 OpenTelemetry 关联异步任务与服务调用，定位排队、慢查询和失败阶段。 |

### 🤝 Open Source

**[OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) · 使用者与贡献者**

从业务接入中的问题出发，补充复现、实现修复，并完成兼容性与 Kubernetes 集群验证。部分已合并贡献：

| 贡献 | 解决的问题 |
| :--- | :--- |
| [Native argv execution · #1760](https://github.com/opensandbox-group/OpenSandbox/pull/1760) | 为 Go execd 增加原生参数执行，贯通 API 与五种语言 SDK，支持不经 Shell 解析的参数传递。 |
| [SDK connection reliability · #1751](https://github.com/opensandbox-group/OpenSandbox/pull/1751) | 修复端点尚未发布时的过早失败，统一暂态重试、超时预算与取消传播。 |
| [Informer cache consistency · #1674](https://github.com/opensandbox-group/OpenSandbox/pull/1674) | 修复迟到响应覆盖新状态、删除对象回写等竞态，补充并发测试。 |

[查看全部已合并贡献 →](https://github.com/opensandbox-group/OpenSandbox/pulls?q=is%3Apr+author%3Amengdehong+is%3Amerged)

**Rust & Linux ecosystem**

- [wuwa-downloader](https://github.com/yuhkix/wuwa-downloader/pull/8)：Tokio 有界并发、断点续传与网络重试文件保留。
- [we-layerd](https://github.com/Aromatic05/we-layerd/pull/7)：增加 Gamescope 无头显示隔离。
- [rust-genai](https://github.com/jeremychone/rust-genai/pull/108)：修复 Ollama 推理流解析。

### 🛠 Tech Stack

**Languages**  
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-262626?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**OS**  
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)

**Cloud Native & Automation**  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**CI/CD & GitOps**  
![Concourse](https://img.shields.io/badge/Concourse-3398DC?style=flat-square&logo=concourse&logoColor=white)
![Harbor](https://img.shields.io/badge/Harbor-60B932?style=flat-square&logo=harbor&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**Data & Storage**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Longhorn](https://img.shields.io/badge/Longhorn-5B69BC?style=flat-square)

**Observability**  
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

### 📄 Research & Side Projects

- **ICASSP 2026 第一作者**：隐私保护感知哈希与零知识相似度验证，基于 Rust 实现。[Paper](https://doi.org/10.1109/ICASSP55912.2026.11461525) · [Code](https://github.com/mengdehong/zkph)
- **[AnimeShelf](https://github.com/mengdehong/AnimeShelf)**：使用 Flutter 开发的本地优先番剧记录与分级管理应用。

---

<p align="center">Go / Rust · Linux · Reliable Systems</p>
