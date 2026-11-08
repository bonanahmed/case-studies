# Case Studies by Adnan Ahmad

I build production systems where software meets physical operations: water infrastructure, industrial telemetry, and conversational AI connected to real equipment. Most of this work was done for clients through [Digibay](https://github.com/Digibay-Tech), so the source code is private.

These write-ups describe **the problems, the architecture, the decisions, and the results**. They contain no client source code, credentials, or confidential data. Client names are generalised. Code walkthroughs are available during interviews.

| Case study | What it shows | Stack |
|---|---|---|
| [AIRSO: irrigation water allocation](airso.md) | Domain-driven calculation engine, recovering a stalled project | TypeScript, Express, MongoDB, Next.js, SCADA data |
| [Utility telemetry platform](utility-telemetry.md) | Industrial integration, event-driven pipelines, multi-branch access control | Modbus, OPC UA, MQTT, Debezium CDC, Keycloak, PostgreSQL/MySQL/MongoDB |
| [AIVA: virtual human connected to live infrastructure](aiva.md) | Conversational avatar built in three days, SCADA API, allow-listed command triggers | ChatGPT (OpenAI API), ElevenLabs, Unreal Engine 5, MetaHuman, Node.js API |
| [Platform and infrastructure](platform-infrastructure.md) | IaC, keyless CI/CD, 71 services run at 99.97% uptime over a 12-month period | Terraform, AWS ECS Fargate, GitHub Actions OIDC, Proxmox, Grafana |

**Contact:** [adnan-ahmad.com](https://adnan-ahmad.com) · [LinkedIn](https://linkedin.com/in/bonanahmed)
