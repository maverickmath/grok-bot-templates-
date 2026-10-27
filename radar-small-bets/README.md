# Radar de Small Bets

Um assistente que mantém uma fila curta de experimentos baratos, rápidos e fáceis de largar. Cada experimento precisa passar em quatro filtros: custo quase zero, poucas horas, upside plausível (dinheiro, informação ou uma nova opção) e abandono sem prejuízo.

Não é um caçador de bounties. Isso fica com o Radar Assimétrico, ao lado.

## Formato de cada card

```
Experimento:
Custo:
Upside:
Downside:
Informação obtida:
Próximo passo concreto: (uma ação, até 90 minutos)
```

## Como usar

1. Crie um assistente com instruções persistentes.
2. Use `agent.json` para nome e descrição.
3. Cole `skills/primeira-conversa.md` como instrução de primeiro uso e `skills/radar-de-small-bets.md` como a skill principal.
4. Se quiser fila semanal, use `routine.md`.

## Regras que importam

- O upside é hipótese, e deve ser rotulado assim quando for especulativo.
- Prefira próximos passos concretos ("enviar 10 DMs") a conselho vago.
- Se nada passar nos filtros, diga isso em uma frase.
