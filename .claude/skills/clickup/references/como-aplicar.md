# Como aplicar — Estruturador de Projeto no ClickUp

> Você aplica sozinho, em minutos. Não precisa instalar nem conectar nada. A saída é a estrutura do projeto — você só transfere pro ClickUp.

## Passo a passo
1. Junte o briefing do projeto: pode ser o documento de escopo, as anotações da reunião de kickoff ou a transcrição da call. Quanto mais completo, melhor a estrutura.
2. Abra uma conversa nova no Claude (ou ChatGPT). Cole o prompt do arquivo `solucao.md`.
3. No fim do prompt, cole o seu briefing (e, se tiver, o prazo final e os nomes/papéis do time).
4. Envie. Você recebe: a estrutura do projeto (Space/Pasta/Listas), a tabela de tarefas, os marcos, as subtarefas e os campos/labels sugeridos.
5. Confira os campos marcados como [DEFINIR] — esses são os buracos do briefing (responsável ou prazo que ninguém fechou). Resolva antes de montar.
6. Monte no ClickUp (abaixo, dois caminhos: colar manual ou importar a tabela).

## Como colar a estrutura no ClickUp

### Caminho rápido — colar manual
1. Crie o Space (ou use um existente) e a Pasta com os nomes que a saída deu.
2. Crie cada Lista da seção "Estrutura do projeto".
3. Em cada Lista, cole as Tarefas. No ClickUp você pode colar várias linhas de uma vez no campo de nova tarefa — cada linha vira uma Tarefa.
4. Abra cada Tarefa e preencha Responsável, Prioridade (Urgente/Alta/Normal/Baixa) e Data de entrega conforme a tabela.
5. Nas tarefas grandes, abra a aba de Subtarefas/Checklist e cole os itens da seção "Subtarefas / Checklists".

### Caminho com importação — colar a tabela
1. Peça ao Claude/ChatGPT pra exportar a "Tarefas por lista" como CSV (colunas: Lista, Tarefa, Responsável, Prioridade, Prazo, Dependência). Salve como `.csv`.
2. No ClickUp: menu do Space/Pasta > Importar/Import > escolha CSV/Excel.
3. Mapeie as colunas: Lista > List, Tarefa > Task Name, Responsável > Assignee, Prioridade > Priority, Prazo > Due Date, Dependência > campo de texto ou relação de dependência.
4. Rode a importação. As tarefas entram já organizadas por Lista.
5. Ajuste as dependências (ligar a Tarefa que espera à que precede) e revise os [DEFINIR].

## Roteiro do vídeo (gravar — alvo 4-6 min, sem emoji)
- 0:00 — A dor: "saiu da reunião com o projeto na cabeça e três páginas de anotação — e agora alguém tem que transformar isso em tarefas."
- 0:25 — O que essa solução faz: pega o briefing e devolve o projeto estruturado (listas, tarefas, prioridades, cronograma), pronto pra montar no ClickUp.
- 0:50 — Mostrar o briefing de exemplo (dado fictício) e colar o prompt do `solucao.md`.
- 1:40 — Colar o briefing no fim do prompt e enviar.
- 2:20 — Ler a saída ao vivo: a estrutura, a tabela de tarefas no formato ClickUp, os marcos.
- 3:30 — Transferir pro ClickUp: mostrar os dois caminhos (colar manual e importar a tabela como CSV).
- 4:30 — Fecho: o resultado esperado + "se quiser isso virando um processo replicável na sua operação — todo briefing já saindo estruturado —, me chama" (contato).

## Erros comuns
- Colar um briefing vago demais: se a reunião não definiu responsável ou prazo, a saída vai marcar [DEFINIR] — isso é o esperado, é você que fecha esses pontos.
- Querer que a IA invente entregas: ela estrutura só pelo que o briefing trouxe. Se faltou escopo, complete o briefing — não peça pra ela "completar".
- Esquecer de ajustar as dependências depois de importar o CSV: o ClickUp importa o texto, mas a ligação entre tarefas dependentes você fecha na mão.
