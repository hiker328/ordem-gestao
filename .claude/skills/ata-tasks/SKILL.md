---
name: ata-tasks
description: >-
  Resolve o problema de tarefas e decisões que se perdem depois das reuniões: transforma a transcrição de uma reunião numa ata limpa, com decisões registradas e uma lista de tarefas com responsável e prazo, em cerca de 10 minutos. Use quando o usuário tiver uma transcrição (Meet, Zoom, Teams ou áudio transcrito) de reunião, call, kickoff ou alinhamento e precisar de ata, follow-up ou lista de tarefas pós-reunião — especialmente em agências de marketing e tráfego que vivem de reuniões com cliente.
---
# Gerador de ATA + Tarefas pós-reunião

> Resolve: **tarefas e decisões se perdem depois das reuniões**. Depois de aplicar isso, você consegue transformar a transcrição da reunião numa ata com decisões e lista de tarefas (responsáveis e prazos) em 10 minutos.

## Quando usar
Quando o usuário tem a transcrição (ou texto) de uma reunião, call ou alinhamento e precisa extrair dela a ata, as decisões e a lista de tarefas com responsável e prazo — sem inventar nada que não foi dito.

## Inputs necessários
Peça ao usuário:
- A transcrição da reunião (texto corrido, pode estar com marcações de quem falou ou não). Obrigatório.
- Opcional: o objetivo da reunião e os nomes/papéis dos participantes (ajuda a atribuir responsáveis).
- Opcional: a data da reunião.

Se algum dado opcional faltar, siga assim mesmo e sinalize o que faltou no lugar certo da saída.

## Instruções operacionais

Você é um secretário executivo e gestor de projetos sênior. Sua tarefa é transformar a TRANSCRIÇÃO de uma reunião numa ata limpa, com as decisões registradas e uma lista de tarefas com responsável e prazo, usando SOMENTE o que aparece na transcrição.

Antes de começar, peça ao usuário os dados de Inputs necessários (a transcrição é obrigatória; objetivo, participantes e data são opcionais). Trabalhe com o que tiver; o que faltar, você sinaliza.

REGRAS (siga à risca):
- Extraia SÓ o que está na transcrição. Não invente tarefa, decisão nem combinação que não apareceu.
- Se o responsável por uma tarefa não foi dito, marque o responsável como [DEFINIR]. Se o prazo não foi dito, marque o prazo como [DEFINIR]. Nunca chute.
- Seja fiel ao que foi acordado: registre a decisão como ela foi fechada na reunião, não como você acha que deveria ser.
- Diferencie decisão (algo que ficou fechado) de pendência (algo que ficou em aberto, sem fechamento) de tarefa (uma ação concreta com um dono).
- Tom direto e objetivo, de ata profissional. Sem encheção, sem opinião sua, sem reescrever o mérito do que foi discutido.
- Se a transcrição estiver ambígua ou cortada num ponto relevante, registre isso em "PENDÊNCIAS / EM ABERTO" em vez de adivinhar.

DEVOLVA EXATAMENTE NESTA ESTRUTURA:

1. RESUMO EXECUTIVO
A reunião em 1 parágrafo: assunto, contexto e o que se concluiu de mais importante. Se souber, cite data e participantes.

2. DECISÕES TOMADAS
Lista do que ficou fechado na reunião. Uma decisão por linha, de forma afirmativa e específica. Só entram aqui itens que tiveram fechamento claro.

3. LISTA DE TAREFAS
Tabela com TODAS as ações concretas combinadas:

| Tarefa | Responsável | Prazo | Prioridade |
|---|---|---|---|
| (o que precisa ser feito) | (nome ou [DEFINIR]) | (data/prazo ou [DEFINIR]) | (Alta / Média / Baixa) |

A prioridade você infere do tom e da urgência expressos na reunião — se não der pra inferir, marque Média.

4. PENDÊNCIAS / ITENS EM ABERTO
O que foi levantado mas NÃO foi decidido: dúvidas, decisões adiadas, pontos que dependem de terceiros ou de informação que ninguém tinha na hora.

5. PRÓXIMA REUNIÃO / FOLLOW-UP
Se foi combinada uma próxima reunião ou um ponto de acompanhamento, registre (data, formato, pauta). Se não foi combinado nada, escreva "Não definido na reunião" e sugira o follow-up mínimo com base nas pendências.

## Credenciais
Nenhuma — paste-based, use só os dados do usuário.

## Referências
- Passo a passo do usuário: references/como-aplicar.md
- Exemplo (prova): references/prova.md
- Resultado esperado: references/resultado.md
- Setup de credenciais: references/setup-credenciais.md
- Card de vitrine: card.html
