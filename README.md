# SlimTrack

The implementation of my graduation project (awarded as Outstanding Graduation Thesis).

## Highlight

### :bookmark:Brief Introduction

The proposed method is inspired by the idea of [Slimmable Neural Networks](https://arxiv.org/abs/1812.08928). On the main-stream benchmarks, our tracker (named SlimTrack) consistently performs on-par or better than the baseline tracker [SiamRPN++](https://arxiv.org/abs/1812.11703). Note that due to the hierarchical weight sharing design, our parameters are only 40% of SiamRPN++ in the sum of all configurations. Moreover, without any downloading and offloading, the proposed tracker can dynamically switch the computational overhead according to the on-device resource constraints and real-time response requirements.

## Acknowledgement

:heart::heart::heart:Our idea is implemented base on the following projects. We really appreciate their great code!

- [PySOT](https://github.com/STVIR/pysot)
- [S-Net](https://github.com/JiahuiYu/slimmable_networks)
- [DS-Net](https://github.com/changlin31/DS-Net)

