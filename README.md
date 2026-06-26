# A Ordem — Gestão (Skills)

> Grupo de **Agent Skills** (formato `SKILL.md`) para Claude Code / Cursor, focado em
> **gestão e operação interna** de agência. Microsoluções plug-and-play (paste-based).
> Feito pela **A Ordem**.

---

## O que é

Skills que tiram a operação do "ficou combinado mas ninguém anotou": transformam
reunião em ata + tarefas, briefing em projeto, updates da equipe em status, ideia em
briefing de criativo e processo em SOP. Você cola o material bruto e o agente devolve
algo pronto pra executar — sem conectar nada.

## Por que existe

A operação da agência vaza no intervalo entre o que foi combinado e o que vira tarefa:
ata que ninguém escreve, briefing pela metade, status espalhado, processo na cabeça de
uma pessoa só. Estas skills fecham esse buraco, sempre no mesmo padrão, transformando
reunião, briefing e processo em **execução pronta** — com dono e prazo.

## Pra quem é

- **Donos e gestores de agência** que perdem decisões e prazos entre a reunião e a execução.
- **Times que usam ClickUp** (ou qualquer gestor de tarefas) e querem montar projeto rápido.

## Como o conjunto é organizado

Cada skill segue o mesmo padrão (*progressive disclosure*):

```
SKILL.md         →  o agente lê primeiro: papel, inputs e regras.
references/*.md  →  como aplicar, prova (exemplo) e resultado esperado.
card.html        →  card de apresentação da microsolução (visual A Ordem).
```

Princípio: **o que não foi definido vira [DEFINIR], explícito** — a skill estrutura o
que existe, não chuta o que falta.

## As skills

| Skill | O que faz |
|-------|-----------|
| **ata-tasks** | Transcrição da reunião (Meet/Zoom/Teams) → **ata com decisões + tarefas** (responsável e prazo) |
| **clickup** | Briefing → **projeto estruturado** (Listas, Tarefas, Prioridades, Cronograma) pronto pro ClickUp |
| **status-semanal-equipe** | Updates soltos da equipe → **status semanal** (feito, em andamento, travas, prioridades) |
| **briefing-criativo** | Pedido/ideia → **briefing de criativo** (objetivo, público, mensagem, formato, CTA, do's/don'ts) |
| **sop-processo** | Processo descrito → **SOP** delegável (passos, responsáveis, checklist, gatilho) |

Cada skill traz, além do `SKILL.md`: `references/` (como-aplicar, prova, resultado,
setup-credenciais) e `card.html`.

## Início rápido

```bash
git clone https://github.com/hiker328/ordem-gestao.git
cd ordem-gestao
claude
> gera a ata e as tarefas dessa reunião (colo a transcrição)
```

Rodando o `claude` dentro da pasta, as skills em `.claude/skills/` são detectadas. Para
usar em qualquer projeto, copie `.claude/skills/*` para `~/.claude/skills/` (Claude
Code) ou `~/.cursor/skills/` (Cursor).

## Credenciais

**Nenhuma** no uso padrão (paste-based). O `clickup` tem um **token opcional** só para
o upgrade "auto" (criar as tarefas direto via API) — e aí com o **seu** token, nunca
embutido (ver `references/setup-credenciais.md`).

## Exemplos

Um exemplo (input fictício → output) por skill em [`examples/`](examples/).

## O que você precisa pra rodar

- **Claude Code** (ou Cursor) — as skills são `SKILL.md`.
- O seu **material bruto** (transcrição, briefing, updates da equipe, processo).

## Estrutura do repositório

```
ordem-gestao/
├── README.md · LICENSE · .gitignore
├── examples/                 # 1 exemplo por skill (input → output)
└── .claude/skills/
    ├── ata-tasks/            (SKILL.md + references/ + card.html)
    ├── clickup/
    ├── status-semanal-equipe/
    ├── briefing-criativo/
    └── sop-processo/
```

## Roadmap

| Versão | Conteúdo |
|--------|----------|
| v1 (atual) | 5 skills paste-based de gestão |
| Próximas | upgrade "auto" do ClickUp · checklist de qualidade de entrega · onboarding de time |

## O que isso NÃO é

- Não conecta nas suas ferramentas no uso padrão — é paste-based (cola transcrição/briefing).
- Não substitui o gestor — entrega ata/projeto pronto; decisão e execução são suas.
- Não chuta o que faltou — o que não foi definido vira [DEFINIR], explícito.

## Feito pela A Ordem

Criado e mantido pela **A Ordem**. Skills feitas para agências de marketing/tráfego.
Licença MIT (ver `LICENSE`).
