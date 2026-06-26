# Prova — Estruturador de Projeto no ClickUp

> Exemplo com dados FICTÍCIOS. Mostra o tipo de saída que a solução gera a partir de um briefing solto.

## Input de exemplo (colado)
```
Briefing (reunião de kickoff):
Cliente: Padaria Forno & Lenha. Vamos refazer o site institucional + cardápio
online e ativar o Instagram. A Marina cuida do conteúdo, o Téo é o dev. Cliente
quer ir ao ar antes do aniversário da loja, que é daqui a 6 semanas. Precisa de
fotos novas dos produtos (vamos contratar fotógrafo), textos das páginas, e a
loja online é só vitrine (sem pagamento no site por enquanto). Aprovação do
cliente é sempre com o dono, o Sr. Aldo.
Prazo final: 6 semanas
Time: Marina (conteúdo), Téo (dev)
```

## Output esperado (trecho)
```
1. ESTRUTURA DO PROJETO
Space: Clientes
  Pasta: Padaria Forno & Lenha — Site + Social
    Lista: Conteúdo        -> agrupa textos, fotos e tudo que alimenta o site/social
    Lista: Site            -> desenvolvimento e publicação das páginas
    Lista: Social          -> ativação do Instagram
    Lista: Aprovações      -> tudo que depende do Sr. Aldo, isolado pra não travar o resto

2. TAREFAS POR LISTA

| Lista | Tarefa | Responsável | Prioridade | Prazo | Dependência |
|---|---|---|---|---|---|
| Conteúdo | Briefing de fotos + contratar fotógrafo | Marina | Alta | Semana 1 | — |
| Conteúdo | Sessão de fotos dos produtos | [DEFINIR] (fotógrafo) | Alta | Semana 2 | Briefing de fotos + contratar fotógrafo |
| Conteúdo | Escrever textos das páginas | Marina | Alta | Semana 2 | — |
| Aprovações | Aprovar textos com Sr. Aldo | Sr. Aldo | Urgente | Semana 3 | Escrever textos das páginas |
| Site | Estrutura e layout das páginas | Téo | Alta | Semana 2 | — |
| Site | Montar páginas com textos + fotos | Téo | Alta | Semana 4 | Aprovar textos com Sr. Aldo; Sessão de fotos dos produtos |
| Site | Cardápio online (vitrine, sem pagamento) | Téo | Normal | Semana 4 | Montar páginas com textos + fotos |
| Aprovações | Aprovação final do site com Sr. Aldo | Sr. Aldo | Urgente | Semana 5 | Cardápio online (vitrine, sem pagamento) |
| Site | Publicar / ir ao ar | Téo | Urgente | Semana 6 | Aprovação final do site com Sr. Aldo |
| Social | Configurar Instagram + 3 posts de lançamento | Marina | Normal | Semana 6 | Sessão de fotos dos produtos |

3. MARCOS / CRONOGRAMA
Início (Semana 1) — conteúdo e fotos em produção.
Marco 1 (Semana 3) — textos aprovados pelo cliente.
Marco 2 (Semana 5) — site aprovado.
Entrega (Semana 6) — site no ar + Instagram ativo, alinhado ao aniversário da loja.

4. SUBTAREFAS / CHECKLISTS
Tarefa "Montar páginas com textos + fotos":
  - Home
  - Sobre
  - Cardápio
  - Contato / localização
  - Teste em mobile

5. CAMPOS E LABELS SUGERIDOS
Campo "Cliente": Padaria Forno & Lenha. Campo "Frente": Conteúdo / Site / Social.
Labels: "Espera-aprovação" (pra marcar o que está parado no Sr. Aldo).

6. O QUE FALTA DEFINIR
- Responsável da sessão de fotos: o fotógrafo ainda não foi contratado [DEFINIR].
- Data de início absoluta: o cronograma está em semanas relativas; fixar a data ao montar.
```

## Por que funciona
Toda a estrutura saiu do próprio briefing — nada foi inventado. Os nomes (Marina, Téo, Sr. Aldo) vieram da reunião; o que a reunião não fechou (o fotógrafo, a data de início) virou [DEFINIR] em vez de um chute. As dependências respeitam a lógica real (não dá pra publicar antes de aprovar), e o cronograma se ancora no único prazo dado: o aniversário da loja em 6 semanas.
