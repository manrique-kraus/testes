# Relatórios de clustering

Site: https://manrique-kraus.github.io/testes/

Nº = ordem em que o teste foi feito.

## Fase 1: Primeiros testes: MATR, 3 features, K = 2

| Nº | Data | Teste | Datasets | Features | K | Células |
|---|---|---|---|---|---|---|
| 1 | 06/10/2026 | [Capacidade, resistência e RUL: 60 células](https://manrique-kraus.github.io/testes/relatorios/cap-ir-rul_K2_60cel_ciclo100.html) | MATR | cap, ir, rul | 2 | 60 |
| 2 | 06/10/2026 | [Capacidade, resistência e RUL: 100 células](https://manrique-kraus.github.io/testes/relatorios/cap-ir-rul_K2_100cel_ciclo100.html) | MATR | cap, ir, rul | 2 | 100 |
| 3 | 06/10/2026 | [Capacidade, resistência e RUL: 124 células](https://manrique-kraus.github.io/testes/relatorios/cap-ir-rul_K2_124cel_ciclo100.html) | MATR | cap, ir, rul | 2 | 124 |
| 4 | 06/10/2026 | [delta\_t, delta\_ir e fade recente: 60 células](https://manrique-kraus.github.io/testes/relatorios/delta_t-delta_ir-fade_recente_K2_60cel_ciclo100.html) | MATR | delta\_t, delta\_ir, fade\_recente | 2 | 60 |
| 5 | 06/10/2026 | [delta\_t, delta\_ir e fade recente: 100 células](https://manrique-kraus.github.io/testes/relatorios/delta_t-delta_ir-fade_recente_K2_100cel_ciclo100.html) | MATR | delta\_t, delta\_ir, fade\_recente | 2 | 100 |
| 6 | 06/10/2026 | [delta\_t, delta\_ir e fade recente: 124 células](https://manrique-kraus.github.io/testes/relatorios/delta_t-delta_ir-fade_recente_K2_124cel_ciclo100.html) | MATR | delta\_t, delta\_ir, fade\_recente | 2 | 124 |

## Fase 2: Dados do artigo Li et al. (2019)

| Nº | Data | Teste | Datasets | Features | K | Células |
|---|---|---|---|---|---|---|
| 7 | 19/10/2026 | [6 features, K = 4](https://manrique-kraus.github.io/testes/relatorios/artigo-Li2019_v_zero-t_zero-cap_zero-v_full-t_full-cap_full_K4_44cel.html) | Li et al. (2019) | v\_zero, t\_zero, cap\_zero, v\_full, t\_full, cap\_full | 4 | 44 |
| 8 | 19/10/2026 | [6 features, K = 2](https://manrique-kraus.github.io/testes/relatorios/artigo-Li2019_v_zero-t_zero-cap_zero-v_full-t_full-cap_full_K2_44cel.html) | Li et al. (2019) | v\_zero, t\_zero, cap\_zero, v\_full, t\_full, cap\_full | 2 | 44 |
| 9 | 19/10/2026 | [3 features, K = 2](https://manrique-kraus.github.io/testes/relatorios/artigo-Li2019_v_zero-cap_zero-cap_full_K2_44cel.html) | Li et al. (2019) | v\_zero, cap\_zero, cap\_full | 2 | 44 |
| 12 | 04/11/2026 | [3 features, K = 4](https://manrique-kraus.github.io/testes/relatorios/artigo-Li2019_v_zero-cap_zero-cap_full_K4_44cel.html) | Li et al. (2019) | v\_zero, cap\_zero, cap\_full | 4 | 44 |

## Fase 3: BatteryLife: 13 datasets juntos, K = 2, 4 e 10

| Nº | Data | Teste | Datasets | Features | K | Células |
|---|---|---|---|---|---|---|
| 10 | 26/10/2026 | [Capacidade, RUL e knee: K = 4](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_cap-rul-knee_ref100_K4_708cel.html) | 13 datasets Li-ion | cap, rul, knee | 4 | 708 |
| 11 | 03/11/2026 | [Capacidade, RUL e knee: K = 2](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_cap-rul-knee_ref100_K2_708cel.html) | 13 datasets Li-ion | cap, rul, knee | 2 | 708 |
| 13 | 04/11/2026 | [Capacidade, RUL e knee: K = 10](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_cap-rul-knee_ref100_K10_708cel.html) | 13 datasets Li-ion | cap, rul, knee | 10 | 708 |

## Fase 4: BatteryLife: dois estágios (DBSCAN define K + 5 algoritmos)

| Nº | Data | Teste | Datasets | Features | K | Células |
|---|---|---|---|---|---|---|
| 14 | 10/11/2026 | [13 datasets juntos: capacidade, RUL e knee](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_DBSCAN_todos_cap-rul-knee_ref100_K4_671cel.html) | 13 datasets Li-ion | cap, rul, knee | 4 | 671 |
| 15 | 11/11/2026 | [13 datasets juntos: tensão, capacidade e corrente](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_DBSCAN_todos_tensao-cap-corrente_ref100_K17_758cel.html) | 13 datasets Li-ion | tensao, cap, corrente | 17 | 758 |
| 16 | 11/11/2026 | [Cada dataset separado: tensão, capacidade e corrente](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_DBSCAN_cada-dataset_tensao-cap-corrente_ref100.html) | juntos e cada um separado | tensao, cap, corrente | todos=17, ISU\_ILCC=10, MICH=2, SNL=2, XJTU=2 | 758 |

## Fase 5: Comparação de features: estado (ciclo 100) × variação (ciclo 10 ao 100)

| Nº | Data | Teste | Datasets | Features | K | Células |
|---|---|---|---|---|---|---|
| 17 | 17/11/2026 | [MATR: SOH, resistência e temperatura](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_MATR_conjuntos_A_estado_vs_B_variacao_ref100.html) | MATR | A\_estado: soh, r, temp / B\_variacao: dsoh, dr, dtemp | – | 124 |
| 18 | 17/11/2026 | [XJTU: tensão, capacidade e corrente](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_XJTU_conjuntos_A_estado_vs_B_variacao_ref100.html) | XJTU | A\_estado: tensao, cap, corrente / B\_variacao: dtensao, dcap, dcorrente | A\_estado=2 | 47 |
| 19 | 18/11/2026 | [XJTU + ISU\_ILCC: tensão, capacidade e corrente](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_XJTU-ISU_ILCC_conjuntos_A_estado_vs_B_variacao_ref100.html) | XJTU + ISU\_ILCC | A\_estado: tensao, cap, corrente / B\_variacao: dtensao, dcap, dcorrente | A\_estado=12, B\_variacao=2 | 286 |
| 20 | 18/11/2026 | [XJTU + ISU\_ILCC + Tongji: tensão, capacidade e corrente](https://manrique-kraus.github.io/testes/relatorios/BatteryLife-Li_XJTU-ISU_ILCC-Tongji_conjuntos_A_estado_vs_B_variacao_ref100.html) | XJTU + ISU\_ILCC + Tongji | A\_estado: tensao, cap, corrente / B\_variacao: dtensao, dcap, dcorrente | A\_estado=7, B\_variacao=2 | 385 |

## Fase 6: Seleção de características: filtro

| Nº | Data | Teste | Datasets | Features | K | Células |
|---|---|---|---|---|---|---|
| 21 | 24/11/2026 | [Filtro 01: Fisher Score](https://manrique-kraus.github.io/testes/relatorios/Filtro-01_Fisher-Score_XJTU-ISU_ILCC-Tongji.html) | XJTU + ISU\_ILCC + Tongji | A\_base: tensao, cap, corrente / B\_fisher: tensao, tensao\_carga, cap\_carga | A\_base=7, B\_fisher=5 | 385 |
| 22 | 25/11/2026 | [Filtro 01: Fisher Score](https://manrique-kraus.github.io/testes/relatorios/Filtro-01_Fisher-Score_13-datasets.html) | CALCE + HNEI + HUST + ISU\_ILCC + MATR + MICH + MICH\_EXP + RWTH + SNL + Stanford + Tongji + UL\_PUR + XJTU | A\_base: tensao, cap, corrente / B\_fisher: cap, cap\_carga, tempo\_carga | A\_base=17, B\_fisher=6 | 857 |
