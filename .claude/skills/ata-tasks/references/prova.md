# Prova — Gerador de ATA + Tarefas pós-reunião

> Exemplo com dados FICTÍCIOS. Mostra o tipo de saída que a solução gera.

## Input de exemplo (colado)
```
Objetivo: alinhar o lançamento da nova landing page
Participantes: Marina (gestão), Caio (design), Rafa (tráfego)
Data: 18/06/2026
Transcrição:
Marina: pessoal, a meta é colocar a landing nova no ar antes do fim do mês.
Caio: o layout eu fecho até sexta, sem problema. Falta a copy final.
Marina: a copy fico eu. Te mando até quarta pra você diagramar.
Rafa: e o pixel? Sem o pixel configurado eu não consigo subir campanha.
Marina: boa. Alguém tem que configurar o pixel. A gente resolve quem depois.
Caio: o domínio a gente já comprou ou não?
Marina: acho que sim, mas não tenho certeza. Vou confirmar com o financeiro.
Rafa: então combinado: assim que a página subir, eu ligo as campanhas no dia seguinte.
Marina: fechado. Marca uma call rápida na quinta que vem pra ver se está tudo de pé.
```

## Output esperado (trecho)
```
1. RESUMO EXECUTIVO
Reunião de 18/06/2026 com Marina, Caio e Rafa para alinhar o lançamento da nova
landing page, com meta de colocá-la no ar antes do fim do mês. Ficaram definidos o
prazo do layout e da copy e a ordem de subida das campanhas; pendências sobre pixel
e domínio ficaram em aberto.

2. DECISÕES TOMADAS
- A nova landing page deve entrar no ar antes do fim do mês.
- As campanhas de tráfego serão ligadas no dia seguinte ao da página no ar.
- Haverá uma call de acompanhamento na quinta-feira seguinte.

3. LISTA DE TAREFAS
| Tarefa | Responsável | Prazo | Prioridade |
|---|---|---|---|
| Fechar o layout da landing page | Caio | Sexta-feira | Alta |
| Enviar a copy final para diagramação | Marina | Quarta-feira | Alta |
| Configurar o pixel de rastreamento | [DEFINIR] | [DEFINIR] | Alta |
| Ligar as campanhas no dia seguinte ao go-live | Rafa | Dia seguinte à página no ar | Média |
| Confirmar com o financeiro se o domínio já foi comprado | Marina | [DEFINIR] | Média |

4. PENDÊNCIAS / ITENS EM ABERTO
- Quem vai configurar o pixel não foi definido (a reunião adiou a decisão).
- Não há certeza se o domínio já foi comprado — depende de confirmação do financeiro.

5. PRÓXIMA REUNIÃO / FOLLOW-UP
Call de acompanhamento na quinta-feira seguinte, para verificar se tudo está de pé.
```

## Por que funciona
A ata sai inteira da própria transcrição (não há achismo): cada decisão tem fechamento explícito na fala, cada tarefa tem um dono quando ele foi citado — e onde a reunião deixou em aberto (pixel sem responsável, domínio sem confirmação), a saída marca [DEFINIR] e joga o item pras pendências, em vez de inventar.
