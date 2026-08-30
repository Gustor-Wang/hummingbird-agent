# Hummingbird AFTER rerun (finish gate + small-model degradation) - BEFORE table: BATCH64_SUMMARY.md

Latest attempt per cell; score = deterministic total (timeout counts 0).

| cell | ornith-1.5:35b | gemma4:12b | qwen3.5:4b | gemma4:e2b |
|---|---|---|---|---|
| hummingbird WF-01 | 1.00(2391s) | 1.00(1675s) | 1.00(308s) | 0.79(179s) |
| hummingbird WF-03 | 1.00(391s) | 1.00(2132s) | 1.00(1282s) | 1.00(249s) |
| hummingbird WF-09 | 0.79(345s) | 0.79(1899s) | 0.57(1849s) | 0.50(225s) |
| hummingbird WF-15 | 1.00(921s) | 0.86(1889s) | 0.86(1788s) | 0.71(334s) |

## Means (scored cells; missing model cells excluded from that mean)

| agent | ornith-1.5:35b | gemma4:12b | qwen3.5:4b | gemma4:e2b | overall |
|---|---|---|---|---|---|
| **hummingbird** | 0.947 (n=4) | 0.911 (n=4) | 0.857 (n=4) | 0.750 (n=4) | **0.866** |

## Retried cells (attempt-1 result superseded by latest attempt)

- hummingbird WF-15 gemma4:12b: 2 attempts -> 0.86(1889s) (hummingbird_WF15_gemma4_12b_m1_0830_062342)
