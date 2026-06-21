# Guia

- **Planejamento de tarefas**: [Issues](https://github.com/orgs/TCC-Feedback-Analytics/projects/3/views/3) 
- **Informações e Atualizações**: [Discussions](https://github.com/orgs/TCC-Feedback-Analytics/discussions) - *Atenção*: Sempre olhem
- **Documentação do Projeto**: [Doc](https://tcc-feedback-analytics.github.io/feedback-analytics/) - *Atenção*: Dúvidas, olha na documentação

### Infraestruturas
- **Deploy**: [Vercel](https://vercel.com/)
- **IA**: [Gemini API](https://ai.google.dev/gemini-api/docs?hl=pt-br)
- **Banco de Dados**: [Supabase](https://supabase.com/)

### O que está em Produção
- **Main**: https://feedback-analytics-web.vercel.app/
- **Homolog**: https://feedback-analytics-web-homolog.vercel.app/
- **Documentação**: https://tcc-feedback-analytics.github.io/feedback-analytics/

---
# Feedback Analytics

Este é um sistema de software desenvolvido como uma solução tecnológica integrada para a coleta, gestão e análise inteligente de feedbacks de clientes. 

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

### Governança e Processo de Desenvolvimento

Para garantir a evolução sustentável adotamos políticas de maturação de código:

1. **Gestão de Demandas:** Centralizada no **GitHub Projects** utilizando fluxos Kanban divididos por *Milestones* de entrega.
2. **Estratégia de Branching:** Uso de branches efêmeras (`feature/*`, `fix/*`) derivadas de uma branch de integração (`homolog`). Commits diretos na `main` são bloqueados por Rulesets.
3. **Quality Gates:** Todo Pull Request dispara uma esteira automatizada no **GitHub Actions** que valida:
   * Formatação de Código (Linter & Typecheck): Confere os padrões de código e valida os tipos.
   * Suíte de Testes (Unitários/Integration): Roda os testes das três frentes do sistema (Web, API e IA) em toda PR para homolog.
   * Validação de Produção (E2E & Build): Na PR de homolog para main, executa novamente as etapas anteriores e adiciona os testes de ponta a ponta (E2E).

---

<p align="center">
  <small>Organização acadêmica voltada à pesquisa aplicada e desenvolvimento de software. 2026.</small>
</p>

---
