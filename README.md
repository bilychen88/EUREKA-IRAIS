<h1 align="center">
  🎆 Amodal Instance Segmentation with IRAIS:<br/>Sim-to-Real Transfer 🎆
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/ICML-2026-blue?style=for-the-badge&logo=academia&logoColor=white" alt="ICML 2026"/>
  <img src="https://img.shields.io/badge/🏆-Top_Conference-gold?style=for-the-badge" alt="Top Conference"/>
  <img src="https://img.shields.io/badge/✨-Accepted-brightgreen?style=for-the-badge" alt="Accepted"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=FF6B6B&center=true&vCenter=true&multiline=true&width=600&height=60&lines=🔥+State-of-the-Art+Amodal+Segmentation;🚀+Sim-to-Real+Transfer+Learning" alt="Typing SVG" />
</p>

<p align="center">
  ✨ <b>Bidong Chen</b>, <b>Lingui Li</b> ✨
</p>

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/📄_Paper-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Paper"/>
  </a>
  &nbsp;
  <a href="#">
    <img src="https://img.shields.io/badge/🌐_Project-Page-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Project Page"/>
  </a>
  &nbsp;
  <a href="https://pan.baidu.com/s/17X0xudMqli1AU4AB0pFRCQ?pwd=jwtq">
    <img src="https://img.shields.io/badge/📦_Dataset-Download-green?style=for-the-badge&logo=dropbox&logoColor=white" alt="Dataset"/>
  </a>
  &nbsp;
  <a href="#">
    <img src="https://img.shields.io/badge/💻_Code-GitHub-black?style=for-the-badge&logo=github&logoColor=white" alt="Code"/>
  </a>
</p>

---

<!-- <p align="center">
  <img src="https://img.shields.io/github/stars/your-repo?style=social" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/your-repo?style=social" alt="Forks"/>
  <img src="https://img.shields.io/github/watchers/your-repo?style=social" alt="Watchers"/>
</p> -->



<p align="center">
  <img src="Overall.png" alt="Overall Framework" width="100%"/>
</p>

## 📌 Overview

This repository provides the official implementation of **"Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer"** (ICML 2026). We present three core components:

| Component | Description |
|-----------|-------------|
| 🎨 **MaviGen** | Geometry-controllable synthetic data generation engine |
| 📊 **IRAIS** | Large-scale amodal instance segmentation dataset for retail scenes |
| 🤖 **EUREKA** | Unified amodal instance segmentation model |

---

## 🔥 Highlights

<table>
  <tr>
    <td>🏆</td>
    <td><b>State-of-the-art</b> amodal segmentation on multiple AIS benchmarks</td>
  </tr>
  <tr>
    <td>🚀</td>
    <td><b>Zero-shot sim-to-real transfer</b>: Train on synthetic data, deploy on real images</td>
  </tr>
  <tr>
    <td>📦</td>
    <td><b>Rich annotations</b>: Amodal masks, depth, occlusion order, camera parameters</td>
  </tr>
</table>

---

## 📊 Results

### Qualitative Comparison

<p align="center">
  <img src="figure7.png" alt="Qualitative results across benchmarks" width="90%"/>
</p>

### Sim-to-Real Generalization (3D-IRAIS → Real-IRAIS)

<p align="center">
  <img src="table3.png" alt="Sim-to-real results" width="95%"/>
</p>

---

## 🛠️ Method

### 🎨 MaviGen: Synthetic Data Generation

<p align="center">
  <img src="MaviGen.png" alt="MaviGen pipeline" width="100%"/>
</p>

### 🤖 EUREKA: Unified Amodal Segmentation

<p align="center">
  <img src="EUREKA.png" alt="EUREKA architecture" width="100%"/>
</p>

---

## 📂 Datase [Coming Soon]  

🔗 **Download**: [Baidu Netdisk](https://pan.baidu.com/s/17X0xudMqli1AU4AB0pFRCQ?pwd=jwtq) (提取码: jwtq)

---

## 📝 Citation

```bibtex
@inproceedings{chen2026amodal,
  title={Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer},
  author={Chen, Bidong and Li, Lingui},
  booktitle={ICML},
  year={2026}
}
