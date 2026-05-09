# EUREKA-IRAIS: Amodal Instance Segmentation for Sim-to-Real Transfer

[![Paper](https://pfst.cf2.poecdn.net/base/image/2be0e06e99303c917fd1d7524cde71aab5065ef80caadca2c828fe8b0e0f84d7?pmaid=615719551)][paper]
[![Project Page](https://pfst.cf2.poecdn.net/base/image/0d9b84d07bd2fa82bb5490a2becf12b1ee8360946499ccee48760d2edc10424f?pmaid=615719549)][project]
[![License](https://img.shields.io/badge/License-[LICENSE_NAME]-green)][license]
[![Dataset](https://pfst.cf2.poecdn.net/base/image/6972aa3655a10a08e5927958d4ead8fa31c9cd3c9cdbfe2ce8675b1996cf6cec?pmaid=615719548)][dataset]

Official repository for **"Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer"**.  
This repo provides code, datasets (EUREKA / IRAIS), training & evaluation scripts, and baseline models.

> **Keywords**: Amodal Instance Segmentation, Sim-to-Real Transfer, Synthetic-to-Real, Occlusion Reasoning, Instance Segmentation

---

## ✨ News

- **2026-07-30**: Initial release of code and configs. *(planned)*
- **YYYY-MM-DD**: EUREKA pretrained models vX.Y released.
- **YYYY-MM-DD**: IRAIS dataset vX.Y released.

---

## Overview

Amodal instance segmentation aims to predict **complete object masks** including **occluded regions**.  
This project focuses on **sim-to-real transfer** using **EUREKA** (synthetic) and **IRAIS** (real or mixed) datasets to improve robustness under occlusion.

**Contributions (example)**:
- A new dataset: **IRAIS** for amodal segmentation and sim-to-real transfer.
- A synthetic dataset: **EUREKA** with controllable occlusions and domain randomization.
- A baseline/approach: **[METHOD_NAME]** for improved transfer performance.
- Benchmarks and evaluation protocols.

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
@inproceedings{eureka_irais_2026,
  title     = {Amodal Instance Segmentation with IRAIS Dataset for Sim-to-Real Transfer},
  author    = {Author 1 and Author 2 and Author 3},
  booktitle = {Conference/Workshop Name},
  year      = {2026},
  url       = {PAPER_URL}
}
