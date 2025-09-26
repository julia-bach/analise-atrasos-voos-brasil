# O Relógio dos Céus: como os atrasos mudaram no Brasil

**Dados**: ANAC VRA (2022–2024) + Airport Codes (DataHub).
**Metodologia**: atraso operacional definido como diferença entre horário realizado e previsto (partida prioritária; se indisponível, chegada). Consideramos atraso quando **>= 15 minutos**.

## O panorama

No período analisado (2022-2024), os atrasos aumentaram em 45816 ocorrências (total).
O aeroporto com mais atrasos foi **SBGR** com 85361 registros >=15min.
Em 2022, a companhia com mais atrasos foi **GLO** (34008).
Em 2023, a companhia com mais atrasos foi **TAM** (45548).
Em 2024, a companhia com mais atrasos foi **AZU** (49410).

## Gráficos

- **Dias da semana**: veja os gráficos por ano para verificar os padrões (ex.: picos às segundas ou sextas).
- **Períodos do dia**: manhã x tarde x noite x madrugada.
- **Aeroportos**: top 10 no período e sua evolução ano a ano.
- Destaque para a companhia com mais atrasos em cada ano.

## Limitações

- Colunas do VRA mudam levemente ao longo do tempo. Implementamos detecção heurística (nomes contendo *prev*, *real*, *part*, *cheg*).
- Análise considera atraso >= 15 min; outras definições podem ser testadas alterando `is_atraso_15`.

*Atualizado em: 2025-09-26 22:51*
