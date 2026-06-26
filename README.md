# A Ordem — Gestão (Skills)

> Grupo de **Agent Skills** (formato `SKILL.md`) para Claude Code / Cursor, focado em
> **gestão e operação interna** de agência. Microsoluções plug-and-play (paste-based).
> Feito pela **A Ordem**.

---

## O que é

Skills que tiram a operação do "ficou combinado mas ninguém anotou": transformam
reunião em ata + tarefas e briefing em projeto estruturado. Você cola a transcrição ou
o briefing e o agente devolve o material pronto pra executar.

## Por que existe

A operação da agência vaza no intervalo entre o que foi combinado e o que vira
tarefa: ata que ninguém escreve, briefing que vira projeto pela metade. Estas skills
fecham esse buraco, no mesmo padrão, transformando reunião e briefing em **execução
pronta** — com dono e prazo.

## Pra quem é

- **Donos e gestores de agência** que perdem decisões e prazos entre a reunião e a execução.
- **Times que usam ClickUp** (ou qualquer gestor de tarefas) e querem montar projeto rápido.

## As skills

| Skill | O que faz |
|-------|-----------|
| **ata-tasks** | Transforma a transcrição da reunião (Meet/Zoom/Teams) em **ata com decisões + lista de tarefas** (responsável e prazo) |
| **clickup** | Transforma um briefing em **projeto estruturado** (Listas, Tarefas, Prioridades, Cronograma) pronto pro ClickUp |

Cada skill traz, além do `SKILL.md`: `references/` (como-aplicar, prova, resultado,
setup-credenciais) e `card.html` (card de vitrine A Ordem).

> Este grupo vai crescer — novas microsoluções de gestão (ex.: status semanal da
> equipe, briefing de criativo, SOP de processo) entram aqui.

## Início rápido

```bash
git clone https://github.com/<voce>/ordem-gestao.git
cd ordem-gestao
claude
> gera a ata e as tarefas dessa reunião (colo a transcrição)
```

As skills em `.claude/skills/` são detectadas ao rodar o agente na pasta. Para usar em
qualquer projeto, copie `.claude/skills/*` para `~/.claude/skills/` (Claude Code) ou
`~/.cursor/skills/` (Cursor).

## Credenciais

**Nenhuma** no uso padrão (paste-based). O `clickup` tem um **token opcional** só para
o upgrade "auto" (criar as tarefas direto via API) — e aí com o **seu** token, nunca
embutido (ver `references/setup-credenciais.md`).

## O que isso NÃO é

- Não conecta nas suas ferramentas no uso padrão — é paste-based (cola transcrição/briefing).
- Não substitui o gestor — entrega ata/projeto pronto; decisão e execução são suas.
- Não chuta o que faltou — o que não foi definido vira [DEFINIR], explícito.

## Feito pela A Ordem

Criado e mantido pela **A Ordem**. Skills feitas para agências de marketing/tráfego.
Licença MIT (ver `LICENSE`).
