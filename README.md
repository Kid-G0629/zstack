<p align="center">
  <a href="https://zstack.org">
    <img src="images/logo.png" alt="ZStack" width="200">
  </a>
</p>

<p align="center">
  <b>Open source IaaS software - 5 minutes for POC, 30 minutes for production</b>
</p>

> **If you need to keep AI training data private, you need your own IaaS. ZStack makes it free and simple.**

[English](README.md) | [中文](README.zh-CN.md)

---

## What is ZStack?

ZStack is open source IaaS (infrastructure as a service) software that automates datacenter management through APIs,
controlling compute, storage, and networking resources.

Users can set up a POC environment in **5 minutes** on a single Linux machine, or build a production environment
in **30 minutes** that scales to hundreds of thousands of physical servers.

## Why ZStack?

### 🌀 Extremely Scalable

A single management node manages **hundreds of thousands** of physical servers, **millions** of VMs,
and handles **tens of thousands** of concurrent API requests.

### ⚡ High Performance

VM creation performance:

| VM Count | Time    |
|----------|----------|
| 1        | 0.51s    |
| 10       | 1.55s    |
| 100      | 11.33s   |
| 1000     | 103s     |

### 🔧 Full Automation

- **API-driven**: All resources managed via APIs, no manual configuration
- **No dependencies**: No third-party software needed, ZStack includes everything
- **Self-healing**: Built-in HA, no external monitoring required

### 🔌 Flexible Plugin System

Core orchestration built on a plugin architecture - adding or removing features won't impact the core system,
ensuring long-term stability.

### 🔍 Powerful Query API

Supports approximately **4 million** query conditions and countless combinations.

## Quick Start

### Docker One-liner

```bash
wget -O install.sh https://zstack.org/install.sh
bash install.sh
```

Or use Docker directly:

```bash
docker run -d -p 8080:8080 -v /opt/zstack:/opt/zstack zstack/zstack:latest
```

### Links

- [Product Download (CN)](https://www.zstack.io/product/product_downloads/)
- [Product Download (EN)](https://www.zstack-cloud.com/product/product_downloads/)
- [Quick Installation Guide](https://www.zstack-cloud.com/help/en/tutorials/quick_install_guide/v4/)
- [Manual Installation Guide](https://zstack.org/installation/manual.html)

## Features

<details>
<summary><b>🧩 Extensible Architecture</b></summary>

Single management node supports large-scale clusters with unlimited horizontal scaling.
</details>

<details>
<summary><b>🌐 Network Functions Virtualization</b></summary>

NFV-based default networking model provides dedicated virtual network devices for each tenant,
no special hardware required.
</details>

<details>
<summary><b>📦 App Store</b></summary>

Application template library for one-click deployment of common applications and services.
</details>

<details>
<summary><b>🔒 Multi-Tenant Security</b></summary>

Complete role-based access control with enterprise-grade multi-tenant isolation.
</details>

<details>
<summary><b>💾 Storage Solutions</b></summary>

Supports multiple storage backends: Local, NFS, Ceph, GlusterFS and more.
</details>

<details>
<summary><b>🧪 Automated Testing</b></summary>

Three-layer automated testing system ensures quality for every feature.
</details>

## Documentation

- [ZStack Documentation](https://www.zstack-cloud.com/help/en/product_manuals/index.html)
- [Architecture Articles](https://zstack.org/blog/)
- [Tutorials](https://www.zstack-cloud.com/help/en/tutorials/)

## License

Apache License 2.0 - see [LICENSE](LICENSE)

---

<p align="center">
  <sub>Built with ❤️ by the ZStack community</sub>
</p>
