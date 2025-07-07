# HGATE-PPO
## Offcial implement of "Dependency-Aware Task Offloading Strategy via Heterogeneous Graph Neural Network and Deep Reinforcement Learning"



## Abstract
As the Internet of Things proliferates, cloud-assisted mobile-edge computing (MEC) enables intelligent connected vehicles (ICVs) to offload their computationally intensive tasks to servers within the Internet of Vehicles, thereby reducing delay and energy consumption. However, most existing research on edge computing offloading overlooks the dependency relationships between subtasks. These dependencies significantly increase the complexity of task offloading, making it difficult to devise general solutions for scenarios of varying scales a challenging endeavor. To tackle this challenge, we present a heterogeneous graph attention network (HGAT) augmented deep reinforcement learning dependency-aware task offloading framework, aiming to achieve minimal task completion time and energy consumption. The dynamic system of vehicles and servers is modeled as an undirected graph, with nodes corresponding to servers/vehicles and edges capturing the intensity of task competition. Tasks are modeled as directed acyclic graphs, where nodes denote subtasks and directed edges define their dependencies. An HGAT-based encoder is then introduced to effectively capture the intricate relationships between subtasks and each servercores. Subtask selection and servercores assignment are formulated as a Markov decision process and solved using the proximal policy optimization method. Simulation results demonstrate that the proposed algorithm outperforms existing ones across various scenarios, showcasing superior adaptability and performance benefits.

## Citation
J. Wu, Y. Zou, X. Zhang, J. Liu, W. Sun and G. Du, "[Dependency-Aware Task Offloading Strategy via Heterogeneous Graph Neural Network and Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/10918838)"
```
@ARTICLE{10918838,
  author={Wu, Jinming and Zou, Yuan and Zhang, Xudong and Liu, Jiahui and Sun, Wenjing and Du, Guodong},
  journal={IEEE Internet of Things Journal}, 
  title={Dependency-Aware Task Offloading Strategy via Heterogeneous Graph Neural Network and Deep Reinforcement Learning}, 
  year={2025},
  volume={12},
  number={13},
  pages={22915-22933},
  keywords={Deep reinforcement learning (DRL);dependency-aware task offloading; directed acyclic graph;heterogeneous graph attention networks (HGATs); mobile-edge computing (MEC); undirected graph}, 
  doi={10.1109/JIOT.2025.3549441}}
```

