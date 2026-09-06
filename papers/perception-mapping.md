# Perception, State Estimation, and SLAM

[← Back to index](../README.md)

## State estimation and SLAM

- **[A Tutorial on Graph-Based SLAM](https://doi.org/10.1109/MITS.2010.939925)** — Grisetti et al., 2010. A clear introduction to pose graphs, linearization, and graph optimization.
- **[LOAM: Lidar Odometry and Mapping in Real-time](https://doi.org/10.15607/RSS.2014.X.007)** — Zhang and Singh, 2014. A landmark real-time LiDAR odometry and mapping system.
- **[Direct Sparse Odometry](https://arxiv.org/abs/1607.02565)** — Engel et al., 2018. A direct, sparse visual-odometry formulation with photometric optimization.
- **[ORB-SLAM2: An Open-Source SLAM System for Monocular, Stereo, and RGB-D Cameras](https://arxiv.org/abs/1610.06475)** — Mur-Artal and Tardós, 2017. A complete feature-based SLAM system supporting multiple camera setups.
- **[ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial, and Multi-Map SLAM](https://arxiv.org/abs/2007.11898)** · [Code](https://github.com/UZ-SLAMLab/ORB_SLAM3) — Campos et al., 2021. Extends the ORB-SLAM family to visual-inertial and multi-map settings.

## General visual representations and segmentation

- **[DINOv2: Learning Robust Visual Features without Supervision](https://arxiv.org/abs/2304.07193)** · [Code](https://github.com/facebookresearch/dinov2) — Oquab et al., 2023. Strong self-supervised visual features used across robotic perception tasks.
- **[Segment Anything](https://arxiv.org/abs/2304.02643)** · [Project](https://segment-anything.com/) — Kirillov et al., 2023. Introduces promptable image segmentation at large scale.
- **[Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection](https://arxiv.org/abs/2303.05499)** · [Code](https://github.com/IDEA-Research/GroundingDINO) — Liu et al., 2023. Connects text prompts with open-set object detection.
- **[SAM 2: Segment Anything in Images and Videos](https://arxiv.org/abs/2408.00714)** · [Project](https://ai.meta.com/sam2/) — Ravi et al., 2024. Extends promptable segmentation to temporal visual data.

## Object pose and scene reconstruction

- **[MegaPose: 6D Pose Estimation of Novel Objects via Render & Compare](https://arxiv.org/abs/2212.06870)** · [Project](https://megapose6d.github.io/) — Labbé et al., 2022. Scalable model-based pose estimation for previously unseen rigid objects.
- **[FoundationPose: Unified 6D Pose Estimation and Tracking of Novel Objects](https://arxiv.org/abs/2312.08344)** · [Project](https://nvlabs.github.io/FoundationPose/) — Wen et al., 2024. Unifies model-based and model-free pose estimation and tracking.
- **[BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects](https://arxiv.org/abs/2303.14158)** · [Project](https://bundlesdf.github.io/) — Wen et al., 2023. Jointly tracks and reconstructs unseen objects from RGB-D video.
- **[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934)** · [Project](https://www.matthewtancik.com/nerf) — Mildenhall et al., 2020. A foundational implicit scene-representation method with growing robotics use.
- **[3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://arxiv.org/abs/2308.04079)** · [Project](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) — Kerbl et al., 2023. Enables fast explicit scene reconstruction and rendering.

## Suggested implementation path

1. Implement an extended Kalman filter for a simple localization problem.
2. Build a 2D pose graph and solve it with nonlinear least squares.
3. Run a visual or LiDAR SLAM system on a public sequence and inspect failure cases.
4. Add open-vocabulary detection/segmentation to a manipulation scene.
5. Evaluate pose estimation under occlusion, symmetry, and domain shift.
