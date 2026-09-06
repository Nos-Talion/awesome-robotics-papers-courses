# Books, Software, Datasets, and Benchmarks

[← Back to index](../README.md)

## Books and long-form notes

- **[Modern Robotics: Mechanics, Planning, and Control](https://modernrobotics.northwestern.edu/)** — Lynch and Park. Free preprint, videos, exercises, and software.
- **[Planning Algorithms](https://lavalle.pl/planning/)** — LaValle. Free online book on motion planning, sensing uncertainty, and planning under differential constraints.
- **[A Mathematical Introduction to Robotic Manipulation](https://www.cds.caltech.edu/~murray/books/MLS/pdf/mlsw.pdf)** — Murray, Li, and Sastry. Free author-hosted text on geometric mechanics and control.
- **[Underactuated Robotics](https://underactuated.csail.mit.edu/)** — Tedrake. Executable notes on nonlinear dynamics, optimization, planning, and control.
- **[Robotic Manipulation](https://manipulation.csail.mit.edu/)** — Tedrake. Open notes and notebooks for manipulation.
- **[Probabilistic Robotics](https://mitpress.mit.edu/9780262201629/probabilistic-robotics/)** — Thrun, Burgard, and Fox. Publisher page for the classic text on state estimation and mapping.
- **[Springer Handbook of Robotics](https://link.springer.com/book/10.1007/978-3-319-32552-1)** — Siciliano and Khatib, editors. Broad reference work; institutional access may be required.

## Core software

| Project | Main use | Official link |
|---|---|---|
| ROS 2 | Robot middleware and application integration | [Documentation](https://docs.ros.org/) |
| MoveIt 2 | Manipulation and motion planning | [Documentation](https://moveit.picknik.ai/) |
| Drake | Modeling, optimization, planning, and control | [Website](https://drake.mit.edu/) |
| Pinocchio | Rigid-body dynamics and derivatives | [Documentation](https://stack-of-tasks.github.io/pinocchio/) |
| MuJoCo | Fast physics simulation | [Documentation](https://mujoco.readthedocs.io/) |
| Gazebo | General-purpose robot simulation | [Documentation](https://gazebosim.org/docs/latest/getstarted/) |
| Isaac Sim | GPU-accelerated robotics simulation | [Documentation](https://docs.isaacsim.omniverse.nvidia.com/latest/) |
| PyBullet | Physics simulation and prototyping | [Repository](https://github.com/bulletphysics/bullet3) |
| robosuite | Robot-learning simulation environments | [Website](https://robosuite.ai/) |
| ManiSkill | GPU-parallel manipulation environments | [Documentation](https://maniskill.readthedocs.io/) |
| robomimic | Offline imitation-learning baselines | [Website](https://robomimic.github.io/) |
| LeRobot | Models, datasets, and tools for real-world robot learning | [Documentation](https://huggingface.co/docs/lerobot/) |

## Datasets and benchmarks

| Resource | Scope | Official link |
|---|---|---|
| Open X-Embodiment | Cross-embodiment robot trajectories | [Project](https://robotics-transformer-x.github.io/) |
| DROID | Diverse real-world manipulation data | [Project](https://droid-dataset.github.io/) |
| BridgeData V2 | Multi-domain manipulation trajectories | [Project](https://rail-berkeley.github.io/bridgedata/) |
| GraspNet-1Billion | 6-DoF grasp detection | [Project](https://graspnet.net/) |
| RLBench | Language-described simulated manipulation | [Project](https://sites.google.com/view/rlbench) |
| CALVIN | Long-horizon language-conditioned manipulation | [Project](https://calvin.cs.uni-freiburg.de/) |
| LIBERO | Lifelong robot learning | [Project](https://libero-project.github.io/) |
| ManiSkill | Generalizable manipulation in simulation | [Documentation](https://maniskill.readthedocs.io/) |

## Reproducibility checklist

Before treating a result as established, check whether the authors provide:

- exact train/evaluation splits and a clear definition of generalization;
- code version, environment version, seeds, and hyperparameters;
- hardware, control frequency, camera setup, and action representation;
- the number of real-robot trials and all intervention rules;
- per-task results, variance or confidence intervals, and failure categories;
- dataset and checkpoint licenses compatible with the intended use.
