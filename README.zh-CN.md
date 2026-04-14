<p align="center">
  <a href="https://zstack.org">
    <img src="images/logo.png" alt="ZStack" width="200">
  </a>
</p>

<p align="center">
  <b>开源 IaaS 软件 — 5 分钟搭建 POC，30 分钟搭建生产环境</b>
</p>

> **如果你的 AI 训练数据需要保密，你就需要自己的 IaaS。ZStack 让它免费又简单。**

---

## 什么是 ZStack?

ZStack 是开源的 IaaS（基础设施即服务）软件，通过 API 自动化管理数据中心的计算、存储和网络资源。

用户只需 **5 分钟** 即可在单台 Linux 机器上搭建 POC 环境，或在 **30 分钟** 内构建可扩展至数十万台物理服务器的生产环境。

## 为什么选择 ZStack?

### 🌀 极致弹性

单管理节点可管理 **数十万** 台物理服务器、**百万级** 虚拟机，支持 **万级** 并发 API 请求。

### ⚡ 高性能

虚拟机创建性能：

| VM 数量 | 耗时    |
|---------|----------|
| 1       | 0.51 秒  |
| 10      | 1.55 秒  |
| 100     | 11.33 秒 |
| 1000    | 103 秒   |

### 🔧 全自动化

- **API 驱动**：所有资源通过 API 管理，无需手动配置
- **无依赖安装**：无需安装额外软件，ZStack 自带所有组件
- **自愈服务**：内置 HA，无需第三方监控

### 🔌 灵活插件系统

核心编排基于插件架构，新增或移除功能不影响核心系统，确保长期稳定运行。

### 🔍 强大查询 API

支持约 **400 万** 种查询条件和无数查询组合，随时随地查询任何资源。

## 快速开始

### Docker 一键部署

```bash
wget -O install.sh https://zstack.org/install.sh
bash install.sh
```

或使用 Docker：

```bash
docker run -d -p 8080:8080 -v /opt/zstack:/opt/zstack zstack/zstack:latest
```

### 相关链接

- [产品下载 (中文)](https://www.zstack.io/product/product_downloads/)
- [产品下载 (英文)](https://www.zstack-cloud.com/product/product_downloads/)
- [快速安装指南](https://www.zstack-cloud.com/help/en/tutorials/quick_install_guide/v4/)
- [手动安装指南](https://zstack.org/installation/manual.html)

## 核心特性

<details>
<summary><b>🧩 可扩展架构</b></summary>

单管理节点支持大规模集群，无限水平扩展能力。
</details>

<details>
<summary><b>🌐 网络功能虚拟化</b></summary>

基于 NFV 的默认网络模型，为每个租户提供独立的虚拟网络设备，无需专用硬件。
</details>

<details>
<summary><b>📦 应用商店</b></summary>

提供应用模板库，一键部署常用应用和服务。
</details>

<details>
<summary><b>🔒 多租户安全</b></summary>

完善的角色权限控制，支持企业级多租户隔离。
</details>

<details>
<summary><b>💾 存储方案</b></summary>

支持多种存储后端：本地存储、NFS、Ceph、GlusterFS 等。
</details>

<details>
<summary><b>🧪 自动化测试</b></summary>

三层自动化测试系统，保障每个功能的质量。
</details>

## 文档

- [ZStack 官方文档](https://www.zstack-cloud.com/help/en/product_manuals/index.html)
- [架构设计文章](https://zstack.org/blog/)
- [教程](https://www.zstack-cloud.com/help/en/tutorials/)

## 许可证

Apache License 2.0 - 详见 [LICENSE](LICENSE)

---

<p align="center">
  <sub>由 ZStack 社区 ❤️ 构建</sub>
</p>
