# Dynamic Facial Expression Recognition Methods Ranking

## [DFEW Benchmark](https://dfew-dataset.github.io/)

|    Methods                                            | Happy |  Sad  | Neutral | Anger | Surprise | Disgust |  Fear |  **UAR**  |  **WAR**  |
|:-------------:                                        |:-----:|:-----:|:-------:|:-----:|:--------:|:-------:|:-----:|:---------:|:---------:|
|3D Resnet18                                            | 76.32 | 50.21 |  64.18  | 62.85 |   47.52  |   0.00  | 24.56 | **46.52** | **58.27** |
|ResNet18+LSTM                                          | 83.56 | 61.56 |  68.27  | 65.29 |   51.26  |   0.00  | 29.34 | **51.32** | **63.85** |
|Resnet18+GRU                                           | 82.87 | 63.83 |  65.06  | 68.51 |   52.00  |   0.86  | 30.14 | **51.68** | **64.02** |
|[EC-STFL](https://doi.org/10.1145/3394171.3413620)     | 79.18 | 49.05 |  57.85  | 60.98 |   46.15  |   2.76  | 21.51 | **45.35** | **56.51** |
|[Former-DFER](https://doi.org/10.1145/3474085.3475292) | 84.05 | 62.57 |  67.52  | 70.03 |   56.43  |   3.45  | 31.78 | **53.69** | **65.70** |
|[EST](https://arxiv.org/abs/2109.08409)                | 86.87 | 66.58 |  67.18  | 71.84 |   47.53  |   5.52  | 28.49 | **53.43** | **65.85** |
|[STT](https://arxiv.org/abs/2205.04749)                | 87.36 | 67.90 |  64.97  | 71.24 |   53.10  |   3.49  | 34.04 | **54.58** | **66.65** |
|[NR-DFERNet](https://arxiv.org/abs/2206.04975)         | 88.47 | 64.84 |  70.03  | 75.09 |   61.60  |   0.00  | 19.43 | **54.21** | **68.19** |

## [FERV39k Benchmark](https://wangyanckxx.github.io/Proj_CVPR2022_FERV39k.html)

|    Methods                                               | Happy |  Sad  | Neutral | Anger | Surprise | Disgust |  Fear |  **UAR**  |  **WAR**  |
|:-------------:                                           |:-----:|:-----:|:-------:|:-----:|:--------:|:-------:|:-----:|:---------:|:---------:|
|  [Former-DFER](https://doi.org/10.1145/3474085.3475292)  | 67.57 | 44.16 |  51.81  | 48.93 |   25.09  |  10.80  |  9.80 | **36.88** | **45.72** |

## [AFEW Benchmark](https://cs.anu.edu.au/few/AFEW.html)

## [CAER Benchmark](https://caer-dataset.github.io/)