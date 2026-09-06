# Tactile Sensing and Manipulation

[← Back to index](../README.md)

## Sensors and simulation

- **[GelSight: High-Resolution Robot Tactile Sensors for Estimating Geometry and Force](https://doi.org/10.3390/s17122768)** — Yuan, Dong, and Adelson, 2017. A widely used optical tactile-sensing principle for contact geometry and force.
- **[DIGIT: A Novel Design for a Low-Cost Compact High-Resolution Tactile Sensor with Application to In-Hand Manipulation](https://arxiv.org/abs/2005.14679)** · [Project](https://digit.ml/) — Lambeta et al., 2020. A compact, manufacturable vision-based tactile sensor.
- **[TACTO: A Fast, Flexible, and Open-Source Simulator for High-Resolution Vision-Based Tactile Sensors](https://arxiv.org/abs/2012.08456)** · [Code](https://github.com/facebookresearch/tacto) — Wang et al., 2021. Enables fast simulated tactile rendering for learning and prototyping.
- **[AnySkin: Plug-and-Play Skin Sensing for Robotic Touch](https://arxiv.org/abs/2409.08276)** · [Project](https://any-skin.github.io/) — Bhirangi et al., 2024. **Preprint.** Focuses on replaceability and cross-instance generalization without per-sensor calibration.

## Learning with touch

- **[Learning to See before Learning to Act: Visual Pre-training for Manipulation](https://arxiv.org/abs/2107.00646)** — Yen-Chen et al., 2022. Useful context for comparing visual and multimodal representation learning.
- **[Touch and Go: Learning from Human-Collected Vision and Touch](https://arxiv.org/abs/2211.12498)** · [Project](https://touch-and-go.github.io/) — Yang et al., 2022. Learns aligned visual-tactile representations from in-the-wild human data.
- **[Dexterity from Touch: Self-Supervised Pre-Training of Tactile Representations with Robotic Play](https://proceedings.mlr.press/v229/guzey23a.html)** · [Project](https://tactile-dexterity.github.io/) — Guzey et al., 2023. T-Dex studies self-supervised tactile representations for precise dexterous manipulation.

## Practical checklist

When comparing tactile systems, record:

- sensing principle, spatial resolution, sampling rate, and usable contact area;
- sensor-to-sensor variation and calibration requirements;
- durability, replaceability, wiring, and mechanical integration;
- simulation-to-real assumptions and lighting/material sensitivity;
- whether policies are tested across new objects, tasks, and sensor instances.
