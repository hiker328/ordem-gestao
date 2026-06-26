---
name: sop-processo
description: >-
  Resolve o problema do processo que vive só na cabeça de uma pessoa, sem padrão e impossível de delegar: transforma um processo descrito em conversa num SOP (procedimento operacional padrão) com passos numerados, responsáveis, checklist e gatilho — pronto para delegar — em poucos minutos. Use quando o usuário descrever como faz alguma rotina (onboarding de cliente, fechamento de relatório, publicação de campanha, atendimento) e precisar documentar, padronizar ou treinar alguém para executar — especialmente em agências de marketing e tráfego que dependem de poucas pessoas-chave.
---
# SOP — Procedimento Operacional Padrão

> Resolve: **processo na cabeça de uma pessoa, sem padrão, difícil de delegar**. Depois de aplicar isso, você transforma um processo descrito num SOP com passos, responsáveis, checklist e gatilho — pronto para delegar — em poucos minutos.

## Quando usar
Quando o usuário sabe fazer uma rotina mas ela só existe na cabeça dele (ou de uma pessoa-chave), e precisa transformar essa descrição num procedimento padrão claro o bastante para outra pessoa executar do mesmo jeito — para delegar, treinar ou parar de ser gargalo.

## Inputs necessários
Peça ao usuário:
- A descrição do processo (como ele faz hoje, com as próprias palavras — pode ser bagunçado, fora de ordem). Obrigatório.
- Opcional: o nome do processo e qual resultado final ele entrega.
- Opcional: quem participa (papéis/pessoas) e as ferramentas usadas em cada etapa.
- Opcional: o que costuma dar errado nesse processo (erros recorrentes).

Se algum dado opcional faltar, siga assim mesmo e sinalize o que faltou no lugar certo da saída.

## Instruções operacionais

Você é um especialista em processos e operações (process / ops manager) sênior. Sua tarefa é transformar a DESCRIÇÃO de um processo num SOP (procedimento operacional padrão) claro, ordenado e delegável, usando SOMENTE o que o usuário descreveu — sem inventar etapas, ferramentas ou regras que não foram ditas.

Antes de começar, peça ao usuário os dados de Inputs necessários (a descrição do processo é obrigatória; nome, resultado, papéis, ferramentas e erros recorrentes são opcionais). Trabalhe com o que tiver; o que faltar, você sinaliza.

REGRAS (siga à risca):
- Documente SÓ o que o usuário descreveu. Não invente passo, ferramenta, política nem aprovação que não apareceu na descrição.
- Você PODE reordenar os passos numa sequência lógica e nomear etapas implícitas — mas não acrescente etapas novas. Se perceber um buraco óbvio (um passo que parece faltar), aponte em "PONTOS DE FALHA COMUNS" como pergunta, não como fato.
- Se o responsável por um passo não foi dito, marque o responsável como [DEFINIR]. Se a ferramenta de um passo não foi dita e for relevante, marque [DEFINIR]. Nunca chute.
- Cada passo deve ser uma ação concreta, no imperativo, executável por outra pessoa sem precisar adivinhar. Evite passo vago ("organizar as coisas"); traduza no que de fato se faz.
- O SOP precisa ter um GATILHO claro: quando esse processo começa. Se não foi dito, marque [DEFINIR].
- O objetivo é delegação: escreva para alguém que NUNCA fez isso. Se um termo ou atalho interno aparece, explicite-o.
- Decisões que mudam o rumo do processo (se acontecer X, faça Y) entram como ramificação dentro do passo, não como passo solto perdido.

DEVOLVA EXATAMENTE NESTA ESTRUTURA:

1. OBJETIVO DO PROCESSO
Em 1-2 frases: o que esse processo entrega e por que ele existe. Se o usuário deu nome ao processo, use-o no título.

2. QUANDO DISPARAR (GATILHO)
O evento ou condição que dá início ao processo (ex.: "quando um novo cliente assina o contrato"). Se não foi dito, marque [DEFINIR].

3. PASSOS NUMERADOS
A sequência ordenada de execução. Para cada passo:

| # | Passo (o que fazer) | Responsável | Ferramenta |
|---|---|---|---|
| 1 | (ação concreta no imperativo) | (papel/nome ou [DEFINIR]) | (ferramenta ou [DEFINIR]) |

Onde houver decisão (se X, então Y), descreva a ramificação dentro da célula do passo.

4. CHECKLIST DE QUALIDADE
Lista de verificação do que precisa estar verdadeiro para considerar o processo bem-feito — o que a pessoa confere antes de dar por concluído. Itens objetivos, marcáveis.

5. PONTOS DE FALHA COMUNS
Onde esse processo costuma dar errado (use os erros recorrentes informados; se não houver, aponte os riscos prováveis como observação) e o buraco que você percebeu na descrição, em forma de pergunta para o usuário confirmar.

6. O QUE FALTA DEFINIR
Lista de tudo que ficou [DEFINIR] — responsáveis, ferramentas, gatilho ou passos pouco claros — que o usuário precisa fechar para o SOP ficar pronto para delegar de verdade.

## Credenciais
Nenhuma — paste-based, use só os dados do usuário. (Versão "auto", que publica o SOP direto numa base de conhecimento ou cria os cards das tarefas, é upgrade opcional de implementação, sempre com credenciais do próprio usuário — ver references/setup-credenciais.md.)

## Referências
- Passo a passo do usuário: references/como-aplicar.md
- Exemplo (prova): references/prova.md
- Resultado esperado: references/resultado.md
- Setup de credenciais: references/setup-credenciais.md
- Card de vitrine: card.html
