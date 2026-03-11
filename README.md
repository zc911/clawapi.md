# clawapi.md - Unified API Gateway for Claw Ecosystem

## About
clawapi.md is the unified API entry point for the Claw ecosystem, providing external API services for all Claw products, including:
- Agent API (agentos.md/agentx.md)
- VLM API (vlm.md)
- Chat API (chatapi.md)
- Skill API (clawhub.md)
- And more ecosystem API services

## Core Features
- 🚀 **Low Latency**: Edge node deployment, global access acceleration
- 🛡️ **High Availability**: 99.9% uptime SLA, multi-data center redundancy
- 💰 **Pay-as-you-go**: Pay only for actual usage, no minimum consumption
- 🔒 **Secure & Reliable**: Unified authentication, rate limiting, risk control
- 📊 **Comprehensive Monitoring**: Real-time call statistics, error analysis, performance monitoring

## Tech Stack
- Gateway: APISIX/Kong
- Authentication: JWT/OAuth2
- Monitoring: Prometheus/Grafana
- Billing: Self-developed billing system
- Documentation: VitePress

## Project Structure
```
clawapi.md/
├── gateway/          # Gateway configuration
├── docs/             # Documentation site
├── developer-portal/ # Developer platform
├── billing/          # Billing system
├── monitor/          # Monitoring system
└── README.md
```

## Quick Start
Visit [https://clawapi.md](https://clawapi.md) for detailed documentation.

## Contact
Developer Support: [zack.mm.chen@gmail.com](mailto:zack.mm.chen@gmail.com)
