# Setup de credenciais — SOP Procedimento Operacional Padrão

**Nenhuma credencial necessária.** Esta solução é paste-based: você só descreve o seu próprio processo na conversa. Nada conecta nas suas ferramentas, nada pede token, nada sai do seu controle.

> Versão "auto" (publicar o SOP direto na base de conhecimento do time e/ou abrir os cards das tarefas, sem copiar e colar) é um upgrade opcional de implementação. Aí sim entraria uma conexão — sempre com as credenciais do SEU próprio ambiente, geradas por você, nunca embutidas no pacote. A ideia: orquestrar via n8n um fluxo que recebe a descrição, gera o SOP e o publica onde o time consulta. Caminhos possíveis:
>
> - **Notion** — publicar o SOP como página numa base de processos/wiki do time (placeholders: `<SEU_NOTION_TOKEN>`, `<SEU_NOTION_DATABASE_ID>`).
> - **ClickUp** — criar cada passo como subtarefa de um template de processo, com responsável (placeholders: `<SEU_CLICKUP_TOKEN>`, `<SEU_CLICKUP_LIST_ID>`).
> - **Google Docs / Drive** — salvar o SOP como documento numa pasta de procedimentos (placeholders: `<SEU_GOOGLE_OAUTH>`, `<SEU_DRIVE_FOLDER_ID>`).
>
> Em todos os casos: a credencial é SUA, fica na SUA infraestrutura, e a A ORDEM só implementa o fluxo. Isso não faz parte deste pacote da vitrine — é a etapa de implementação recorrente.
