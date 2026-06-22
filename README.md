# ⚡ Portfólio de Automações — n8n

**193 workflows** construídos com [n8n](https://n8n.io), cobrindo automação de ponta a ponta.

## 📊 Estatísticas

| Métrica | Valor |
|---------|-------|
| Workflows totais | 193 |
| Workflows ativos | 58 |
| Categorias | 14 |

## 📁 Categorias

| Categoria | Descrição |
|-----------|-----------|
| 🏦 **Saque Complementar** | Integração BMG, simulações, digitação, status de contratos |
| 📞 **Comercial** | Acompanhamento, higienização de dados, backoffice comercial |
| 🔐 **Gestão de Acesso** | Provisionamento AD/Google/Agilus, bloqueio WiFi, relatórios RH |
| 📊 **Relatório** | Relatórios automatizados para produção, equipamentos, usuários |
| 🤖 **IA** | Agentes de IA, transcrição de áudio, automação inteligente |
| 💬 **SMS / WhatsApp** | Disparos em massa, notificações, campanhas |
| 🔄 **Agilus** | Integração com ERP: cadastro, consultas, margens |
| 📑 **Precatório** | Higienização de dados previdenciários, IN100, Dataprev |
| 🛠️ **Ferramentas** | Utilidades: conversão XML/JSON, imagem→texto, consultas |
| 🎬 **TecRox** | Automação de redes sociais, vídeos UGC |
| 🏗️ **NoCode Startup** | Templates, agentes de voz, proxies de API |
| 🧠 **Negócio com Agentes de IA** | Orquestração de agentes autônomos |

## 🔧 Stack Técnica

- **n8n** (self-hosted Docker) — orquestrador de workflows
- **PostgreSQL** — persistência e dados de negócio
- **Evolution API** — envio/recebimento WhatsApp
- **APIs externas**: BMG, Dataprev, Google Workspace, Active Directory, Unifi, GLPI, Qdrant

## 🖥️ Infra

100% self-hosted em VMs Proxmox com PostgreSQL, Redis, Qdrant e Docker Swarm.

## 📂 Como usar

Cada arquivo `.json` na pasta da categoria é um workflow exportado do n8n. Importe no seu n8n: Settings → Import from file.

## 🌐 Portfólio Online

Abra [`index.html`](./index.html) para ver o portfólio visual.

---

Exportado em 2026-06-22 · 193 workflows · 58 ativos · 14 categorias
