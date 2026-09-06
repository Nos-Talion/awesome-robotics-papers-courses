# University Courses and Open Curricula

[← Back to index](../README.md)

Availability changes by semester. Links favor stable course homepages or official university archives.

## Foundations, kinematics, dynamics, and control

- **[Modern Robotics](https://modernrobotics.northwestern.edu/)** — Northwestern University. Free textbook, videos, exercises, and software covering rigid-body motion, kinematics, dynamics, planning, and control.
- **[CS223A / ME320: Introduction to Robotics](https://cs.stanford.edu/group/manips/teaching/cs223a/)** — Stanford University. Manipulator modeling, Jacobians, dynamics, operational-space control, force control, and visual servoing.
- **[Robot Dynamics](https://rsl.ethz.ch/education-students/lectures/robotdynamics.html)** — ETH Zürich. Dynamics and control of fixed-base and floating-base robotic systems.
- **[Underactuated Robotics](https://underactuated.csail.mit.edu/)** — MIT. Nonlinear dynamics, optimization, planning, estimation, and control with executable notes.

## Manipulation, planning, and autonomy

- **[Robotic Manipulation](https://manipulation.csail.mit.edu/)** — MIT. Perception, planning, and control for manipulation, with interactive notes and Drake notebooks.
- **[16-350: Planning Techniques for Robotics](https://www.cs.cmu.edu/~maxim/classes/robotplanning/)** — Carnegie Mellon University. Search, motion planning, task planning, decision-making, and multi-robot planning.
- **[16-782: Planning and Decision-making in Robotics](https://www.cs.cmu.edu/~maxim/classes/robotplanning_grad/)** — Carnegie Mellon University. Graduate-level planning methods and robotic case studies.
- **[Introduction to Mobile Robotics](https://rl.uni-freiburg.de/teaching/ss24/mobile-robotics/)** — University of Freiburg. Kinematics, sensing, localization, mapping, SLAM, control, and navigation.

## Reinforcement learning and robot learning

- **[CS234: Reinforcement Learning](https://web.stanford.edu/class/cs234/)** — Stanford University. Core algorithms and theory for sequential decision-making.
- **[CS285: Deep Reinforcement Learning](https://rail.eecs.berkeley.edu/deeprlcourse/)** — UC Berkeley. Deep RL, model-based learning, offline RL, imitation learning, and control.
- **[CS224R: Deep Reinforcement Learning](https://cs224r.stanford.edu/)** — Stanford University. Modern deep RL with applications including robotics and language-model post-training.
- **[16-832: Integrated Planning and Learning](https://www.cs.cmu.edu/~maxim/classes/integratedplanningandlearning/)** — Carnegie Mellon University. Research-oriented material at the planning/learning interface.

## Robotics software practice

- **[Programming for Robotics – ROS](https://rsl.ethz.ch/education-students/lectures/ros.html)** — ETH Zürich. A structured introduction to ROS-oriented robotics development.
- **[ROS 2 Tutorials](https://docs.ros.org/en/jazzy/Tutorials.html)** — Open Robotics. Step-by-step official tutorials for the current long-term-support ROS 2 distribution.
- **[MoveIt 2 Tutorials](https://moveit.picknik.ai/main/doc/tutorials/tutorials.html)** — MoveIt. Motion planning, planning scenes, kinematics, and manipulation workflows.
- **[Drake Tutorials](https://drake.mit.edu/)** — Robot Locomotion Group, MIT. Modeling, simulation, mathematical programming, planning, and control.

## A practical 16-week sequence

| Weeks | Focus | Primary resource | Output |
|---|---|---|---|
| 1–3 | Rigid transforms and kinematics | Modern Robotics | FK/IK and Jacobian notebook |
| 4–5 | Dynamics and feedback control | Stanford CS223A or ETH Robot Dynamics | Simulated joint/task-space controller |
| 6–7 | Motion planning | CMU 16-350 | RRT-Connect implementation and comparison |
| 8–9 | State estimation and SLAM | Freiburg Mobile Robotics | EKF or pose-graph project |
| 10–12 | Imitation and reinforcement learning | CS285 or CS234 | Reproducible policy-learning baseline |
| 13–14 | Robot manipulation | MIT Robotic Manipulation | Perception-planning-control pipeline |
| 15–16 | Final project | Papers in this repository | Evaluation report with failure analysis |
