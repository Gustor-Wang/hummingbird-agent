# LRAB 64-cell batch summary (2026-08-29/30, tasks WF-01/03/09/15 x 4 agents x 4 models)

Latest attempt per cell; score = deterministic total (timeout counts 0).

| cell | ornith-1.5:35b | gemma4:12b | qwen3.5:4b | gemma4:e2b |
|---|---|---|---|---|
| hummingbird WF-01 | 1.00(2236s) | 1.00(2057s) | 1.00(331s) | 0.79(120s) |
| hummingbird WF-03 | 1.00(456s) | 1.00(1683s) | 0.79(2309s) | 1.00(243s) |
| hummingbird WF-09 | 0.89(549s) | 0.79(1538s) | 0.79(1155s) | 0.50(281s) |
| hummingbird WF-15 | 1.00(1220s) | 0.86(2250s) | 1.00(770s) | 0.43(489s) |
| opencode WF-01 | 1.00(938s) | 0.00(210s) | 0.79(635s) | 0.00(58s) |
| opencode WF-03 | 1.00(856s) | 0.00(1435s) | 1.00(1124s) | 0.00(77s) |
| opencode WF-09 | 0.50(966s) | 0.29(1810s) | 0.00(117s) | 0.00(54s) |
| opencode WF-15 | 1.00(826s) | 0.71(2199s) | 0.57(1159s) | 0.00(45s) |
| agent-mini WF-01 | 0.00(144s) | 1.00(351s) | 0.00(426s) | 0.29(66s) |
| agent-mini WF-03 | 0.00(28s) | 0.50(1953s) | 0.79(228s) | 0.29(81s) |
| agent-mini WF-09 | 0.00(35s) | 0.79(578s) | 0.29(146s) | 0.00(47s) |
| agent-mini WF-15 | 0.00(26s) | 0.71(619s) | 0.29(185s) | 0.29(53s) |
| goose WF-01 | 1.00(1007s) | 0.00(580s) | 1.00(554s) | 0.00(175s) |
| goose WF-03 | 0.79(974s) | 0.00(891s) | 0.79(1290s) | 0.00(69s) |
| goose WF-09 | 0.29(1178s) | 0.79(735s) | 0.29(992s) | 0.79(242s) |
| goose WF-15 | 0.86(2128s) | 0.93(1527s) | 0.29(1422s) | 0.50(294s) |

## Means (scored cells; missing model cells excluded from that mean)

| agent | ornith-1.5:35b | gemma4:12b | qwen3.5:4b | gemma4:e2b | overall |
|---|---|---|---|---|---|
| **hummingbird** | 0.973 (n=4) | 0.911 (n=4) | 0.893 (n=4) | 0.679 (n=4) | **0.864** |
| **opencode** | 0.875 (n=4) | 0.250 (n=4) | 0.589 (n=4) | 0.000 (n=4) | **0.429** |
| **agent-mini** | 0.000 (n=4) | 0.750 (n=4) | 0.340 (n=4) | 0.214 (n=4) | **0.326** |
| **goose** | 0.732 (n=4) | 0.429 (n=4) | 0.590 (n=4) | 0.322 (n=4) | **0.518** |

## Retried cells (attempt-1 result superseded by latest attempt)

- hummingbird WF-09 gemma4:12b: 2 attempts -> 0.79(1538s) (hummingbird_WF09_gemma4_12b_m1_0829_125631)
- hummingbird WF-09 qwen3.5:4b: 2 attempts -> 0.79(1155s) (hummingbird_WF09_qwen3.5_4b_m1_0829_152501)
- hummingbird WF-15 ornith-1.5:35b: 2 attempts -> 1.00(1220s) (hummingbird_WF15_ornith1.5_35b_m1_0829_105251)
- goose WF-01 gemma4:12b: 2 attempts -> 0.00(580s) (goose_WF01_gemma4_12b_m1_0829_232929)
- goose WF-03 gemma4:12b: 2 attempts -> 0.00(891s) (goose_WF03_gemma4_12b_m1_0830_001929)
