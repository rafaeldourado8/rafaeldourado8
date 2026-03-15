<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:0d1f2d,100:0a2a1f&height=120&section=header" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&size=13&duration=3000&pause=800&color=4A9EFF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=60&lines=Backend+Engineer+%C2%B7+Distributed+Systems+%C2%B7+Intelligent+Systems;Dourados+%E2%80%93+MS%2C+Brasil" alt="Typing SVG" />

<br/>

# Rafael Dourado

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1f2d?style=for-the-badge&logo=linkedin&logoColor=4a9eff)](https://linkedin.com/in/rafael-dourado-dev)
[![GitHub](https://img.shields.io/badge/GitHub-0a0a0a?style=for-the-badge&logo=github&logoColor=e8e6df)](https://github.com/rafaeldourado8)
[![Email](https://img.shields.io/badge/rafaeldouradoc7%40gmail.com-0a0a0a?style=for-the-badge&logo=gmail&logoColor=4a9eff)](mailto:rafaeldouradoc7@gmail.com)

</div>

---

<div align="center">

```
Construo sistemas backend que precisam ser rápidos, corretos e resilientes.
Foco na interseção entre arquitetura de software e inteligência aplicada —
desde pipelines de RAG até processamento de vídeo com YOLOv8 em tempo real.

Penso em sistemas antes de escrever código.
Estimo capacidade. Modelo dados. Só então implemento.
```

</div>

---

## 🔭 Projeto Atual — GT-Vision VMS com IA

> **Video Management System** white-label, self-hosted, multi-tenant com analytics modular.  
> Financiado pelo **Grupo Trajano** · Em produção

```python
class GTVision:
    stack     = ["Django", "FastAPI", "MediaMTX", "RabbitMQ", "Redis", "PostgreSQL", "YOLOv8"]
    infra     = ["Docker Compose", "Nginx", "AWS", "JWT Auth", "API Key Auth"]
    analytics = ["intrusion", "people_count", "vehicle_count", "lpr_parking", "weapon", "face_recognition"]

    def diferencial(self):
        return {
            "cameras_burras":       "RTSP → YOLOv8 → evento (bullet vira inteligente)",
            "cameras_inteligentes": "Hikvision/Intelbras ANPR → normaliza → persiste",
            "agent_local":          "NAT/CGNAT traversal via ffmpeg + polling com backoff",
            "event_bus":            "RabbitMQ topic exchange + Redis SSE realtime",
            "multitenancy":         "Isolamento completo por tenant em todas as queries",
        }
```

[![Django](https://img.shields.io/badge/Django-0d2b0d?style=flat-square&logo=django&logoColor=4caf70)](.)
[![FastAPI](https://img.shields.io/badge/FastAPI-0d2424?style=flat-square&logo=fastapi&logoColor=00d4aa)](.)
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-2d1a0d?style=flat-square&logo=rabbitmq&logoColor=FF6600)](.)
[![Redis](https://img.shields.io/badge/Redis-2d0d0d?style=flat-square&logo=redis&logoColor=ff4444)](.)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1a2d?style=flat-square&logo=postgresql&logoColor=4a9eff)](.)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-1a1a0d?style=flat-square&logo=pytorch&logoColor=EE4C2C)](.)
[![Docker](https://img.shields.io/badge/Docker-0d1a2d?style=flat-square&logo=docker&logoColor=4a9eff)](.)
[![AWS](https://img.shields.io/badge/AWS-1a1a0d?style=flat-square&logo=amazonaws&logoColor=FF9900)](.)

---

## 🧠 Outros Projetos

| Projeto | Descrição | Stack |
|--------|-----------|-------|
| **StudyFlow** | RAG implementado do zero — embeddings, indexação vetorial, geração contextual | `FastAPI` `pgvector` `RAG` `Embeddings` |
| **SunOPS** | CRM para integradores solares com geração de relatórios automatizada | `Django` `FastAPI` `RabbitMQ` `Redis` |
| **Agente WhatsApp** | Backend com RAG empresarial para atendimento automatizado | `FastAPI` `Agents` `RAG` |
| **URLShorts** | Encurtador de URL projetado para alta escala | `Redis` `CassandraDB` |
| **Gateway de Pagamento** | Integração Mercado Pago com validação HMAC de webhooks | `.NET` `C#` |
| **Emissor NF-e** | Integração SEFAZ, XML fiscal, certificados digitais | `Java` `Spring` |

---

## ⚙️ Stack

<div align="center">

**Linguagens**

[![My Skills](https://skillicons.dev/icons?i=python,cs,java,go,ts)](.)

**Backend & Frameworks**

[![My Skills](https://skillicons.dev/icons?i=fastapi,django,dotnet,spring)](.)

**Dados & Infra**

[![My Skills](https://skillicons.dev/icons?i=postgres,redis,mongodb,docker,aws,nginx,linux)](.)

**ML / AI**

[![My Skills](https://skillicons.dev/icons?i=pytorch,opencv)](.)

</div>

---

## 🏗️ Como Penso Sobre Sistemas

```
┌─────────────────────────────────────────────────────────────┐
│  1. Requisitos funcionais     → o que o sistema faz         │
│  2. Requisitos não funcionais → latência, throughput, SLA   │
│  3. Estimativa de capacidade  → QPS, storage, bandwidth     │
│  4. Modelagem de dados        → entidades, índices, queries │
│  5. API Design                → contratos entre serviços    │
│  6. Arquitetura               → onde cada componente vive   │
└─────────────────────────────────────────────────────────────┘
```

![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-0d1a2d?style=flat-square&color=0d1a2d&labelColor=0d1a2d&logo=buffer&logoColor=4a9eff)
![DDD](https://img.shields.io/badge/Domain_Driven_Design-0d1a2d?style=flat-square&color=0d1a2d&labelColor=0d1a2d&logo=buffer&logoColor=4a9eff)
![SOLID](https://img.shields.io/badge/SOLID-0d1a2d?style=flat-square&color=0d1a2d&labelColor=0d1a2d&logo=buffer&logoColor=4a9eff)
![Event-Driven](https://img.shields.io/badge/Event--Driven-0d1a2d?style=flat-square&color=0d1a2d&labelColor=0d1a2d&logo=buffer&logoColor=4a9eff)
![CAP Theorem](https://img.shields.io/badge/CAP_Theorem-0d1a2d?style=flat-square&color=0d1a2d&labelColor=0d1a2d&logo=buffer&logoColor=4a9eff)
![Microsserviços](https://img.shields.io/badge/Microsservi%C3%A7os-0d1a2d?style=flat-square&color=0d1a2d&labelColor=0d1a2d&logo=buffer&logoColor=4a9eff)

---

## 📊 Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=rafaeldourado8&show_icons=true&theme=github_dark&bg_color=0a0a0a&border_color=1e1e1e&title_color=4a9eff&icon_color=4caf70&text_color=888888&count_private=true" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rafaeldourado8&layout=compact&theme=github_dark&bg_color=0a0a0a&border_color=1e1e1e&title_color=4a9eff&text_color=888888&langs_count=6" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a2a1f,50:0d1f2d,100:0a0a0a&height=80&section=footer" width="100%"/>

*"System Design é uma forma do arquiteto se expressar, se convencer e vender."*

</div>
