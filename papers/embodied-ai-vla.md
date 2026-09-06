# Embodied AI and Vision-Language-Action Models

[← Back to index](../README.md)

This area changes quickly. Entries are organized by conceptual lineage, and preprints are labeled explicitly.

## Language-conditioned robotics

- **[Do As I Can, Not As I Say: Grounding Language in Robotic Affordances](https://arxiv.org/abs/2204.01691)** · [Project](https://say-can.github.io/) — Ahn et al., 2022. SayCan combines language-model planning with learned skill affordances.
- **[PaLM-E: An Embodied Multimodal Language Model](https://arxiv.org/abs/2303.03378)** · [Project](https://palm-e.github.io/) — Driess et al., 2023. Injects continuous embodied observations into a large language model.

## Robotics Transformer lineage

- **[RT-1: Robotics Transformer for Real-World Control at Scale](https://arxiv.org/abs/2212.06817)** · [Project](https://robotics-transformer1.github.io/) — Brohan et al., 2022. Scales language-conditioned policies across many real-robot tasks.
- **[RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control](https://arxiv.org/abs/2307.15818)** · [Project](https://robotics-transformer2.github.io/) — Brohan et al., 2023. Co-fine-tunes vision-language models to emit robot actions.
- **[Open X-Embodiment: Robotic Learning Datasets and RT-X Models](https://arxiv.org/abs/2310.08864)** · [Project](https://robotics-transformer-x.github.io/) — Open X-Embodiment Collaboration, 2023. Standardizes diverse robot datasets and trains cross-embodiment policies.

## Open generalist policies

- **[Octo: An Open-Source Generalist Robot Policy](https://arxiv.org/abs/2405.12213)** · [Project](https://octo-models.github.io/) — Octo Model Team et al., 2024. A transformer policy designed for adaptation across robot platforms and tasks.
- **[OpenVLA: An Open-Source Vision-Language-Action Model](https://proceedings.mlr.press/v270/kim25c.html)** · [Project](https://openvla.github.io/) — Kim et al., CoRL 2024. An openly released VLA model built from a pretrained vision-language backbone.
- **[RDT-1B: A Diffusion Foundation Model for Bimanual Manipulation](https://arxiv.org/abs/2410.07864)** · [Project](https://rdt-robotics.github.io/rdt-robotics/) — Liu et al., ICLR 2025. A large diffusion transformer for cross-robot and bimanual manipulation.
- **[π0: A Vision-Language-Action Flow Model for General Robot Control](https://arxiv.org/abs/2410.24164)** · [Project](https://www.pi.website/blog/pi0) — Black et al., 2024. **Preprint.** Uses flow matching to produce continuous action chunks across embodiments.
- **[π0.5: A Vision-Language-Action Model with Open-World Generalization](https://proceedings.mlr.press/v305/black25a.html)** · [Project](https://www.pi.website/blog/pi05) — Black et al., CoRL 2025. Extends generalist policies toward open-world task and environment transfer.
- **[GR00T N1: An Open Foundation Model for Generalist Humanoid Robots](https://arxiv.org/abs/2503.14734)** · [Code](https://github.com/NVIDIA/Isaac-GR00T) — NVIDIA et al., 2025. **Preprint.** A dual-system foundation model for humanoid manipulation.

## How to evaluate a VLA paper

Look beyond average success rate:

- Are evaluation tasks, objects, scenes, instructions, and embodiments genuinely held out?
- Is the training mixture disclosed well enough to detect overlap?
- Are latency, action rate, hardware, and safety interventions reported?
- Does the comparison control for data volume and pretrained backbones?
- Are checkpoints, code, data, and evaluation protocols actually available?
