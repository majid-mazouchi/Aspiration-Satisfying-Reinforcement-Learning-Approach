# Aspiration-Satisfying-Reinforcement-Learning-Approach
## Data-Driven Dynamic Multiobjective Optimal Control: An Aspiration-Satisfying Reinforcement Learning Approach
Published in: IEEE Transactions on Neural Networks and Learning Systems

### [Link to paper](https://ieeexplore.ieee.org/abstract/document/9411709)

#### Authors: [Majid Mazouchi](https://majid-mazouchi.github.io/), Yongliang Yang, Hamidreza Modares
### Abstract
This article presents an iterative data-driven algorithm for solving dynamic multiobjective (MO) optimal control problems arising in control of nonlinear continuous-time systems. It is first shown that the Hamiltonian functional corresponding to each objective can be leveraged to compare the performance of admissible policies. Hamiltonian inequalities are then used for which their satisfaction guarantees satisfying the objectives’ aspirations. Relaxed Hamilton–Jacobi–Bellman (HJB) equations in terms of HJB inequalities are then solved in a dynamic constrained MO framework to find Pareto optimal solutions. Relation to satisficing (good enough) decision-making framework is shown. A sum-of-square (SOS)-based iterative algorithm is developed to solve the formulated aspiration-satisfying MO optimization. To obviate the requirement of complete knowledge of the system dynamics, a data-driven satisficing reinforcement learning approach is proposed to solve the SOS optimization problem in real time using only the information of the system trajectories measured during a time interval without having full knowledge of the system dynamics. Finally, two simulation examples are utilized to verify the analytical results of the proposed algorithm.

### Overview figure
![Overview](https://github.com/majid-mazouchi/majid-mazouchi.github.io/blob/main/assets/img/MultiObProj.png)

### Algorithm 1 SOS-BASED MULTIOBJECTIVE RL 
![algorithm](https://github.com/majid-mazouchi/majid-mazouchi.github.io/blob/main/assets/img/Alg1asMo.png)

