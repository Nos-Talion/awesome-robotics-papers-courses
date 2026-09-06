# Robot Learning and Manipulation

[← Back to index](../README.md)

## Imitation and reinforcement learning

- **[A Reduction of Imitation Learning and Structured Prediction to No-Regret Online Learning](https://arxiv.org/abs/1011.0686)** — Ross, Gordon, and Bagnell, 2011. Introduces DAgger and explains covariate shift in behavioral cloning.
- **[Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)** — Schulman et al., 2017. A widely used on-policy reinforcement-learning baseline.
- **[Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor](https://arxiv.org/abs/1801.01290)** — Haarnoja et al., 2018. A strong off-policy method for continuous control.
- **[QT-Opt: Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation](https://arxiv.org/abs/1806.10293)** — Kalashnikov et al., 2018. Demonstrates large-scale real-robot grasp learning.
- **[What Matters in Learning from Offline Human Demonstrations for Robot Manipulation](https://arxiv.org/abs/2108.03298)** · [Project](https://robomimic.github.io/) — Mandlekar et al., 2022. A systematic study and reusable benchmark for offline imitation learning.

## Generative visuomotor policies

- **[Diffusion Policy: Visuomotor Policy Learning via Action Diffusion](https://arxiv.org/abs/2303.04137)** · [Project](https://diffusion-policy.cs.columbia.edu/) — Chi et al., 2023. Models multimodal action sequences with conditional diffusion.
- **[Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware](https://arxiv.org/abs/2304.13705)** · [Project](https://tonyzhaozh.github.io/aloha/) — Zhao et al., 2023. Introduces Action Chunking with Transformers (ACT) and the ALOHA platform.
- **[Behavior Generation with Latent Actions](https://arxiv.org/abs/2403.03181)** · [Project](https://sjlee.cc/vq-bet/) — Lee et al., 2024. VQ-BeT represents long, multimodal behavior using learned discrete actions.
- **[3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations](https://arxiv.org/abs/2403.03954)** · [Project](https://3d-diffusion-policy.github.io/) — Ze et al., 2024. Uses compact point-cloud representations for data-efficient generalization.
- **[EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning](https://arxiv.org/abs/2407.01479)** · [Project](https://equi-bot.github.io/) — Yang et al., 2024. Builds geometric equivariance into a diffusion policy.

## Grasping and manipulation

- **[Dex-Net 2.0: Deep Learning to Plan Robust Grasps with Synthetic Point Clouds and Analytic Grasp Metrics](https://arxiv.org/abs/1703.09312)** · [Project](https://berkeleyautomation.github.io/dex-net/) — Mahler et al., 2017. Connects analytic grasp metrics, synthetic data, and depth-based grasp prediction.
- **[GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping](https://arxiv.org/abs/1912.13470)** · [Project](https://graspnet.net/) — Fang et al., 2020. A large benchmark for 6-DoF grasp detection in clutter.
- **[Contact-GraspNet: Efficient 6-DoF Grasp Generation in Cluttered Scenes](https://arxiv.org/abs/2103.14127)** · [Code](https://github.com/NVlabs/contact_graspnet) — Sundermeyer et al., 2021. Generates diverse grasps directly from scene point clouds.
- **[Transporter Networks: Rearranging the Visual World for Robotic Manipulation](https://arxiv.org/abs/2010.14406)** · [Project](https://transporternets.github.io/) — Zeng et al., 2021. Introduces spatially structured pick-and-place policies.
- **[PerAct: Multi-Task 6D Robotic Manipulation via Perceiver-Actor](https://arxiv.org/abs/2209.05451)** · [Project](https://peract.github.io/) — Shridhar et al., 2022. Predicts discretized 6-DoF actions from language and voxel observations.
- **[RVT: Robotic View Transformer for 3D Object Manipulation](https://arxiv.org/abs/2306.14896)** · [Project](https://robotic-view-transformer.github.io/) — Goyal et al., 2023. Projects 3D observations into virtual views for efficient action prediction.

## Data collection and benchmarks

- **[RLBench: The Robot Learning Benchmark & Learning Environment](https://arxiv.org/abs/1909.12271)** · [Project](https://sites.google.com/view/rlbench) — James et al., 2020. A broad set of language-described manipulation tasks in simulation.
- **[CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks](https://arxiv.org/abs/2112.03227)** · [Project](https://calvin.cs.uni-freiburg.de/) — Mees et al., 2022. Evaluates long-horizon, language-conditioned manipulation.
- **[BridgeData V2: A Dataset for Robot Learning at Scale](https://arxiv.org/abs/2308.12952)** · [Project](https://rail-berkeley.github.io/bridgedata/) — Walke et al., 2023. A large and diverse open dataset of manipulation trajectories.
- **[Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots](https://arxiv.org/abs/2402.10329)** · [Project](https://umi-gripper.github.io/) — Chi et al., 2024. A portable demonstration interface designed for scalable real-world data collection.
- **[DROID: A Large-Scale In-the-Wild Robot Manipulation Dataset](https://arxiv.org/abs/2403.12945)** · [Project](https://droid-dataset.github.io/) — Khazatsky et al., 2024. Multi-institution real-robot data spanning diverse scenes and tasks.
