
# Feedback Analytics

Este é um sistema de software desenvolvido como uma solução tecnológica integrada para a coleta, gestão e análise inteligente de feedbacks de clientes. 

---

### Nosso Time 

| Integrante | Papel Principal | Foco Técnico |
| :--- | :--- | :--- |
| **Clara Luz Lopes** | Product Owner & AI |  Gestão ágil de Escopo, Priorização do Backlog, Engenharia de Prompts para LLMs |
| **Fernando Sérgio** | Backend Engineer | APIs Restful (Express), Regras de Negócio, Conexão e Migrations |
| **Rachel Alves** | DevOps & QA | Esteiras de CI/CD (GitHub Actions), Qualidade de Código (Vitest + Playwright) e Deploys (Vercel) |
| **Vinicius dos Santos** | Frontend Engineer | SPA/Web Client (React 19 + Vite), Estado da Aplicação, UI/UX Consistente |

Professor Orientador: Wosney Ramos de Souza

---

### Governança e Processo de Desenvolvimento

Para garantir a evolução sustentável adotamos políticas de maturação de código:

1. **Gestão de Demandas:** Centralizada no **GitHub Projects** utilizando fluxos Kanban divididos por *Milestones* de entrega.
2. **Estratégia de Branching:** Uso de branches efêmeras (`feat/*`, `fix/*`, `chore/*`, `docs/*`) derivadas da branch de integração (`developer`), que chega à `main` por Pull Request. Commits diretos na `developer` e na `main` são bloqueados por Rulesets.
3. **Quality Gates:** Todo push e Pull Request para a `developer` ou a `main` dispara uma esteira automatizada no **GitHub Actions** que valida, nas três frentes do sistema (Web, API e IA):
   * Formatação de Código (Linter & Typecheck): Confere os padrões de código e valida os tipos; na Web, também gera o build.
   * Suíte de Testes (Vitest): Roda os testes unitários e de integração.
4. **Deploy:** Feito por workflows manuais do GitHub Actions, só a partir da `main`, publicando na **Vercel**. O deploy da API aplica as migrations do banco antes de publicar.


Acesse: https://feedback-analytics-web.vercel.app/

---

<p align="center">
  <small>Organização acadêmica voltada à pesquisa aplicada e desenvolvimento de software. 2026.</small>
</p>

---
