# Setup de credenciais — Estruturador de Projeto no ClickUp

**Nenhuma credencial necessária.** Esta solução é paste-based: você só cola o seu próprio briefing na conversa e recebe a estrutura do projeto. Nada conecta na sua conta ClickUp, nada pede token, nada sai do seu controle. A saída é a ESTRUTURA — você monta as tarefas no ClickUp você mesmo (colando manual ou importando a tabela como CSV).

> Upgrade opcional (implementação): criar as tarefas direto no seu ClickUp, no automático — sem montar nem importar nada na mão. Aí sim a integração usaria o SEU token ClickUp, gerado por você na sua própria conta, guardado como variável de ambiente (no n8n ou na chamada de API), nunca colado no prompt nem compartilhado. Placeholder de referência: `<SEU_TOKEN_CLICKUP>`. Esse modo de execução automática NÃO faz parte deste pacote da vitrine; é escopo de implementação com a A ORDEM.

| Ferramenta | O que adicionar | Onde gerar |
|---|---|---|
| ClickUp (só no upgrade auto) | `<SEU_TOKEN_CLICKUP>` (placeholder) | na sua conta ClickUp: Settings > Apps > gerar token de API pessoal |

Regras:
- Use SEMPRE as suas próprias credenciais.
- A solução nunca pede pra você mandar token pra ninguém.
- Na vitrine (prompt-skill que cola no Claude), **não precisa de credencial** — só o seu briefing.
