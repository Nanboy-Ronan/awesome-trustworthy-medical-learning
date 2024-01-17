# Med-Safe-ML
Welcome to Med-Safe-ML, a collection of academic articles, published methodology and datasets on trustworthy machine learning in healthcare and medicine.

## Topics

### Explanable Machine Learning
| **Paper Title** | **Year** | **Venue** | **Code** | **Summary** |
| :---------------: | :----: | :----: | :----: | ---- |
| Paying More Attention to Attention: Improving the Performance of Convolutional Neural Networks via Attention Transfer | 2017 | ICLR | [attention-transfer](https://github.com/szagoruyko/attention-transfer) | This paper show that, by properly defining attention for convolutional neural networks, we can actually use this type of information in order to significantly improve the performance of a student CNN
network by forcing it to mimic the attention maps of a powerful teacher network.
To that end, we propose several novel methods of transferring attention, showing consistent improvement across a variety of datasets and convolutional neural network architectures. |

### Federated Learning
| **Paper Title** | **Year** | **Venue** | **Code** | **Summary** |
| :---------------: | :----: | :----: | :----: | ---- |
| FedProto: Federated Prototype Learning across Heterogeneous Clients | 2022 | AAAI | [FedProto](https://github.com/yuetan031/FedProto) | FedProto is a proto-type learning framework in which the clients and server communicate the abstract class prototypes instead of the gradients. The training on each clients aims to minimize the classification error on the local data while keeping the resulting local prototypes sufficiently close to the corresponding global ones. Global model aggregates prototypes. |

### Attacks and Defenses
| **Paper Title** | **Year** | **Venue** | **Code** | **Summary** |
| :---------------: | :----: | :----: | :----: | ---- |
| Shared Adversarial Unlearning: Backdoor Mitigation by Unlearning Shared Adversarial Examples | 2023 | NeurIPS | [SAU](https://github.com/SCLBD/BackdoorBench) | The paper proposed Shared Adversarial Unlearning (SAU), which it first generates shared adversarial examples (SAEs), and then, unlearns the generated SAEs such that they are either correctly classfied by the purified model and/or differently classified by the two models. |
| Neural Polarizer: A Lightweight and Effective Backdoor Defense via Purifying Poisoned Features | 2023 | NeurIPS | [Neural Polarizer](https://github.com/SCLBD/BackdoorBench) | This paper propose to insert a learnable neural polarizer into the backdoored model as an intermediate layer, in order to qurify the poisoned sample via filtering trigger information while maintaining benign information. The neural polarizer is linear layer, which requires less data for finetune compared to other fine-tune based method. |

### Other Awesome Lists
| **Topic** | **Year** | **Paper** | **Code** |
| :---------------: | :----: | :----: | :----: |
| CLIP in medical imaging: A comprehensive survey | 2023 | [CLIP in medical imaging: A comprehensive survey](https://arxiv.org/pdf/2312.07353.pdf) | [Awesome-CLIP-in-Medical-Imaging](Awesome-CLIP-in-Medical-Imaging)|
| Medical Large Multimodal Models | 2024 | N/A | [Awesome-Multimodal-Medical-Large-Models](https://github.com/LarryUESTC/Awesome-Multimodal-Medical-Large-Models?tab=readme-ov-file) |