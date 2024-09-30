# DRL4FloatingWasteCapture
This repository provides an overview and the relevant links for the following articles:
* [A Deep Reinforcement Learning Framework and Methodology for Reducing the Sim-to-Real Gap in ASV Navigation](https://arxiv.org/abs/2407.08263) - Accepted to IROS 2024
* [Evaluation of DRL Robustness for Autonomous Surface Vehicle Control](tbd) - Submitted to ICRA 2025


## Description

Despite the increasing adoption of Deep Reinforcement Learning (DRL) for Autonomous Surface Vehicles (ASVs), there still remain challenges limiting real-world deployment. In our work, we address these challenges by integrating buoyancy and hydrodynamics models into a modern Reinforcement Learning framework to reduce training time. Additionally, we demonstrate the effectiveness of system identification coupled with domain randomization in improving the RL agent's performance, bridging the gap to real-world applications. Our approach is validated through real-world experiments focused on the task of capturing floating waste. Results indicate a significant improvement, with a 13.1% reduction in energy consumption and a 7.4% decrease in task completion time compared to baseline methods.

| Training Environment - Isaac Sim |
| :---: |
| ![Isaac Sim](img/isaac.gif) |

| Testing Environment - Gazebo |
| :---: |
| ![Gazebo](img/gazebo.gif) |

| Field Test - Kingfisher |
| :---: |
| ![Field Test](img/field.gif) |

## Installation

### 1. RL Framework
To install the RL framework for simulating hydrodynamics and buoyancy, follow the instructions in the [RANS-ASV-IROS2024](https://github.com/JunghwanRo/RANS-ASV-IROS2024) repository. Ensure that all requirements mentioned in that repository are met.

### 2. Kingfisher-related Code
Additionally, you'll need the Kingfisher-related code for running simulations and real-world tests. This code can be found in the [kingfisher_control](https://github.com/luisfelipewb/kingfisher_control) repository.

Follow the instructions provided in the repository to set up the Kingfisher-related code.

## Usage

For running training and test procedures, please refer to the respective repositories:

- **RL Framework**: Follow the instructions provided in the [RANS-ASV-IROS2024](https://github.com/JunghwanRo/RANS-ASV-IROS2024) repository.
- **Kingfisher-related Code**: Instructions for running simulations and real-world tests can be found in the [kingfisher_control](https://github.com/luisfelipewb/kingfisher_control/tree/pub/iros2024) repository.

## Citation 
If you use our code in your work, we suggest citing the following papers:

```bibtex
@misc{batista2024deepreinforcementlearningframework,
      title={A Deep Reinforcement Learning Framework and Methodology for Reducing the Sim-to-Real Gap in ASV Navigation}, 
      author={Luis F W Batista and Junghwan Ro and Antoine Richard and Pete Schroepfer and Seth Hutchinson and Cedric Pradalier},
      year={2024},
      eprint={2407.08263},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2407.08263}, 
}

@article{el2023rans,
  title={RANS: Highly-Parallelised Simulator for Reinforcement Learning based Autonomous Navigating Spacecrafts},
  author={El-Hariry, Matteo and Richard, Antoine and Olivares-Mendez, Miguel},
  journal={arXiv preprint arXiv:2310.07393},
  year={2023}
}
```
