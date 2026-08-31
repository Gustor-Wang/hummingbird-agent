# LRAB-H full layer (4 agents x 4 models, 90min budget, LH-03 kill-resume)

Latest attempt per cell; score = deterministic total (timeout counts 0).

| cell | ornith-1.5:35b | gemma4:12b | qwen3.5:4b | gemma4:e2b |
|---|---|---|---|---|
| hummingbird LH-01 | 1.00(1201s) | 0.93(2478s) | 0.07(1844s) | 0.18(593s) |
| hummingbird LH-02 | 0.94(502s) | 0.73(2873s) | 0.06(1540s) | 0.88(206s) |
| hummingbird LH-03 | 1.00(1390s) | TMO(5401s) | 1.00(977s) | 0.49(688s) |
| opencode LH-01 | 0.71(805s) | 0.00(308s) | 0.00(256s) | 0.00(42s) |
| opencode LH-02 | 0.94(235s) | 0.94(1044s) | 0.06(1762s) | 0.00(63s) |
| opencode LH-03 | 0.51(1139s) | 0.31(245s) | 0.31(58s) | 0.31(76s) |
| agent-mini LH-01 | 0.00(46s) | 0.07(466s) | 0.93(414s) | 0.07(108s) |
| agent-mini LH-02 | 0.00(10s) | 0.94(216s) | 0.94(129s) | 0.13(91s) |
| agent-mini LH-03 | 0.36(111s) | 0.65(580s) | 0.31(79s) | 0.31(36s) |
| goose LH-01 | 1.00(1118s) | 0.89(742s) | 0.07(1401s) | 0.00(62s) |
| goose LH-02 | 0.94(409s) | 0.88(1212s) | 0.00(128s) | 0.00(31s) |
| goose LH-03 | 1.00(926s) | 0.31(3130s) | 0.31(118s) | 0.31(55s) |

## Means (scored cells; missing model cells excluded from that mean)

| agent | ornith-1.5:35b | gemma4:12b | qwen3.5:4b | gemma4:e2b | overall |
|---|---|---|---|---|---|
| **hummingbird** | 0.980 (n=3) | 0.828 (n=2) | 0.377 (n=3) | 0.514 (n=3) | **0.661** |
| **opencode** | 0.720 (n=3) | 0.415 (n=3) | 0.122 (n=3) | 0.102 (n=3) | **0.340** |
| **agent-mini** | 0.121 (n=3) | 0.553 (n=3) | 0.725 (n=3) | 0.169 (n=3) | **0.392** |
| **goose** | 0.980 (n=3) | 0.692 (n=3) | 0.126 (n=3) | 0.102 (n=3) | **0.475** |

## Retried cells (attempt-1 result superseded by latest attempt)

- hummingbird LH-01 gemma4:e2b: 2 attempts -> 0.18(593s) (hummingbird_LH01_gemma4_e2b_m0_0830_183139)
- hummingbird LH-03 gemma4:12b: 2 attempts -> TMO(5401s) (hummingbird_LH03_gemma4_12b_m1_0830_132325)
- hummingbird LH-03 qwen3.5:4b: 2 attempts -> 1.00(977s) (hummingbird_LH03_qwen3.5_4b_m0_0830_181501)
- goose LH-02 qwen3.5:4b: 2 attempts -> 0.00(128s) (goose_LH02_qwen3.5_4b_m0_0831_123739)
