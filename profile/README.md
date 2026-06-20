# Feedback Analytics

Este é um sistema de software desenvolvido como uma solução tecnológica integrada para a gestão, processamento e análise inteligente de feedbacks de clientes. 

O projeto adota metodologias ágeis, engenharia de software rigorosa e uma arquitetura moderna orientada a componentes e serviços.

---

### Diferenciais Técnicos
* **Arquitetura Monorepo:** Centralização do código (Frontend, Backend, IA e Infraestrutura) para consistência de deploys e versionamento.
* **Inteligência Semântica:** Integração com Large Language Models (LLMs) para análise de sentimentos e injeção automatizada de metadados.
* **Qualidade de Software:** Portões de qualidade estruturados via CI/CD, validação estrita de tipos, linters e testes automatizados (unitários e de integração).

---

### Nosso Time 


| Integrante | Papel Principal | Foco Técnico |
| :--- | :--- | :--- |
| **Clara Luz Lopes** | Product Owner & AI | Engenharia de Prompts (Google Gemini API), Estruturação de Dados e Gestão do Backlog |
| **Fernando Sérgio** | Backend Engineer | APIs Restful (Express), Regras de Negócio, Conexão e Migrations |
| **Rachel Alves** | DevOps & QA | Esteiras de CI/CD (GitHub Actions), Qualidade de Código (Vitest + Playwright) e Deploys (Vercel) |
| **Vinicius dos Santos** | Frontend Engineer | SPA/Web Client (React 19 + Vite), Estado da Aplicação, UI/UX Consistente |

Professor Orientador: Wosney Ramos de Souza

---

### Stack Tecnológica Geral

* **Frontend:** React 19 (TypeScript) + Vite + Tailwind CSS 4.x
* **Backend:** Node.js (TypeScript) + Express
* **Banco de Dados:** PostgreSQL (Supabase) 
* **IA/Analytics:** Google Gemini API 
* **CI/CD & Infra:** GitHub Actions, Vercel Serverless Functions, Supabase

---

### Governança e Processo de Desenvolvimento

Para garantir a evolução sustentável adotamos políticas de maturação de código:

1. **Gestão de Demandas:** Centralizada no **GitHub Projects** utilizando fluxos Kanban divididos por *Milestones* de entrega.
2. **Estratégia de Branching:** Uso de branches efêmeras (`feature/*`, `fix/*`) derivadas de uma branch de integração (`homolog`). Commits diretos na `main` são bloqueados por Rulesets.
3. **Quality Gates:** Todo Pull Request dispara uma esteira automatizada no **GitHub Actions** que valida:
   * Formatação de Código (Linter)
   * Suíte de Testes (Unitários/Integration)
   * Build de Produção
4. **Revisão por Pares:** Nenhum código é integrado sem a aprovação de pelo menos um outro engenheiro do time após o *Code Review*.

---

<p align="center">
  <small>Organização acadêmica voltada à pesquisa aplicada e desenvolvimento de software. 2026.</small>
</p>

---
