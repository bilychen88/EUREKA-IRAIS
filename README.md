# Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer

<p align="center">
  <b>ICML 2026</b>
</p>

<p align="center">
  <b>Bidong Chen</b><sup>†1,2</sup>, <b>Lingui Li</b><sup>†3</sup>
</p>

<p align="center">
  <sup>1</sup>Department of Informatics Engineering, University of Coimbra, Portugal<br/>
  <sup>2</sup>Faculty of Applied Sciences, Macao Polytechnic University, Macao, China<br/>
  <sup>3</sup>School of Modern Information Industry, Guangzhou College of Commerce, China
</p>

<p align="center">
  <sup>†</sup>Corresponding author
</p>

<p align="center">
  <a href="#">Paper</a> | <a href="#">Project Page</a> | <a href="https://pan.baidu.com/s/17X0xudMqli1AU4AB0pFRCQ?pwd=jwtq">Dataset</a>
</p>

---

<p align="center">
  <img src="Overall.png" alt="Overall Framework" width="100%"/>
</p>

## 📌 Overview

This repository provides the official implementation of **"Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer"** (ICML 2026). We present three core components:

| Component | Description |
|-----------|-------------|
| **MaviGen** | Geometry-controllable synthetic data generation engine |
| **IRAIS** | Large-scale amodal instance segmentation dataset for retail scenes |
| **EUREKA** | Unified amodal instance segmentation model |

Our approach achieves strong sim-to-real generalization in heavily occluded retail scenarios.

---

## 🔥 Highlights

- ✅ **State-of-the-art** amodal segmentation on multiple AIS benchmarks
- ✅ **Zero-shot sim-to-real transfer**: Train on synthetic data, deploy on real images
- ✅ **Rich annotations**: Amodal masks, depth, occlusion order, camera parameters

---

## 📊 Results

### Qualitative Comparison

<p align="center">
  <img src="figure7.png" alt="Qualitative results across benchmarks" width="90%"/>
</p>

Compared with APSNet, VRSP-Net, ORCNN, and AISFormer, our method achieves superior amodal segmentation quality across both retail and open-world scenes.

### Sim-to-Real Generalization (3D-IRAIS → Real-IRAIS)

<p align="center">
  <img src="table3.png" alt="Sim-to-real results" width="95%"/>
</p>

Training **only** on synthetic data, our model achieves strong performance on real retail images, demonstrating effective sim-to-real transfer.

---

## 🛠️ Method

### MaviGen: Synthetic Data Generation

<p align="center">
  <img src="MaviGen.png" alt="MaviGen pipeline" width="100%"/>
</p>

MaviGen automatically constructs 3D retail scenes and generates scalable synthetic training data with multi-modal annotations including depth, occlusion order, and camera parameters.

### EUREKA: Unified Amodal Segmentation

<p align="center">
  <img src="EUREKA.png" alt="EUREKA architecture" width="100%"/>
</p>

EUREKA adopts a unified instance representation for joint visible-region prediction and amodal completion, forming the core segmentation model of our pipeline.

---

## 📂 Dataset

**IRAIS Dataset** will be publicly available upon paper publication.

🔗 **Download**: [Baidu Netdisk](https://pan.baidu.com/s/17X0xudMqli1AU4AB0pFRCQ?pwd=jwtq) (提取码: jwtq)

---

## 🚀 Getting Started

### Installation

```bash
# Coming soon

### Training
# Coming soon

### Evaluation
# Coming soon


@inproceedings{chen2026amodal,
  title={Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer},
  author={Chen, Bidong and Li, Lingui},
  booktitle={Forty-third International Conference on Machine Learning (ICML)},
  year={2026}
}
