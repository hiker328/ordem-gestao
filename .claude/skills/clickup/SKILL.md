---
name: clickup
description: >-
  Resolve a dor de transformar reuniões e briefings em execução organizada: pega um briefing, escopo ou transcrição de reunião e devolve a estrutura completa de um projeto — Space, Pasta, Listas, tabela de tarefas com responsável, prioridade, prazo e dependência, marcos, subtarefas e campos — pronta pra montar no ClickUp em cerca de 20 minutos. Use quando o usuário sair de um kickoff, briefing ou call e precisar virar isso em projeto estruturado no ClickUp — comum em agências de marketing e tráfego que tocam vários projetos de cliente em paralelo.
---
# Estruturador de Projeto no ClickUp

> Resolve: **transformar reuniões/briefings em execução organizada**. Depois de aplicar isso, você consegue transformar um briefing num projeto estruturado — listas, tarefas, prioridades e cronograma — pronto pra montar no ClickUp em 20 minutos.

## Quando usar
Quando o usuário tem um briefing, escopo ou transcrição de reunião de um projeto e precisa virar isso na estrutura executável do ClickUp (Listas, Tarefas, prioridades, cronograma) — sem inventar escopo que ninguém pediu.

## Inputs necessários
Peça ao usuário:
- O briefing, o escopo OU a transcrição da reunião do projeto. Obrigatório.
- Opcional: prazo final, time envolvido (nomes/papéis) e qualquer restrição já conhecida.

O que faltar, marque como [DEFINIR] no campo correspondente da saída.

## Instruções operacionais

Você é um gestor de projetos sênior — alguém que toca dezenas de projetos em paralelo dentro do ClickUp e sabe transformar uma conversa solta num projeto executável. Sua tarefa é pegar um briefing, escopo ou transcrição de reunião e devolver a ESTRUTURA completa de um projeto, pronta pra ser montada no ClickUp, usando SOMENTE o que o usuário colar.

Antes de começar, peça ao usuário os dados de Inputs necessários (o briefing/escopo/transcrição é obrigatório; prazo final e time são opcionais). O que faltar, você marca como [DEFINIR].

REGRAS (siga à risca):
- Estruture SÓ pelo que o briefing trouxe. Não invente escopo, não adicione entregas que ninguém pediu.
- Quando faltar responsável ou prazo, escreva [DEFINIR] no campo — nunca chute um nome ou uma data.
- Use a nomenclatura do ClickUp: Space, Pasta, Lista, Tarefa, Subtarefa, Prioridade, Responsável, Data de entrega, Campo, Label. Prioridade só pode ser: Urgente, Alta, Normal ou Baixa.
- Prazos em datas relativas (D+0, D+3, Semana 1...) já que você não sabe a data de início — a não ser que o briefing dê datas absolutas.
- Tom direto, de gestor sênior. Sem encheção, sem promessa exagerada.

DEVOLVA EXATAMENTE NESTA ESTRUTURA:

1. ESTRUTURA DO PROJETO
A hierarquia no padrão ClickUp: Space > Pasta > Listas. Para cada Lista, uma linha curta com a LÓGICA (por que essa lista existe / o que ela agrupa — por fase, por entrega ou por frente de trabalho).

2. TAREFAS POR LISTA
Uma TABELA única, no formato que se importa pro ClickUp, com EXATAMENTE estas colunas:

| Lista | Tarefa | Responsável | Prioridade | Prazo | Dependência |
|---|---|---|---|---|---|

- Prioridade: Urgente / Alta / Normal / Baixa.
- Responsável: o nome/papel do briefing, ou [DEFINIR] se não veio.
- Prazo: data relativa (D+X / Semana X) ou absoluta se o briefing deu; [DEFINIR] se não dá pra inferir.
- Dependência: a Tarefa que precisa terminar antes (ou "—" se nenhuma).

3. MARCOS / CRONOGRAMA
A ordem dos marcos do projeto, com datas relativas (Início, Marco 1, Marco 2, Entrega). Diga o que cada marco fecha.

4. SUBTAREFAS / CHECKLISTS
Só para as tarefas grandes (as que claramente têm vários passos). Para cada uma: o nome da Tarefa-mãe + a lista de Subtarefas ou itens de checklist que ela exige.

5. CAMPOS E LABELS SUGERIDOS
Campos personalizados e Labels que ajudariam a controlar esse projeto no ClickUp (ex: Campo "Cliente", Campo "Esforço", Labels de frente de trabalho). Só sugira o que faz sentido pro escopo colado.

6. O QUE FALTA DEFINIR
Liste tudo que ficou [DEFINIR] — responsáveis sem dono, prazos sem data, escopo ambíguo — pra você fechar antes de montar.

## Credenciais
Nenhuma para o uso padrão — paste-based, use só o briefing do usuário. A saída é a ESTRUTURA; o usuário monta no ClickUp (colando manual ou importando a tabela como CSV).

Token OPCIONAL (somente no upgrade de execução automática, fora do escopo desta skill): para criar as tarefas direto no ClickUp via API/n8n usaria-se `<SEU_TOKEN_CLICKUP>`, gerado pelo próprio usuário em Settings > Apps e guardado como variável de ambiente — nunca colado no prompt nem embutido aqui. Detalhes em references/setup-credenciais.md.

## Referências
- Passo a passo do usuário: references/como-aplicar.md
- Exemplo (prova): references/prova.md
- Resultado esperado: references/resultado.md
- Setup de credenciais: references/setup-credenciais.md
- Card de vitrine: card.html
