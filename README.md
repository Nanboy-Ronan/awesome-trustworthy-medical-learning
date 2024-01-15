# Med-Safe-ML
Welcome to Med-Safe-ML, a collection of academic articles, published methodology and datasets on trustworthy machine learning in healthcare and medicine.

## Topics

### Explanable Machine Learning
| **Paper Title** | **Year** | **Venue** | **Code** | **Summary** |
| --------------- | :----: | :----: | :----: | ---- |

### Federated Learning
| **Paper Title** | **Year** | **Venue** | **Code** | **Summary** |
| --------------- | :----: | :----: | :----: | ---- |
| FedProto: Federated Prototype Learning across Heterogeneous Clients | 2022 | AAAI | [FedProto](https://github.com/yuetan031/FedProto) | FedProto is a proto-type learning framework in which the clients and server communicate the abstract class prototypes instead of the gradients. The training on each clients aims to minimize the classification error on the local data while keeping the resulting local prototypes sufficiently close to the corresponding global ones. Global model aggregates prototypes. |

### Attacks and Defenses
| **Paper Title** | **Year** | **Venue** | **Code** | **Summary** |
| --------------- | :----: | :----: | :----: | ---- |
| Shared Adversarial Unlearning: Backdoor Mitigation by Unlearning Shared Adversarial Examples | 2023 | NeurIPS | [SAU](https://github.com/SCLBD/BackdoorBench) | The paper proposed Shared Adversarial Unlearning (SAU), which it first generates shared adversarial examples (SAEs), and then, unlearns the generated SAEs such that they are either correctly classfied by the purified model and/or differently classified by the two models. |
| Neural Polarizer: A Lightweight and Effective Backdoor Defense via Purifying Poisoned Features | 2023 | NeurIPS | [Neural Polarizer](https://github.com/SCLBD/BackdoorBench) | This paper propose to insert a learnable neural polarizer into the backdoored model as an intermediate layer, in order to qurify the poisoned sample via filtering trigger information while maintaining benign information. The neural polarizer is linear layer, which requires less data for finetune compared to other fine-tune based method. |