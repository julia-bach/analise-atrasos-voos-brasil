# O Relógio dos Céus: como os atrasos mudaram no Brasil

**Dados**: ANAC VRA (2022–2024) + Airport Codes (DataHub).
**Metodologia**: atraso operacional definido como diferença entre horário realizado e previsto (partida prioritária; se indisponível, chegada). Consideramos atraso quando **>= 15 minutos**.

## O panorama
No período analisado (2022-2024), os atrasos aumentaram em 45816 ocorrências (total).
O aeroporto com mais atrasos foi **SBGR** com 85361 registros >=15min.
Em 2022, a companhia com mais atrasos foi **GLO** (34008).
Em 2023, a companhia com mais atrasos foi **TAM** (45548).
Em 2024, a companhia com mais atrasos foi **AZU** (49410).

## Quando e onde
- **Dias da semana**: veja os gráficos por ano e compare padrões (ex.: picos às segundas ou sextas).
- **Períodos do dia**: manhã x tarde x noite x madrugada — qual concentra mais atrasos em cada ano?
- **Aeroportos**: top 10 no período e sua evolução ano a ano.

## Companhias
- Destaque para a companhia com mais atrasos em cada ano (gráficos gerados).

## Limitações
- Colunas do VRA mudam levemente ao longo do tempo. Implementamos detecção heurística (nomes contendo *prev*, *real*, *part*, *cheg*). Se a sua amostra tiver nomes distintos, ajuste `guia`.
- Análise considera atraso >= 15 min; outras definições podem ser testadas alterando `is_atraso_15`.

## Reprodutibilidade
- Código e links diretos no notebook. Exporte as tabelas em `output/` para anexos e figure captions no seu post.

*Atualizado em: 2025-09-26 22:51*
