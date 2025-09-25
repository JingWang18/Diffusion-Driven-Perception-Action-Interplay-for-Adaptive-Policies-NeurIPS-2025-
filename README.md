# [NeurIPS 2025] Act to See, See to Act: Diffusion-Driven Perception–Action Interplay for Adaptive Policies

This repository contains the official implementation of our NeurIPS 2025 paper *“Act to See, See to Act: Diffusion-Driven Perception–Action Interplay for Adaptive Policies.”*

## 📖 Overview

Robots often fail in dynamic, uncertain environments because perception and action are treated as separate modules. Our work bridges this gap by introducing **DP-AG (Diffusion Policy with Action Guidance)**, a framework that tightly couples perception and action through diffusion models.

* **Perception adapts with action feedback**: sensory representations evolve continuously as actions unfold.
* **Action refines with updated perception**: diffusion-guided policies adjust decisions in real time.
* This closed perception–action loop yields policies that are **robust, adaptive, and effective** in both simulation and real-world tasks.

## 🚀 Features

* Implementation of **DP-AG** built on top of Diffusion Policy.
* Support for standard benchmarks: **Robomimic, Franka Kitchen, Push-T, Dynamic Push-T**.

## 📊 Results

DP-AG significantly outperforms state-of-the-art baselines:

* +6% on Push-T and +13% on Dynamic Push-T.
* Higher success rates and smoother actions across Robomimic and Franka Kitchen.
* Up to **23% improvement** in real-world manipulation tasks compared to diffusion policy.
  

## 📑 Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{wang2025act,
  title={Act to See, See to Act: Diffusion-Driven Perception--Action Interplay for Adaptive Policies},
  author={Wang, Jing and Peng, Weiting and Tang, Jing and Gong, Zeyu and Wang, Xihua and Tao, Bo and Cheng, Li},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
  year={2025}
}
```
