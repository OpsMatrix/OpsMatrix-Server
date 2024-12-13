---

# **Foundry - 一站式 DevOps 运维平台**

![GitHub stars](https://img.shields.io/github/stars/OpsMatrix/foundry?style=social)
![GitHub forks](https://img.shields.io/github/forks/OpsMatrix/foundry?style=social)
![GitHub issues](https://img.shields.io/github/issues/OpsMatrix/foundry)
![GitHub license](https://img.shields.io/github/license/OpsMatrix/foundry)

---

## **项目简介**

**Foundry** 是一个开源的 DevOps 运维平台，旨在为开发者和运维团队提供一站式的工具和服务，涵盖 CI/CD、私有化部署、资产管理以及运维小工具等功能。通过 Foundry，用户可以轻松实现自动化运维、高效管理资源，并提升开发和部署的效率。

---

## **核心功能**

### 1. **CI/CD 流水线**
- 支持多种 CI/CD 工具集成（如 Jenkins、GitLab CI、GitHub Actions）。
- 提供可视化的流水线配置界面，简化部署流程。
- 支持多环境部署（开发、测试、生产）。

### 2. **私有化部署**
- 支持一键部署到私有云或本地环境。
- 提供 Docker 和 Kubernetes 的集成，方便容器化部署。
- 支持 Helm Chart 管理，简化 Kubernetes 应用的部署。
- 支持离线部署 kubernetes 集群和业务环境。

### 3. **资产管理**
- 集中管理服务器、数据库、网络设备等资源。
- 提供资源监控和告警功能，实时掌握资源状态。
- 支持资源权限管理，确保数据安全。

### 4. **监控管理**
- 通过代理程序实时上传各个私有化环境监控数据，集中管理展示。
- 支持配置告警规则，实时感知服务状态。


### 4. **运维小工具**
- 提供常用运维工具，如日志分析、性能监控、故障排查等。
- 支持自定义脚本和插件，满足个性化需求。
- 提供 API 接口，方便与其他系统集成。

---

## **技术栈**

- **前端**：Vue.js
- **后端**：Go
- **数据库**：PostgreSQL
- **容器化**：Docker
- **集群管理**：Kubernetes
- **CI/CD**：Jenkins / GitLab CI / GitHub Actions
- **监控**：Prometheus / Grafana

---

## **快速开始**

### **1. 环境准备**
- 安装 Docker 和 Docker Compose。
- 确保系统已安装 Go 1.23。

### **2. 克隆项目**
```bash
git clone https://github.com/OpsMatrix/foundry.git
cd foundry
```

### **3. 启动服务**
```bash
# 使用 Docker Compose 启动
docker-compose up -d
```

### **4. 访问平台**
- 打开浏览器，访问 `http://localhost:8080`。

---

## **文档与教程**

- [用户手册](docs/user-guide.md)
- [开发者指南](docs/developer-guide.md)
- [API 文档](docs/api.md)

---

## **贡献指南**

我们非常欢迎社区的贡献！如果你有兴趣参与项目开发，请参考以下步骤：

1. **Fork 项目**：点击右上角的 `Fork` 按钮，将项目克隆到你的 GitHub 仓库。
2. **创建分支**：基于 `main` 分支创建一个新的功能分支。
3. **提交代码**：完成开发后，提交 Pull Request 到主仓库。
4. **代码审查**：等待社区成员进行代码审查，并根据反馈进行修改。
5. **合并代码**：代码审查通过后，你的代码将被合并到主分支。

更多详细信息，请参考 [贡献指南](CONTRIBUTING.md)。

---

## **社区与支持**

- **问题反馈**：如果你在使用过程中遇到问题，请在 [Issues](https://github.com/OpsMatrix/foundry/issues) 中提交问题。
- **讨论区**：加入我们的 [Discussions](https://github.com/OpsMatrix/foundry/discussions) 参与讨论。

---

## **许可证**

本项目采用 [Apache-2.0 许可证](https://img.shields.io/github/license/OpsMatrix/foundry) 进行开源。

---

## **鸣谢**

感谢以下开源项目和社区的支持：
- [Docker](https://www.docker.com/)
- [Kubernetes](https://kubernetes.io/)
- [Jenkins](https://www.jenkins.io/)
- [Prometheus](https://prometheus.io/)
- [Grafana](https://grafana.com/)
- [soybean-admin](https://github.com/soybeanjs/soybean-admin)
---

## **联系我们**

如果你有任何问题或建议，欢迎通过以下方式联系我们：
- 邮箱：[xiamingyu_shuai@163.com](xiamingyu_shuai@163.com)

---

**foundry** 是一个由社区驱动的开源项目，我们期待你的加入！

---
