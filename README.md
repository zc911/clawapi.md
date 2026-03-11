# clawapi.md - Claw生态统一API网关

## 项目介绍
clawapi.md是Claw生态的统一API入口，为所有Claw产品提供对外API服务，包括：
- Agent API（agentos.md/agentx.md）
- VLM API（vlm.md）
- Chat API（chatapi.md）
- Skill API（clawhub.md）
- 更多生态API服务

## 核心特性
- 🚀 **低延迟**：边缘节点部署，全球访问加速
- 🛡️ **高可用**：99.9%可用性保障，多机房冗余
- 💰 **按量付费**：按实际调用量付费，无最低消费
- 🔒 **安全可靠**：统一鉴权、限流、风控
- 📊 **完善监控**：实时调用统计、错误分析、性能监控

## 技术栈
- 网关：APISIX/Kong
- 认证：JWT/OAuth2
- 监控：Prometheus/Grafana
- 计费：自研计费系统
- 文档：VitePress

## 项目结构
```
clawapi.md/
├── gateway/          # 网关配置
├── docs/             # 文档站点
├── developer-portal/ # 开发者平台
├── billing/          # 计费系统
├── monitor/          # 监控系统
└── README.md
```

## 快速开始
[访问官方文档](https://clawapi.md) 获取详细使用说明。

## 联系我们
开发者支持：support@clawapi.md
