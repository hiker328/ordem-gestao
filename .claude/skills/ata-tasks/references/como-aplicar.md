# Como aplicar — Gerador de ATA + Tarefas pós-reunião

> Você aplica sozinho, em minutos. Não precisa instalar nem conectar nada. O único insumo é a transcrição da reunião.

## Antes: como obter a transcrição
A solução roda em cima de texto. Você precisa da transcrição da reunião — três caminhos:

- **Google Meet:** ative as legendas durante a reunião e/ou a transcrição automática (disponível nos planos Workspace). Ao final, a transcrição vai pro Google Docs do organizador. Copie o texto.
- **Zoom:** ative "Gravar na nuvem" com transcrição de áudio (Audio Transcript) ou as legendas automáticas. A transcrição fica disponível no painel da gravação. Baixe ou copie o .vtt/.txt.
- **Microsoft Teams:** clique em "Iniciar transcrição" durante a reunião. Depois, ela aparece junto da gravação no chat da reunião / Stream. Copie o texto.
- **Sem transcrição nativa (ligação, presencial, áudio gravado):** use um transcritor — por exemplo cole o áudio num serviço de transcrição (Whisper, ou ferramentas como Tactiq/Otter) e copie o texto resultante.

Qualquer um serve: a solução só precisa do texto colado. Não importa se está bruto, com marcação de falante ou não.

## Passo a passo
1. Obtenha a transcrição da reunião (ver acima) e copie o texto.
2. Abra uma conversa nova no Claude (ou ChatGPT). Cole o prompt do arquivo `solucao.md`.
3. No fim do prompt, cole a sua transcrição no campo indicado. Se tiver, preencha também objetivo, participantes e data — melhora a atribuição de responsáveis.
4. Envie. Você recebe: resumo executivo, decisões tomadas, a tabela de tarefas (Tarefa | Responsável | Prazo | Prioridade), pendências e o follow-up.
5. Revise os campos marcados [DEFINIR] — são justamente o que ficou em aberto na reunião. Defina responsável/prazo com o time e atualize.
6. Distribua a ata pro grupo enquanto a reunião ainda está fresca. Esse é o ganho operacional: nada se perde no caminho.

## Roteiro do vídeo (gravar — alvo 4-6 min, sem emoji)
- 0:00 — A dor: "a reunião acaba, todo mundo concorda com tudo, e na segunda ninguém lembra quem ficou de fazer o quê."
- 0:30 — O que essa solução faz: pega a transcrição da reunião e devolve a ata com decisões e a lista de tarefas com responsável e prazo.
- 1:00 — Onde pegar a transcrição: mostrar rápido Meet / Zoom / Teams (legenda/transcrição) e citar o caminho do transcritor pra áudio.
- 2:00 — Colar o prompt + a transcrição (usar uma reunião de exemplo com dado fictício).
- 3:00 — Ler a saída ao vivo: resumo, decisões, a tabela de tarefas e os [DEFINIR].
- 4:30 — Fecho: o resultado esperado + "se quiser isso rodando automático em cima de toda reunião da sua operação, me chama" (contato).

## Erros comuns
- Colar uma transcrição cortada pela metade: a ata sai incompleta. Confira que copiou do começo ao fim.
- Ignorar os [DEFINIR]: eles não são erro da ferramenta — são o que a reunião deixou em aberto. Trate-os como o seu checklist.
- Não informar os participantes quando a transcrição não marca quem falou: sem isso, mais tarefas saem com responsável [DEFINIR].
