# 📅 Roadmap de Desenvolvimento — MVP

Este documento descreve o planejamento de desenvolvimento do Produto Mínimo Viável (MVP), estruturado em **sprints de 2 semanas**, com base no *Service Blueprint*, nos requisitos técnicos e nas boas práticas de desenvolvimento ágil.

A estratégia segue o ciclo **Construir → Medir → Aprender**, priorizando funcionalidades essenciais e validação com dados reais desde o início.

---

# 🧭 Visão Geral das Sprints

| Sprint   | Foco                 | Resultado Principal                         |
| -------- | -------------------- | ------------------------------------------- |
| Sprint 0 | Fundação             | Infraestrutura, arquitetura e design        |
| Sprint 1 | Onboarding           | Cadastro seguro e validação institucional   |
| Sprint 2 | Perfil & Privacidade | Perfil acadêmico e controle de visibilidade |
| Sprint 3 | Busca & Conexões     | Matching e convites                         |
| Sprint 4 | Feed                 | Interação social                            |
| Sprint 5 | Mensageria           | Comunicação e grupos                        |
| Sprint 6 | Lançamento           | Testes, métricas e go-live                  |

---

# 🚀 Sprint 0 — Fundação, Arquitetura e UX/UI

## 🎯 Objetivo

Preparar a base tecnológica e a experiência do usuário antes do desenvolvimento funcional.

## 🧱 Back-end & Infra

* Arquitetura SOA / Microsserviços
* Banco de dados multi-tenant

## 🎨 Front-end & UX

* Protótipos de alta fidelidade
* Definição do fluxo do usuário
* App estruturado como **Thin Client**

---

# 🏃 Sprint 1 — Onboarding e Validação

## 🎯 Objetivo

Permitir criação de conta segura com e-mail institucional.

## ⚙️ Funcionalidades

* Captura de e-mail institucional
* Identificação automática de domínio
* Magic Link ou OTP

## 🔐 Compliance (LGPD)

* Consentimento explícito antes do cadastro

---

# 🛡️ Sprint 2 — Perfil e Privacidade

## 🎯 Objetivo

Criar identidade acadêmica e controles de visibilidade.

## ⚙️ Funcionalidades

* CRUD do perfil
* Curso, período, habilidades e interesses
* Sem métricas competitivas

## 🔐 Compliance

* Privacy Masking
* Pseudonimização de dados

---

# 🔍 Sprint 3 — Busca e Conexões

## 🎯 Objetivo

Permitir descoberta e conexão entre usuários.

## ⚙️ Funcionalidades

* Busca avançada com filtros
* Solicitações de conexão
* Notificações push

---

# 📰 Sprint 4 — Feed Bimodal

## 🎯 Objetivo

Disponibilizar interação social assíncrona.

## ⚙️ Funcionalidades

* Postagens e interações
* Alternância entre:

  * Feed local
  * Feed global

## 🏗 Infra

* Cache distribuído
* Tempo de resposta alvo < 2s

---

# 💬 Sprint 5 — Mensageria e Grupos

## 🎯 Objetivo

Habilitar colaboração em tempo real.

## ⚙️ Funcionalidades

* Chat 1:1
* Grupos de estudo
* Upload de arquivos assíncrono

## ⚠️ Riscos

* Alertas de direitos autorais

---

# 🎯 Sprint 6 — Testes e Lançamento

## 🎯 Objetivo

Garantir estabilidade e liberar o MVP.

## 🧪 Testes

* Testes de carga
* Auditoria de segurança e LGPD

## 📊 Métricas

* Projetos validados
* Conversão para grupos ativos

---

# 🧪 Práticas Recomendadas

## ✅ Test-Driven Development (TDD)

Garantir qualidade e estabilidade desde o início.

## 🎯 Foco no “Viável”

A funcionalidade central (conexões interuniversitárias) deve funcionar perfeitamente para considerar o MVP pronto.

---

