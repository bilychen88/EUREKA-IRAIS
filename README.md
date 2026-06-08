# Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer

**Bidong Chen, Lingui Li**

[[`Paper PDF`](./Bidong%20Chen_ICML_2026_Amodal_Instance_Segmentation_with_IRAIS_Dataset_for_Sim_to_Real_Transfer.pdf)] [[`Reading Notes (ZH)`](./comprehension/comprehension.md)]

This repository presents three core components from **Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer**: `MaviGen`, `Sim-to-Real`, and `EUREKA`. The overall goal is to improve real-world amodal instance segmentation in heavily occluded retail scenes via geometry-controllable synthetic data and a unified modeling approach.

<p align="center">
  <img src="/assets/figure7.png" alt="Figure 7 qualitative results across benchmarks" width="90%"/>
</p>

The paper shows strong and consistent amodal segmentation quality across multiple AIS benchmarks. Compared with representative baselines such as APSNet, VRSP-Net, ORCNN, and AISFormer, the proposed method achieves clearly stronger overall performance in both retail occlusion settings and open-world scenes.

## Sim-to-Real Generalization: 3D-IRAIS -> Real-IRAIS

<p align="center">
  <img src="/assets/table3.png" alt="Sim-to-real results" width="95%"/>
</p>

Under the `3D-IRAIS -> Real-IRAIS` setting, the model is trained only on synthetic data and still achieves clearly stronger amodal and visible metrics on real retail images. This result highlights the paper's strong sim-to-real generalization capability.

<p align="center">
  <img src="/assets/MaviGen.png" alt="MaviGen pipeline overview" width="100%"/>
</p>

## Data Generation: MaviGen

`MaviGen` is the data generation engine of this work. It automatically builds 3D retail scenes and produces scalable synthetic training data. Beyond amodal labels, it also provides geometry signals such as depth, occlusion order, and camera parameters, enabling richer supervision for sim-to-real learning.

<p align="center">
  <img src="/assets/EUREKA.png" alt="EUREKA architecture overview" width="100%"/>
</p>

## Model: EUREKA

`EUREKA` is the proposed amodal instance segmentation model. It uses a unified instance representation to jointly handle visible-region prediction and full amodal completion, forming the core model component of the overall pipeline together with `MaviGen` and `IRAIS`.

## Authors

- Bidong Chen
- Lingui Li
