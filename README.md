<div align="center">

**[🇧🇷 Português](#-sobre-mim) · [🇺🇸 English](#-about-me)**

</div>

---

<a name="sobre-mim"></a>

# 🇧🇷 Português

## Olá, sou Diego Werlich 👋

Desenvolvedor Full Stack com 5+ anos de experiência construindo aplicações web robustas e plataformas SaaS. Na **LifeCode**, projeto e mantenho um sistema multi-tenant que atende câmaras municipais brasileiras.

Gosto de transformar requisitos complexos em código limpo e sustentável — e me importo tanto com infraestrutura e eficiência de custos quanto com o produto em si.

> 🌎 Santa Catarina, Brasil

---

## 🛠 Stack

**Backend:** PHP · Laravel · REST APIs · MySQL · Redis

**Frontend:** Vue.js 3 (Composition API) · Pinia · Vite · Axios

**Infra & Ferramentas:** AWS (EC2, RDS, S3) · Nginx · Docker · Git

---

## 📈 Destaques

- ⚡ Reduzi custos de infraestrutura AWS em **67%** com migração Apache → Nginx
- 🧠 Reduzi uso de RAM do servidor em **29%** via otimização de queries e configurações
- 🏛 Construí e mantenho uma plataforma **SaaS multi-tenant** usada por câmaras municipais em todo o Brasil
- 🔗 Integrei APIs governamentais brasileiras (SIOPS, CNES, DATASUS) e gateways de pagamento

---

## 💼 Projetos Profissionais

### 🏛 Sistema de Gestão Legislativa — LifeCode *(SaaS próprio, em produção)*
Plataforma multi-tenant completa para gestão de câmaras municipais brasileiras. Cada câmara tem seu ambiente isolado com controle total de dados e permissões.

- Autenticação segura via cookies HttpOnly (sem token exposto no frontend)
- Controle de acesso granular (RBAC) com permissões por módulo
- Gestão de proposições, plenárias, comissões e documentos legislativos
- Relatórios em PDF e Excel, notificações in-app e por e-mail
- Auditoria automática de todas as alterações do sistema
- Infraestrutura na AWS com alta disponibilidade

**Stack:** Laravel · Vue.js 3 · MySQL · AWS · Nginx · Sanctum

---

### 🛒 Integração E-commerce + Gateway de Pagamento *(Freela)*
Integração entre **NuvemShop** (plataforma de e-commerce) e **Asaas** (gateway de pagamentos brasileiro), automatizando o ciclo completo de pedidos e cobranças.

- Sincronização automática de pedidos NuvemShop → Asaas
- Geração de cobranças (boleto, PIX, cartão) a partir de eventos do e-commerce
- Webhooks bidirecionais para atualização de status em tempo real
- Tratamento de falhas, filas assíncronas e retry automático
- Painel administrativo para monitoramento das integrações

**Stack:** PHP 7 · Slim Framework · MySQL · Webhooks

---

### 🚑 Monitoramento de Dados de Saúde *(Projeto cliente)*
Sistema para coleta, processamento e visualização de dados de saúde pública, com integração às bases do governo federal (SIOPS, CNES, DATASUS).

- Importação e normalização automática de dados do Ministério da Saúde
- Dashboards com indicadores por município e estado
- Exportação de relatórios customizados em PDF e Excel
- Gestão de usuários com diferentes níveis de acesso

**Stack:** Laravel · Vue.js 3 · MySQL · DATASUS API · SIOPS · CNES

---

### 🚛 Sistema de Gestão de Frota *(Innovare TI)*
Plataforma para controle e monitoramento de frotas, com integrações corporativas.

- Rastreamento e histórico de veículos
- Gestão de manutenções preventivas e corretivas
- Integração com sistemas de segurança (Ellevo/Qualys)
- Relatórios gerenciais integrados com SAP

**Stack:** PHP · Laravel · Vue.js · MySQL · SAP Integration

---

### 💬 Integração WhatsApp Business *(Projeto cliente)*
Automação de comunicação via **WhatsApp Business API** para notificações e fluxos de mensagens.

- Envio automatizado de notificações transacionais
- Fluxos de conversa com respostas configuráveis
- Webhook para recebimento e processamento de mensagens
- Painel de monitoramento de disparos e status de entrega

**Stack:** Laravel · Vue.js · WhatsApp Business API · Webhooks

---

## 🚀 Projeto Open Source

### [setup-simplificado](https://github.com/dwerlich21/setup-simplificado)
Boilerplate full-stack para iniciar novos projetos rapidamente — Laravel 12 + Vue 3.

Inclui: autenticação via cookies HttpOnly, CRUD genérico com componentes base, permissões RBAC, auditoria automática, notificações, exportação PDF/Excel, Kanban, operações em massa e gerador de CRUD via script.

---

## 📬 Contato

- 💼 [LinkedIn](https://www.linkedin.com/in/diego-werlich/)
- 📧 dwerlich21@gmail.com

---
---

<a name="about-me"></a>

# 🇺🇸 English

## Hi, I'm Diego Werlich 👋

Full Stack Developer with 5+ years of experience building robust web applications and SaaS platforms. At **LifeCode**, I design and maintain a multi-tenant system serving Brazilian municipal governments.

I enjoy turning complex business requirements into clean, maintainable code — and I care as much about infrastructure and cost efficiency as I do about the product itself.

> 🌎 Based in Santa Catarina, Brazil

---

## 🛠 Tech Stack

**Backend:** PHP · Laravel · REST APIs · MySQL · Redis

**Frontend:** Vue.js 3 (Composition API) · Pinia · Vite · Axios

**Infrastructure & Tools:** AWS (EC2, RDS, S3) · Nginx · Docker · Git

---

## 📈 Highlights

- ⚡ Reduced AWS infrastructure costs by **67%** through Apache → Nginx migration
- 🧠 Reduced server RAM usage by **29%** via query and config optimization
- 🏛 Built and maintain a **multi-tenant SaaS** platform used by municipal chambers across Brazil
- 🔗 Integrated complex Brazilian government APIs (SIOPS, CNES, DATASUS) and payment gateways

---

## 💼 Professional Projects

### 🏛 Legislative Management System — LifeCode *(Proprietary SaaS, in production)*
Complete multi-tenant platform for managing Brazilian municipal chambers. Each chamber has its own isolated environment with full data and permission control.

- Secure authentication via HttpOnly cookies (no token exposed to the frontend)
- Granular access control (RBAC) with per-module permissions
- Management of bills, plenary sessions, committees and legislative documents
- PDF and Excel reports, in-app and email notifications
- Automatic audit logging of all system changes
- High-availability infrastructure on AWS

**Stack:** Laravel · Vue.js 3 · MySQL · AWS · Nginx · Sanctum

---

### 🛒 E-commerce + Payment Gateway Integration *(Freelance)*
Integration between **NuvemShop** (e-commerce platform) and **Asaas** (Brazilian payment gateway), automating the complete order and billing cycle.

- Automatic order sync from NuvemShop → Asaas
- Invoice generation (bank slip, PIX, credit card) triggered by e-commerce events
- Bidirectional webhooks for real-time status updates
- Failure handling, async queues and automatic retry
- Admin dashboard for monitoring integrations

**Stack:** PHP 7 · Slim Framework · MySQL · Webhooks

---

### 🚑 Healthcare Data Monitoring *(Client project)*
System for collecting, processing and visualizing public health data, integrated with Brazilian federal government databases (SIOPS, CNES, DATASUS).

- Automatic import and normalization of data from Ministry of Health APIs
- Dashboards with health indicators by city and state
- Custom report export in PDF and Excel
- User management with role-based access levels

**Stack:** Laravel · Vue.js 3 · MySQL · DATASUS API · SIOPS · CNES

---

### 🚛 Fleet Management System *(Innovare TI)*
Platform for vehicle fleet control and monitoring, with corporate system integrations.

- Vehicle tracking and history
- Preventive and corrective maintenance management
- Integration with security systems (Ellevo/Qualys)
- Management reports integrated with SAP

**Stack:** PHP · Laravel · Vue.js · MySQL · SAP Integration

---

### 💬 WhatsApp Business Integration *(Client project)*
Communication automation via **WhatsApp Business API** for notifications and automated message flows.

- Automated transactional notification dispatch
- Conversation flows with configurable responses
- Webhook for receiving and processing messages
- Monitoring dashboard for message status and delivery

**Stack:** Laravel · Vue.js · WhatsApp Business API · Webhooks

---

## 🚀 Open Source

### [setup-simplificado](https://github.com/dwerlich21/setup-simplificado)
Full-stack boilerplate to kickstart new projects quickly — Laravel 12 + Vue 3.

Includes: HttpOnly cookie auth, generic CRUD with base components, RBAC permissions, automatic audit logging, notifications, PDF/Excel export, Kanban, bulk operations and a CRUD generator script.

---

## 📬 Get in touch

- 💼 [LinkedIn](https://www.linkedin.com/in/diego-werlich/)
- 📧 dwerlich21@gmail.com
