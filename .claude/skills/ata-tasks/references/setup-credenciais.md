# Setup de credenciais — Gerador de ATA + Tarefas pós-reunião

**Nenhuma credencial necessária.** Esta solução é paste-based: você só cola a transcrição da sua própria reunião na conversa. Nada conecta nas suas reuniões, nada pede token, nada sai do seu controle.

> Versão "auto" (jogar as tarefas direto numa ferramenta de gestão, sem copiar e colar à mão) é um upgrade opcional de implementação. Aí sim entraria uma conexão — sempre com as credenciais do SEU próprio ambiente, geradas por você, nunca embutidas no pacote. A ideia: orquestrar via n8n um fluxo que recebe a transcrição, gera a ata e cria as tarefas direto na ferramenta onde o time trabalha. Caminhos possíveis:
>
> - **ClickUp** — criar cada tarefa da lista como item, com responsável e prazo (placeholders: `<SEU_CLICKUP_TOKEN>`, `<SEU_CLICKUP_LIST_ID>`).
> - **Notion** — inserir as tarefas como linhas numa base de dados de projetos (placeholders: `<SEU_NOTION_TOKEN>`, `<SEU_NOTION_DATABASE_ID>`).
> - **Google Sheets** — registrar as tarefas numa planilha de acompanhamento (placeholders: `<SEU_GOOGLE_OAUTH>`, `<SEU_SHEET_ID>`).
>
> Em todos os casos: a credencial é SUA, fica na SUA infraestrutura, e a A ORDEM só implementa o fluxo. Isso não faz parte deste pacote da vitrine — é a etapa de implementação recorrente.
