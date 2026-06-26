# Prova — SOP Procedimento Operacional Padrão

> Exemplo com dados FICTÍCIOS. Mostra o tipo de saída que a solução gera.

## Input de exemplo (colado)
```
Processo: onboarding de cliente novo de tráfego
Como faço hoje:
Quando o cliente assina o contrato, eu mando um e-mail de boas-vindas com o link do
formulário de acessos. Aí eu espero ele preencher (gerenciador de anúncios, conta do
Instagram, pixel). Quando ele preenche, eu confiro se os acessos vieram certos — às
vezes vem o acesso errado e tenho que pedir de novo, isso atrasa tudo. Depois eu monto
a estrutura de campanha no gerenciador e marco a reunião de kickoff. Na kickoff a gente
alinha meta e expectativa. Aí começa a rodar. As ferramentas são Gmail, um formulário
no Typeform e o gerenciador de anúncios.
```

## Output esperado (trecho)
```
1. OBJETIVO DO PROCESSO
Onboarding de cliente novo de tráfego: levar o cliente recém-assinado do contrato até a
campanha rodando, com todos os acessos conferidos e a meta alinhada em reunião de kickoff.

2. QUANDO DISPARAR (GATILHO)
Quando o cliente assina o contrato.

3. PASSOS NUMERADOS
| # | Passo (o que fazer) | Responsável | Ferramenta |
|---|---|---|---|
| 1 | Enviar e-mail de boas-vindas com o link do formulário de acessos | [DEFINIR] | Gmail |
| 2 | Aguardar o cliente preencher o formulário (gerenciador de anúncios, Instagram, pixel) | Cliente | Typeform |
| 3 | Conferir se os acessos vieram corretos. Se vier acesso errado, solicitar novamente antes de seguir | [DEFINIR] | Gerenciador de anúncios |
| 4 | Montar a estrutura de campanha no gerenciador | [DEFINIR] | Gerenciador de anúncios |
| 5 | Marcar e realizar a reunião de kickoff (alinhar meta e expectativa) | [DEFINIR] | [DEFINIR] |
| 6 | Iniciar a veiculação das campanhas | [DEFINIR] | Gerenciador de anúncios |

4. CHECKLIST DE QUALIDADE
- Todos os acessos solicitados foram recebidos e conferidos como corretos.
- A estrutura de campanha está montada no gerenciador antes da kickoff.
- A reunião de kickoff aconteceu e meta/expectativa ficaram alinhadas e registradas.
- As campanhas só começam a rodar após acessos OK e meta alinhada.

5. PONTOS DE FALHA COMUNS
- Acesso errado enviado pelo cliente (citado): atrasa todo o processo. Mitigar com instrução
  clara no formulário de quais acessos e em que nível conceder.
- Pergunta para confirmar: existe um SLA/prazo para o cliente preencher o formulário? O passo 2
  pode ficar parado indefinidamente se ninguém cobrar.

6. O QUE FALTA DEFINIR
- Responsável pelos passos 1, 3, 4, 5 e 6 (quem na equipe executa): [DEFINIR]
- Ferramenta usada na reunião de kickoff (Meet, Zoom, etc.): [DEFINIR]
- Prazo esperado para o cliente preencher o formulário de acessos: [DEFINIR]
```

## Por que funciona
O SOP sai todo da própria descrição (não há etapa inventada): a solução apenas ordenou os passos e nomeou as etapas implícitas. O tratamento do acesso errado, que estava solto na fala, virou uma ramificação dentro do passo 3 e um ponto de falha. Onde o usuário não disse quem executa ou qual ferramenta, a saída marca [DEFINIR] em vez de chutar — e o buraco percebido (sem prazo para o cliente preencher) vira pergunta, não fato. O resultado já está pronto para delegar assim que os [DEFINIR] forem fechados.
