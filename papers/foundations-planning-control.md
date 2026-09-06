# Foundations, Planning, and Control

[← Back to index](../README.md)

Read roughly from top to bottom within each section. Links point to the paper, publisher record, or an author-hosted copy.

## Modeling and control

- **[Operational Space Formulation and Analysis of Robot Manipulators](https://doi.org/10.1109/JRA.1987.1087068)** — Khatib, 1987. Establishes task-space dynamics and control for manipulators.
- **[Impedance Control: An Approach to Manipulation, Part I—Theory](https://doi.org/10.1115/1.3140702)** — Hogan, 1985. Introduces control of dynamic interaction rather than position alone.
- **[A Mathematical Introduction to Robotic Manipulation](https://www.cds.caltech.edu/~murray/books/MLS/pdf/mlsw.pdf)** — Murray, Li, and Sastry, 1994. A rigorous foundation in rigid-body motion, kinematics, dynamics, and control.
- **[Control Barrier Function Based Quadratic Programs for Safety Critical Systems](https://arxiv.org/abs/1609.06408)** — Ames et al., 2017. A standard route to enforcing safety constraints in feedback control.
- **[Information-Theoretic Model Predictive Control: Theory and Applications to Autonomous Driving](https://arxiv.org/abs/1707.02342)** — Williams et al., 2018. Develops sampling-based MPPI control for nonlinear systems.

## Sampling-based motion planning

- **[Probabilistic Roadmaps for Path Planning in High-Dimensional Configuration Spaces](https://doi.org/10.1109/70.508439)** — Kavraki et al., 1996. The foundational multi-query sampling-based planner.
- **[Rapidly-Exploring Random Trees: A New Tool for Path Planning](https://msl.cs.illinois.edu/~lavalle/papers/Lav98c.pdf)** — LaValle, 1998. Introduces RRTs for efficiently exploring large state spaces.
- **[RRT-Connect: An Efficient Approach to Single-Query Path Planning](https://doi.org/10.1109/ROBOT.2000.844730)** — Kuffner and LaValle, 2000. A practical bidirectional RRT variant still widely used.
- **[Sampling-Based Algorithms for Optimal Motion Planning](https://arxiv.org/abs/1105.1186)** — Karaman and Frazzoli, 2011. Introduces PRM* and RRT* with asymptotic optimality.
- **[Batch Informed Trees (BIT*): Sampling-based Optimal Planning via the Heuristically Guided Search of Implicit Random Geometric Graphs](https://arxiv.org/abs/1405.5848)** — Gammell et al., 2015. Connects informed graph search with anytime sampling-based planning.

## Trajectory optimization

- **[CHOMP: Gradient Optimization Techniques for Efficient Motion Planning](https://doi.org/10.1109/ROBOT.2009.5152817)** — Ratliff et al., 2009. A landmark functional-gradient formulation for smooth collision-free trajectories.
- **[STOMP: Stochastic Trajectory Optimization for Motion Planning](https://doi.org/10.1109/ICRA.2011.5980280)** — Kalakrishnan et al., 2011. Uses noisy trajectory rollouts without requiring analytic cost gradients.
- **[Motion Planning with Sequential Convex Optimization and Convex Collision Checking](https://arxiv.org/abs/1311.5602)** — Schulman et al., 2014. Introduces TrajOpt, a practical constrained trajectory optimizer.
- **[GPMP2: A Factor Graph Framework for Motion Planning](https://arxiv.org/abs/1707.07383)** — Mukadam et al., 2018. Expresses continuous-time trajectory optimization as inference on a factor graph.

## Suggested implementation path

1. Implement planar forward/inverse kinematics and Jacobian control.
2. Add joint-space and task-space PD control in simulation.
3. Implement RRT-Connect, then compare it with RRT* on the same scenes.
4. Formulate a collision-aware trajectory optimization problem.
5. Add an MPC or control-barrier-function layer for online constraints.
