# Setup de credenciais — Briefing de criativo

**Nenhuma credencial necessária.** Esta solução é paste-based: você só descreve o pedido da peça na conversa. Nada conecta nas suas ferramentas, nada pede token, nada sai do seu controle.

> Versão "auto" (gerar o briefing e já abrir o card de produção na ferramenta onde o time trabalha, sem copiar e colar) é um upgrade opcional de implementação. Aí sim entraria uma conexão — sempre com as credenciais do SEU próprio ambiente, geradas por você, nunca embutidas no pacote. A ideia: orquestrar via n8n um fluxo que recebe o pedido, gera o briefing e cria o card de produção. Caminhos possíveis:
>
> - **Trello / ClickUp** — criar o card de produção do criativo com o briefing no corpo e o responsável (placeholders: `<SEU_TRELLO_TOKEN>` / `<SEU_CLICKUP_TOKEN>`, mais o ID do board/lista).
> - **Notion** — inserir o briefing como página numa base de produção de criativos (placeholders: `<SEU_NOTION_TOKEN>`, `<SEU_NOTION_DATABASE_ID>`).
> - **Google Drive / Docs** — salvar o briefing como documento na pasta do cliente (placeholders: `<SEU_GOOGLE_OAUTH>`, `<SEU_DRIVE_FOLDER_ID>`).
>
> Em todos os casos: a credencial é SUA, fica na SUA infraestrutura, e a A ORDEM só implementa o fluxo. Isso não faz parte deste pacote da vitrine — é a etapa de implementação recorrente.
