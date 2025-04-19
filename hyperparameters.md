| Runs    | learning rate | weight decay | epochs | optimizer | scheduler | momentum | net class  | batch size | best val accruacy | best epoch |
| -------- | ------- | ------- | ------- | ------- | --------------- | ------- | -------| ------ | ------- | ------- |
| vit_linear  |  0.001   | 0.01 | 100 | SGD | multi_step (milestones=[60, 80], gamma=0.1) | 0.99 | VitLinear | 32 | 0.87 | 71 |
| run1 |  0.01   | 0.01 | 100 | SGD | multi_step (milestones=[60, 80], gamma=0.1) | 0.99 | VitLinear |  32 | 0.86625 | 71 |
| run2 |  0.01   | 0.01 | 100 | SGD | multi_step (milestones=[60, 80], gamma=0.1) | 0.99 | VitLinear |  64 | 0.8713 | 71 |
| run3 |  0.001   | 0.01 | 100 | Adam | multi_step (milestones=[60, 80], gamma=0.1) | 0.99 | VitLinear | 64 | 0.870192 | 71 |
| run4 |  0.01   | 0.01 | 100 | SGD | multi_step (milestones=[60, 80], gamma=0.1) | 0.99 | VPT-Deep| 32 | 0.9225 | 69 |