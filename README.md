## Olá, eu sou o Yuri 👋

**Platform Engineer · Kubernetes & OpenShift · SRE** — São Paulo, Brasil

🌎 Aberto a oportunidades remotas.

Tenho 13 anos de carreira. Passei 10 deles em redes, Linux, virtualização, firewalls e monitoração, e os últimos 3 em plataforma, operando aplicações em Kubernetes e OpenShift em produção.

No dia a dia escrevo os próprios manifestos, mantenho esteiras GitOps que criei do zero (Tekton e ArgoCD) e faço a análise de causa raiz quando algo quebra. Meu diferencial é conhecer bem a infraestrutura onde a aplicação roda (rede, DNS, storage e firewall), o que me deixa diagnosticar um problema da aplicação até a camada de rede.

### 🛠️ O que eu uso

| Área | Ferramentas |
| :--- | :--- |
| Plataforma & containers | Kubernetes, OpenShift, Docker |
| CI/CD & GitOps | ArgoCD, Tekton, GitLab CI |
| Dados | PostgreSQL com Patroni e Citus (failover, replicação, backup) |
| Observabilidade | Zabbix, Grafana |
| Infraestrutura & redes | Linux, roteamento (OSPF, BGP), VLAN, DNS, VPN, firewalls (Fortigate, Sophos, pfSense), VMware |
| Automação | Python, Shell |

### 📚 Estudando agora

Terraform · AWS · Go

### 🚀 No ar

| Projeto | O que é | Stack |
| :--- | :--- | :--- |
| [**Dusk Tracker**](https://dusktracker.yurisena.com.br) | Calculadora de forja, matriz de drops e inventário de materiais para Perfect World Clássico | JavaScript puro, Cloudflare Pages + Functions |
| **Gestão para restaurantes** *(piloto fechado)* | O gestor fala, o sistema organiza. Transforma o dia a dia da equipe em indicadores para decidir melhor | TypeScript, Cloudflare Workers, SQLite, IA |

### 🧩 Outros projetos

| Projeto | O que é | Stack |
| :--- | :--- | :--- |
| **Kemet** | Framework multiagente que criei para desenvolver software com IA: 13 agentes com papéis definidos (produto, requisitos, arquitetura, dev, QA, segurança e deploy), guardrails de governança, desenvolvimento guiado por especificação e memória de projeto que funciona com qualquer modelo. É com ele que construo os projetos acima | Claude, Gemini, GPT, Python |
| **FiscalDeTask** | Bot de Telegram que sincroniza com o Google Agenda, avisa na hora de cada compromisso e cobra até a tarefa ser feita (soneca, resumo diário, estatísticas) | Python, SQLite, Google Calendar API |
| [**ytb-disable-numpad-shortcuts**](https://github.com/YuriSenaTech/ytb-disable-numpad-shortcuts) | Extensão do Chrome que bloqueia os atalhos numéricos do YouTube | JavaScript, Chrome Extension |

### 🚧 Construindo

**telemetry-platform**: plataforma de ingestão de métricas e eventos de observabilidade. Tem uma API em Go e grava num PostgreSQL + Citus distribuído e particionado. Os mesmos manifests Kubernetes rodam num cluster local com GitOps (ArgoCD, Citus + Patroni em HA) e num EKS provisionado por Terraform. *Repositórios públicos em breve.*

### 📫 Contato

[LinkedIn](https://www.linkedin.com/in/yurissenas) · yurisenatech@gmail.com

---

<details>
<summary>🇺🇸 English</summary>

### Hi, I'm Yuri 👋

**Platform Engineer · Kubernetes & OpenShift · SRE** — São Paulo, Brazil · 🌎 Open to remote opportunities.

I have 13 years in tech. I spent 10 of them in networking, Linux, virtualization, firewalls and monitoring, and the last 3 in platform engineering, running applications on Kubernetes and OpenShift in production.

I write my own manifests, maintain GitOps pipelines I built from scratch (Tekton and ArgoCD), and do root cause analysis when things break. My edge is knowing the infrastructure the application runs on (network, DNS, storage, firewall), so I can troubleshoot from the app down to the network layer.

**Tools:** Kubernetes, OpenShift, Docker · ArgoCD, Tekton, GitLab CI · PostgreSQL with Patroni and Citus (failover, replication, backup) · Zabbix, Grafana · Linux, routing (OSPF, BGP), VLAN, DNS, VPN, firewalls (Fortigate, Sophos, pfSense), VMware · Python, Shell

**Currently learning:** Terraform · AWS · Go

**Live:**

| Project | What it is | Stack |
| :--- | :--- | :--- |
| [**Dusk Tracker**](https://dusktracker.yurisena.com.br) | Forge calculator, drop matrix and material inventory for Perfect World Classic | Vanilla JS, Cloudflare Pages + Functions |
| **Restaurant management** *(closed pilot)* | The manager talks, the system organizes it and turns the team's day-to-day into indicators for better decisions | TypeScript, Cloudflare Workers, SQLite, AI |

**Other projects:**

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **Kemet** | Multi-agent framework I created for AI-assisted software development: 13 agents with defined roles (product, requirements, architecture, dev, QA, security and deploy), governance guardrails, spec-driven development and a model-agnostic project memory. It's how I build the projects above | Claude, Gemini, GPT, Python |
| **FiscalDeTask** | Telegram bot that syncs with Google Calendar, alerts at each appointment and keeps nudging until the task is done (snooze, daily summary, stats) | Python, SQLite, Google Calendar API |
| [**ytb-disable-numpad-shortcuts**](https://github.com/YuriSenaTech/ytb-disable-numpad-shortcuts) | Chrome extension that blocks YouTube's number-key shortcuts | JavaScript, Chrome Extension |

**Building:** *telemetry-platform*, an observability ingestion platform. It has a Go API backed by a distributed, partitioned PostgreSQL + Citus. The same Kubernetes manifests run on a local GitOps cluster (ArgoCD, Citus + Patroni HA) and on an EKS cluster provisioned with Terraform. *Public repositories coming soon.*

</details>
