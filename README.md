# miniguia-estudos-notebooklm
# Jiu-Jitsu — Preparação para Campeonatos

Caderno de estudo sobre regras e regulamentos das principais federações de Jiu-Jitsu Brasileiro, com foco em preparação para competições.

## Objetivos

- Entender o sistema de pontuação e critérios de vitória da IBJJF e CBJJE
- Conhecer as principais diferenças de regras entre as federações
- Dominar os requisitos de kimono para não ser desclassificado

## Fontes

- [Regras IBJJF 2024 (PDF)](https://website-cbjj-production.s3.amazonaws.com/BdpQPVgcCYBMB5tpg6T9wPP4?response-content-disposition=inline%3B%20filename%3D%222024JUN_IBJJF_Regras_PT.pdf%22%3B%20filename%2A%3DUTF-8%27%272024JUN_IBJJF_Regras_PT.pdf&response-content-type=application%2Fpdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAUPTFRNARGXPAI7HM%2F20260603%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260603T130200Z&X-Amz-Expires=300&X-Amz-SignedHeaders=host&X-Amz-Signature=113611972743a2b5869899c691cada08e011c290fd983ab94254eda87d70d55f)
- [Regras CBJJE 2025 (PDF)](https://cbjje.com.br/assets/regras/regras-cbjje-portugues-2025-jan-02.pdf)
- [Requisitos de Uniforme CBJJ](https://cbjj.com.br/uniform)

## Prompts Testados

**Pontuação**
> "Com base nas regras da IBJJF, quais são as formas de vitória e como funciona o critério de desempate?"

Problema: a IA misturou regras da IBJJF com a CBJJE. Solução: sempre especificar a federação no prompt.

**Penalidades**
> "Liste todas as situações que geram punição segundo o regulamento IBJJF, agrupadas por categoria."

Problema: a IA inventou artigos que não existem. Solução: pedir sempre que cite o número do artigo para validar.

**Comparativo**
> "Crie uma tabela comparando IBJJF e CBJJE: pontuação, tempo de luta por faixa e técnicas proibidas."

Problema: comparação imprecisa quando só um PDF estava carregado. Solução: garantir upload de todas as fontes antes.

**Kimono**
> "Quais são os requisitos obrigatórios de kimono segundo a CBJJ? Liste medidas de manga, lapela e calça."

Funcionou bem na primeira tentativa.

## Resumo

**Pontuação IBJJF**

| Ação | Pontos |
|------|--------|
| Takedown / derrubada | 2 |
| Joelho no ventre | 2 |
| Passagem de guarda | 3 |
| Monte / costas com ganchos | 4 |
| Vantagem | 1 |

Desempate: pontos → vantagens → última ação ofensiva → decisão arbitral.

**Formas de vitória:** finalização, pontos, WO, desqualificação, decisão arbitral.

**Kimono (CBJJ):** cor única (branco, azul ou preto), lapela mínima de 1,3 cm de espessura e 4 cm de largura, folga mínima de 7 cm na manga e na calça.

## Glossário

| Termo | Significado |
|-------|-------------|
| Sweep | Raspagem — inverter posição saindo de baixo para cima (2 pts) |
| Takedown | Derrubada em pé para o chão (2 pts) |
| Mount | Monte — estar sobre o torso do adversário (4 pts) |
| Back take | Posição nas costas com ganchos (4 pts) |
| Submission | Finalização por chave ou estrangulamento |
| Advantage | Vantagem — quase-pontuação ou tentativa ofensiva |
| Stalling | Jogar passivo para ganhar no tempo — gera punição |
| Slam | Arremesso no chão — proibido em todas as faixas |
| Heel hook | Chave de joelho/tornozelo — restrita a faixas avançadas |
| DQ | Desqualificação por punições ou infração grave |

## Prompts Reutilizáveis

```
"Com base no regulamento da [IBJJF/CBJJE], resuma as formas de pontuação, critérios de desempate e formas de vitória."
```

```
"Liste as situações que geram punição segundo a [IBJJF/CBJJE], separando por categoria. Cite o artigo de referência."
```

```
"Crie uma tabela comparando IBJJF e CBJJE para: [pontuação / técnicas proibidas por faixa / tempo de luta]."
```

```
"Segundo o regulamento da [IBJJF/CBJJE], a técnica [X] é permitida na categoria [faixa + gênero + idade]?"
```

```
"Crie 10 perguntas de múltipla escolha sobre as regras de pontuação e penalidades do Jiu-Jitsu, com gabarito comentado."
```