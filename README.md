# landscape
Infrastructure as Code Landscape

## 项目简介
IaC Landscape 是一个展示和组织基础设施即代码（Infrastructure as Code, IaC）生态系统中各类工具和最佳实践的平台。该项目旨在帮助开发者和运维人员更好地理解和使用 IaC 工具，提高工作效率和安全性。

## 特性
- **工具分类**：将 IaC 相关工具按类别进行组织，方便用户查找。
- **最佳实践**：提供各类工具的使用指南和最佳实践，帮助用户更好地实施 IaC。
- **可视化**：通过可视化工具展示基础设施的依赖关系和状态，便于管理和监控。

## 工具分类
### 生态工具指南
基础设施即代码(IaC)生态系统中的各类工具使用指南和最佳实践。

#### DevOps工具链
- **版本控制与协作**：
  - GitHub Actions：云原生CI/CD自动化平台
  - GitLab：完整的DevOps平台
  - Jenkins：领先的开源自动化服务器
  - Azure DevOps：企业级开发协作平台
  - AWS CodePipeline：AWS的持续交付服务
  - Atlantis：Terraform PR自动化
  - 阿里云云效：阿里云一站式DevOps平台
  - 腾讯CODING：腾讯云DevOps研发管理平台

- **状态管理工具**：
  - Terraform Cloud：企业级状态管理
  - Spacelift：IaC管理平台
  - env0：多云IaC自动化平台

#### 安全工具链
- **安全扫描工具**：
  - Checkov：IaC安全扫描
  - tfsec：Terraform代码分析
  - Snyk IaC：基础设施代码扫描
  - Terrascan：多云配置审计
  - Semgrep：静态代码分析

- **策略管理与合规**：
  - HashiCorp Sentinel：策略即代码
  - Open Policy Agent：策略执行引擎
  - AWS Config：合规性检查
  - Azure Policy：云资源治理

- **密钥与访问管理**：
  - HashiCorp Vault：密钥管理平台
  - AWS Secrets Manager：密钥轮换与管理
  - Azure Key Vault：云密钥管理
  - GitGuardian：密钥检测与修复

#### 安全最佳实践
- **代码安全**：
  - 最小权限原则实施
  - 敏感信息加密存储
  - 基础设施版本控制
  - 代码审查流程

- **运行时安全**：
  - 资源访问控制
  - 网络安全配置
  - 日志审计追踪
  - 漏洞管理流程

#### 配置管理工具
- **自动化配置**：
  - Terraform：基础设施编排
  - Ansible：服务器配置管理
  - Puppet：基础设施自动化
  - Chef：配置自动化

- **云原生工具**：
  - AWS CloudFormation：AWS资源编排
  - Azure ARM：Azure资源管理
  - Google Cloud Deployment：GCP部署管理
  - Pulumi：多语言IaC支持

#### 可视化与监控
- **基础设施可视化**：
  - Terraform Graph：依赖关系图
  - Inframap：资源关系可视化
  - Blast Radius：Terraform分析
  - Brainboard：架构设计工具

- **成本管理**：
  - Infracost：Terraform成本预估
  - CloudHealth：多云成本管理
  - AWS Cost Explorer：AWS成本分析
  - Azure Cost Management：Azure成本优化

## 设置
在 `iac-landscape/settings.yml` 文件中，您可以自定义一些景观的设置，包括基础设施类型、URL 和颜色主题。

### 示例设置
```yaml
foundation: "Infrastructure as Code"
url: http://127.0.0.1:8000
colors:
  color1: "rgba(69, 39, 160, 1)"      # 深紫色
  color2: "rgba(25, 118, 210, 1)"     # 蓝色
  color3: "rgba(123, 31, 162, 1)"     # 紫色
  color4: "rgba(38, 50, 56, 1)"       # 深灰
  color5: "rgba(66, 165, 245, 0.8)"   # 淡蓝
  color6: "rgba(26, 35, 126, 0.7)"    # 深蓝
  color7: "rgba(236, 239, 241, 1)"    # 浅灰
```

## 快速开始
1. 克隆项目：
   ```bash
   git clone https://github.com/iac-landscape/landscape.git
   cd landscape
   ```

2. 安装依赖：
   ```bash
   # 根据项目需要安装依赖
   ```

3. 启动项目：
   ```bash
   # 启动项目的命令
   ```

## 贡献
欢迎任何形式的贡献！请查看 [贡献指南](CONTRIBUTING.md) 以获取更多信息。

## 许可证
该项目采用 Apache 许可证 2.0 版，详细信息请查看 [LICENSE](LICENSE) 文件。

## 联系我们
如有任何问题或建议，请通过以下方式与我们联系：
- GitHub: [iac-landscape](https://github.com/iac-landscape/landscape)
- WeChat: [wechat](https://kaliarch-bucket-1251990360.cos.ap-beijing.myqcloud.com/blog_img/20241224142657.png)
- homepage: "https://redhatxl.github.io/"
