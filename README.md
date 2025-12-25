# UniTacHand: Unified Spatio-Tactile Representation for Human to Robotic Hand Skill Transfer

<div align="center">

[[Website]](https://beingbeyond.github.io/UniTacHand/)
[[arXiv]](https://arxiv.org/abs/2512.21233)

[![Python Version](https://img.shields.io/badge/Python-3.10-blue.svg)]()
[![GitHub license](https://img.shields.io/badge/MIT-blue)]()

</div>
<div align="center">

![](docs/images/pipeline.jpg)

</div>
 we propose **UniTacHand**, a novel unified representation to align robotic tactile information captured by dexterous hands with human hand touch obtained from gloves with sensors. In this paper, we project disparate tactile signals, from both the human haptic gloves and the robotic hands, onto a morphologically consistent 2D surface space of the MANO hand model. Our approach achieves a zero-shot tactile-based policy transfer, in which the policies are solely trained using human data, to a physical robot. We also demonstrate that co-training on mixed data including both human and robotic demonstrations via **UniTacHand** yields a superior capability, enabling policies to achieve better data efficiency with only one-shot demonstration on the real robot. **UniTacHand** provides a general, scalable, and data-efficient pathway for transferring human haptic intelligence to policies on tactile dexterous hands.


# Citation
If you find our work useful, please consider citing us!
```
@article{unitachand,
  title={UniTacHand: Unified Spatio-Tactile Representation for Human to Robotic Hand Skill Transfer},
  author={Zhang, Chi and Cai, Penglin and Yuan, Haoqi and Xu, Chaoyi and Lu, Zongqing},
  journal={arXiv preprint arXiv:2512.21233},
  year={2025}
}
```
