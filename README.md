# EUREKA-IRAIS
Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer, EUREKA, IRAIS Datasets
# EUREKA-IRAIS: Amodal Instance Segmentation for Sim-to-Real Transfer

[![Paper](https://img.shields.io/badge/Paper-PDF-red)]([PAPER_URL])
[![Project Page](https://img.shields.io/badge/Project-Page-blue)]([PROJECT_PAGE_URL])
[![License](https://img.shields.io/badge/License-[LICENSE_NAME]-green)]([LICENSE_URL])
[![Dataset](https://img.shields.io/badge/Dataset-EUREKA%20%7C%20IRAIS-orange)]([DATASET_URL])

Official repository for **"Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer"**.  
This repo provides code, datasets (EUREKA / IRAIS), training & evaluation scripts, and baseline models.

> **Keywords**: Amodal Instance Segmentation, Sim-to-Real Transfer, Synthetic-to-Real, Occlusion Reasoning, Instance Segmentation

---

## ✨ News

- **[2026-07-30]**: Initial release of code and configs.
- **[YYYY-MM-DD]**: EUREKA Pretrained models v[VERSION] released.
- **[YYYY-MM-DD]**: IRAIS dataset v[VERSION] released.

---

## Overview

Amodal instance segmentation aims to predict **complete object masks** including **occluded regions**.  
This project focuses on **sim-to-real transfer** using **EUREKA** (synthetic) and **IRAIS** (real or mixed) datasets to improve robustness under occlusion.

**Contributions (example)**:
- A new dataset: **IRAIS** for amodal segmentation and sim-to-real transfer.
- A synthetic dataset: **EUREKA** with controllable occlusions and domain randomization.
- A baseline/approach: [METHOD_NAME] for improved transfer performance.
- Benchmarks and evaluation protocols.

> Replace the bullets above with your actual contributions.

---

## Repository Structure

```text
.
├── configs/                 # training/eval configs
├── datasets/
│   ├── eureka/              # dataset scripts or meta files
│   └── irais/
├── tools/                   # training/eval tools
├── scripts/                 # helper scripts (download, preprocess, etc.)
├── src/                     # core library code
├── checkpoints/             # (optional) pretrained weights (or leave empty)
├── docs/                    # additional documentation
└── README.md

---

## Citation

If you find this project useful in your research, please cite our paper and datasets.

### Paper

```bibtex
@inproceedings{eureka_irais_2026,
  title     = {Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer},
  author    = {[Author 1] and [Author 2] and [Author 3]},
  booktitle = {[Conference/Workshop Name]},
  year      = {2026},
  pages     = {[xx--yy]},
  doi       = {[DOI]},
  url       = {[PAPER_URL]},
}
