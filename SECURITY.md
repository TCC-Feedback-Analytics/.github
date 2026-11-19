# Política de segurança

Obrigado por ajudar a manter o Feedback Analytics seguro. Esta política vale para todos os repositórios da organização TCC-Feedback-Analytics.

## O que está coberto

| Repositório | O que é | Em produção |
|---|---|---|
| [feedback-analytics-web](https://github.com/TCC-Feedback-Analytics/feedback-analytics-web) | Site e painel do gestor | https://feedback-analytics-web.vercel.app |
| [feedback-analytics-api-gateway](https://github.com/TCC-Feedback-Analytics/feedback-analytics-api-gateway) | API, login e fila da IA | https://feedback-analytics-api-gateway.vercel.app |
| [feedback-analytics-ia-analyze](https://github.com/TCC-Feedback-Analytics/feedback-analytics-ia-analyze) | Serviço que conversa com o modelo de IA | Interno, chamado só pela API |
| [feedback-analytics-contracts](https://github.com/TCC-Feedback-Analytics/feedback-analytics-contracts) | Contratos compartilhados entre os serviços | Pacote usado pelos serviços |

Só a versão publicada a partir da branch `main` de cada repositório recebe correções de segurança.

## Como reportar uma falha

**Não abra uma issue pública.** Use o canal privado do GitHub:

1. Abra a aba **Security** do repositório onde está a falha.
2. Clique em **Report a vulnerability**.
3. Descreva o problema. O relato chega só para os mantenedores e não fica público.

Ajuda muito se o relato trouxer:

- o endereço ou a rota afetada e o que dá para fazer com a falha;
- os passos para reproduzir;
- o impacto que você percebeu (por exemplo, ver dados de outra empresa ou entrar sem senha);
- se possível, uma sugestão de correção.

## O que acontece depois

- Confirmamos o recebimento e avaliamos a gravidade.
- Combinamos com você o prazo da correção e mantemos você informado.
- Depois de corrigida e publicada, a falha pode ser divulgada num aviso de segurança do repositório, com o seu crédito, se você quiser.
- Se a falha tiver exposto dados pessoais, seguimos o [roteiro de incidente](https://github.com/TCC-Feedback-Analytics/feedback-analytics/blob/main/docs/seguranca/roteiro-de-incidente.md), que inclui avisar as empresas afetadas como prevê a LGPD.

## Regras para quem pesquisa

Pedimos que a pesquisa siga estas regras:

- Use uma conta e uma empresa criadas por você. Não acesse, altere nem apague dados de outras empresas ou de clientes.
- Não faça ataques de negação de serviço nem envie formulários em massa. O sistema roda em planos com cota de uso.
- Não use engenharia social contra a equipe ou contra os clientes.
- Ao encontrar dados de outra pessoa, pare, não os guarde e avise pelo canal privado.

Ficam fora do escopo os serviços de terceiros que hospedam o sistema (Vercel, Supabase, Brevo, OpenRouter e Google) e a configuração de DNS do domínio `vercel.app`, que é da Vercel.

## Saiba mais

A forma como o sistema se protege está documentada no [mapa de ameaças](https://github.com/TCC-Feedback-Analytics/feedback-analytics/blob/main/docs/seguranca/mapa-de-ameacas.md) e no [inventário de dados pessoais](https://github.com/TCC-Feedback-Analytics/feedback-analytics/blob/main/docs/seguranca/inventario-de-dados.md).
