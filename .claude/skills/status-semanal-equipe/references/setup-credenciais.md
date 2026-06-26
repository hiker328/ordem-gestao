# Setup de credenciais — Status semanal da equipe

**Nenhuma credencial necessária.** Esta solução é paste-based: você só cola os updates da sua própria equipe na conversa. Nada conecta no seu Slack, no seu e-mail ou na sua planilha; nada pede token; nada sai do seu controle.

> Versão "auto" (puxar os updates direto da ferramenta onde o time reporta e montar o status sozinho, sem copiar e colar) é um upgrade opcional de implementação. Aí sim entraria uma conexão — sempre com as credenciais do SEU próprio ambiente, geradas por você, nunca embutidas no pacote. A ideia: orquestrar via n8n um fluxo que coleta os updates da semana, consolida e devolve o status pronto. Caminhos possíveis:
>
> - **Slack** — ler as mensagens de um canal de updates da semana (placeholders: `<SEU_SLACK_TOKEN>`, `<SEU_SLACK_CHANNEL_ID>`).
> - **Google Sheets** — ler uma planilha onde cada um reporta o status (placeholders: `<SEU_GOOGLE_OAUTH>`, `<SEU_SHEET_ID>`).
> - **Notion / ClickUp** — puxar o andamento das tarefas direto do board do time (placeholders: `<SEU_NOTION_TOKEN>` / `<SEU_CLICKUP_TOKEN>`, mais o ID da base/lista).
>
> Em todos os casos: a credencial é SUA, fica na SUA infraestrutura, e a A ORDEM só implementa o fluxo. Isso não faz parte deste pacote da vitrine — é a etapa de implementação recorrente.
