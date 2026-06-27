# ⚡ n8n Portfolio — 193 Workflows de Automação

[![Workflows](https://img.shields.io/badge/Workflows-193-00C853?style=for-the-badge&logo=n8n&logoColor=white)](https://github.com/RaulTecRox/n8n-portfolio)
[![Ativos](https://img.shields.io/badge/Ativos-58-success?style=for-the-badge)]()
[![Categorias](https://img.shields.io/badge/Categorias-14-blue?style=for-the-badge)]()
[![Self-hosted](https://img.shields.io/badge/Self--hosted-Proxmox-FF6F00?style=for-the-badge)]()

---

**193 workflows de produção** construídos com [n8n](https://n8n.io), rodando 24/7 em infraestrutura própria.

> 🏢 Todos os workflows são usados em produção na **MDG Intermediações** — automação real, não demo.

## 📊 Estatísticas

| Métrica | Valor |
|---------|-------|
| Workflows totais | 193 |
| Workflows ativos | 58 |
| Categorias | 14 |
| Infra | Proxmox + Docker + PostgreSQL + Redis |
| Período | 18 meses de operação contínua |

## 📁 Categorias

| | Categoria | Descrição | Workflows |
|---|-----------|-----------|:---:|
| 🏦 | **Saque Complementar** | Integração BMG, simulações, digitação, status de contratos | 22 |
| 📞 | **Comercial** | Acompanhamento, higienização de dados, backoffice | 18 |
| 🔐 | **Gestão de Acesso** | Provisionamento AD/Google/Agilus, bloqueio WiFi, relatórios RH | 15 |
| 📊 | **Relatórios** | Automatizados: produção, equipamentos, usuários | 20 |
| 🤖 | **IA** | Agentes inteligentes, transcrição de áudio, automação com LLM | 12 |
| 💬 | **SMS / WhatsApp** | Disparos em massa, notificações, campanhas | 18 |
| 🔄 | **Agilus** | Integração ERP: cadastro, consultas, margens | 16 |
| 📑 | **Precatório** | Higienização dados previdenciários, IN100, Dataprev | 14 |
| 🛠️ | **Ferramentas** | Conversão XML/JSON, imagem→texto, consultas | 10 |
| 🎬 | **TecRox** | Automação redes sociais, vídeos UGC | 8 |
| 🏗️ | **NoCode Startup** | Templates, proxies de API, agentes de voz | 6 |
| 🧠 | **Agentes de IA** | Orquestração de agentes autônomos | 8 |
| 💳 | **Financeiro** | Conciliação, boletos, cobrança | 12 |
| 🏥 | **Benefícios** | Portabilidade, consignado, INSS | 14 |

## 🔧 Stack Técnica

```
Orquestrador     → n8n (self-hosted Docker)
Banco de dados   → PostgreSQL + Redis
Mensageria       → Evolution API + WhatsApp Cloud API
Infra            → Proxmox VMs + Docker Swarm + PM2
APIs integradas  → BMG, Dataprev, Google Workspace, AD, Unifi, GLPI
Busca vetorial   → Qdrant
IA               → OpenAI, Gemini, Whisper (transcrição)
```

## 🏗️ Infraestrutura

```
                    ┌─────────────────────┐
                    │   Proxmox VE        │
                    │   (3 nós)           │
                    └──────┬──────────────┘
                           │
         ┌─────────────────┼─────────────────┐
         ▼                 ▼                 ▼
   ┌──────────┐     ┌──────────┐     ┌──────────┐
   │ n8n      │     │ Postgres │     │ Redis    │
   │ (Docker) │     │ (Docker) │     │ (Docker) │
   └──────────┘     └──────────┘     └──────────┘
         │
         ▼
   ┌──────────┐     ┌──────────┐     ┌──────────┐
   │ Evolution│     │ Agilus   │     │ Google   │
   │ API      │     │ ERP      │     │ Workspace│
   └──────────┘     └──────────┘     └──────────┘
```

## 🚀 Como usar

Cada arquivo `.json` na pasta da categoria é um workflow exportado do n8n:

1. Acesse seu n8n → **Settings** → **Import from file**
2. Selecione o workflow desejado
3. Configure as credenciais (Apis, Banco, etc.)
4. Ative e monitore

> ⚠️ Alguns workflows dependem de APIs internas (Agilus, AD, Unifi) que só funcionam na rede local.

## 🌐 Portfólio Visual

Abra o [`index.html`](./index.html) para uma versão navegável do portfólio com busca e filtros por categoria.

## 📬 Contato

- 💼 **LinkedIn:** [linkedin.com/in/raulguimaraes](https://linkedin.com/in/raulguimaraes)
- 🐦 **Telegram:** @Jesuisrox
- 📧 **E-mail:** raul@mdgintermediacoes.com.br

---

<div align="center">
  <sub>Exportado em 2026-06-22 · 193 workflows · 58 ativos · 14 categorias</sub>
</div>
