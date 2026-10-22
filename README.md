# GeoDSE-Net

**GeoDSE-Net: Imaging-Mechanism-Guided View-Robust Fine-Grained SAR Target Recognition**

This repository is being prepared for the release of GeoDSE-Net. The implementation and trained weights will be made publicly available.

## Overview

Target scattering responses vary substantially across viewing geometries, while structural differences among targets can provide discriminative scattering cues under comparable observation conditions. GeoDSE-Net explicitly incorporates relative azimuth and depression angle to guide scattering feature alignment and adaptation for fine-grained SAR target recognition.

The framework consists of three modules:

- **SRAE — Scattering-Response Relative-Azimuth Estimator:** estimates a circular posterior over relative azimuth from dominant scattering responses.
- **PRAF — Probabilistic Relative-Azimuth Alignment Fusion:** aligns and fuses directional scattering features in a canonical target frame under multiple probable azimuth hypotheses.
- **IMDA — Imaging-Mechanism-Coupled Depression Adapter:** adapts feature sampling using depression angles and geometric constraints derived from height displacement and radar shadows.

## Framework

![Overall architecture of GeoDSE-Net](assets/Framework.png)

## Contact

For questions regarding the paper or code, please contact:

**Yifei Yin**  
Beijing Institute of Technology  
Email: 513843129@qq.com

You are also welcome to open an issue in this repository.
