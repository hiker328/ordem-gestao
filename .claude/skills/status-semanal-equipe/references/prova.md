# Prova — Status semanal da equipe

> Exemplo com dados FICTÍCIOS. Mostra o tipo de saída que a solução gera.

## Input de exemplo (colado)
```
Semana de referência: 16 a 20/06/2026
Deveriam reportar: Bia, Léo, Dani, Téo
Updates:
Bia (cliente Aurora): subi as 3 campanhas novas de tráfego, CPL caiu de R$42 pra R$28.
Falta o cliente aprovar os criativos da fase 2 — mandei quinta, sem resposta ainda.
Léo (cliente Verde): terminei o relatório mensal e apresentei pro cliente. Renovou
mais 3 meses. Estou agora montando o funil de e-mail, mas travei: preciso de acesso
à conta de e-mail marketing do cliente e ninguém sabe quem tem a senha.
Dani (interno): refiz a identidade do nosso próprio Instagram, postei 4 vezes.
Téo: (sem update)
```

## Output esperado (trecho)
```
1. RESUMO DA SEMANA
Semana de 16 a 20/06/2026. A operação entregou: 3 campanhas novas no cliente Aurora
(CPL de R$42 para R$28) e a renovação do cliente Verde por mais 3 meses após o
relatório mensal. Em movimento, o funil de e-mail do Verde e o conteúdo interno.
Atenção para duas travas: aprovação de criativos parada no cliente Aurora e falta de
acesso ao e-mail marketing do cliente Verde. Téo não reportou.

2. POR PESSOA / PROJETO
- Bia (Aurora) — Feito: 3 campanhas novas no ar, CPL R$42 -> R$28 | Fazendo: aguardando
  aprovação dos criativos da fase 2 | Travas: cliente não respondeu a aprovação (desde quinta)
- Léo (Verde) — Feito: relatório mensal apresentado, cliente renovou +3 meses | Fazendo:
  montagem do funil de e-mail | Travas: sem acesso à conta de e-mail marketing do cliente
- Dani (interno) — Feito: nova identidade do Instagram + 4 posts | Fazendo: — | Travas: —
- NÃO reportaram esta semana: Téo

3. BLOQUEIOS QUE PRECISAM DE DECISÃO
- Funil de e-mail do cliente Verde está parado: falta o acesso à conta de e-mail
  marketing e ninguém sabe quem tem a senha. Destrava com: cobrar a credencial do
  cliente (decisão de quem aciona o contato).
- Criativos da fase 2 do Aurora parados na aprovação do cliente desde quinta.
  Destrava com: decidir se faz follow-up direto ou escala com o gestor da conta.

4. PRIORIDADES DA PRÓXIMA SEMANA
1. Conseguir o acesso ao e-mail marketing do Verde (destrava o funil).
2. Fechar a aprovação dos criativos da fase 2 do Aurora.
3. Confirmar o status do Téo (sem update nesta semana).

5. ALERTAS / RISCOS
- Téo sem update: pode ser sobrecarga, ausência ou tarefa parada — verificar.
- Aprovação do Aurora sem resposta há dias pode atrasar a fase 2 inteira.

6. PENDÊNCIAS / [DEFINIR]
- Responsável por cobrar o acesso ao e-mail marketing do Verde: [DEFINIR]
- Status real das entregas do Téo nesta semana: [DEFINIR]
```

## Por que funciona
O status sai inteiro dos próprios updates (não há achismo): cada entrega aparece como foi reportada, cada trava com o que a bloqueia. O ganho está em três coisas que a leitura solta não dá: os bloqueios que dependem de decisão ficam isolados num lugar só, quem não reportou (Téo) é apontado em vez de sumir, e o que ficou sem dono vira [DEFINIR] em vez de ser inventado.
