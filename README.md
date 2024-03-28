# DRL4FloatingWasteCapture

This repository supports the paper 'Deep Reinforcement Learning for Autonomous Surface Vehicles: Bridging the Gap to Real-World Deployment'. It provides links to the code used during experiments. Future enhancements will be updated in the main branches of the respective repositories.

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
- **Kingfisher-related Code**: Instructions for running simulations and real-world tests can be found in the [kingfisher_control](https://github.com/luisfelipewb/kingfisher_control/tree/iros2024) repository.

## Citation 
If you use our code in your work, we suggest citing the following papers:

```bibtex
@article{tbd,
  title={Advancing ASV Autonomy for Environmental Cleanup: A Deep Reinforcement Learning Framework for Floating Waste Capture},
  author={Batista, Luis F. W. and Ro, Junghwan and Richard, Antoine and Schroepfer, Pete and Hutchinson, Seth and Pradalier, Cedric},
  journal={to be updated},
  year={2024}
}

@article{el2023rans,
  title={RANS: Highly-Parallelised Simulator for Reinforcement Learning based Autonomous Navigating Spacecrafts},
  author={El-Hariry, Matteo and Richard, Antoine and Olivares-Mendez, Miguel},
  journal={arXiv preprint arXiv:2310.07393},
  year={2023}
}
```
