# SLRRL: Systematic Literature Review on Reinforcement Learning for Humanoid Robots

This repository contains the dataset and analysis related to a systematic literature review (SLR) on the use of **Reinforcement Learning (RL) in humanoid robotics**. The review covers 39 papers published in major conferences and journals between 2019 and 2024.

## Overview

The goal of this SLR is to investigate the current state of RL applications in humanoid robots, highlighting the most commonly used techniques, simulation platforms, datasets, validation strategies, and research gaps. Key research questions addressed in the review include:

- **RQ1:** What are the main RL techniques applied in humanoid robots?  
- **RQ2:** What are the current challenges in implementing RL in humanoids?  
- **RQ3:** How does RL in humanoids compare to other robotic control approaches in terms of performance and adaptability?  
- **RQ4:** What are the limitations of current RL techniques in humanoid robots?  
- **RQ5:** How can transfer learning be applied to improve the performance of humanoid robots in different tasks?  
- **RQ6:** What metrics are most effective for evaluating the performance of RL systems in humanoid robots?  
- **RQ7:** How can RL approaches be integrated with other artificial intelligence techniques, such as supervised or unsupervised learning?  
- **RQ8:** What are the most promising use cases for humanoid robots utilizing RL in real-world applications?

## Dataset

The dataset includes detailed information extracted from each selected paper, including:

- **Title**
- **Research Question (RQ)**
- **Authors**
- **Year**
- **Venue / Event**
- **Simulation Platform**
- **RL Algorithm Family**
- **Validation Type (Simulation / Real)**
- **Dataset Used**

Example entries include:

| Title | Authors | Year | Platform | RL Algorithm | Validation | Dataset |
|-------|--------|------|---------|--------------|------------|---------|
| A Reinforcement Learning Approach to Synthesizing Climbing Movements | Kourosh Naderi et al. | 2019 | MuJoCo | Efficient RL for smooth interactive climbing movements | sim | There is no |
| Data-Driven Latent Space Representation for Robust Bipedal Locomotion Learning | Guillermo A. Castillo et al. | 2024 | Digit | Autoencoder-based RL for robust, generalizable bipedal locomotion | sim | Gait dataset |
| SoccerKicks: a Dataset of 3D Dead Ball Kicks Reference Movements for Humanoid Robots | Nayari Marie Lessa et al. | 2021 | HMMR | Provides a dataset of 3D soccer kick movements to improve robot training in sports scenarios | sim | SoccerKicks |

The full dataset is included in this repository in CSV/Excel format for analysis.

## Insights

Some key findings from the SLR include:

- The **CMU Motion Capture Database** is the most widely used dataset for human motion imitation.  
- **MuJoCo** is the most common simulation environment, but others like PyBullet, CoppeliaSim, Unity ML, and custom platforms are also employed.  
- About **60% of studies do not report or use standard datasets**, highlighting challenges in reproducibility.  
- There is a fragmentation of approaches and limited standardization in humanoid RL research.  

## Usage

This repository can be used for:

- Meta-analysis of RL techniques in humanoid robotics.  
- Identifying gaps in datasets, benchmarks, and simulation platforms.  
- Guiding future research on RL applications for humanoid robots.  

To use the dataset:

```bash
# Clone the repository
git clone https://github.com/vitor-souza-ime/slrrl.git

# Access the dataset
cd slrrl
open dataset.csv  # or open in Excel/Google Sheets
````

## References

Please refer to the original papers for details on algorithms, datasets, and experimental setups. Some examples:

* Kourosh Naderi, Amin Babadi, Shaghayegh Roohi, and Perttu Hamalainen. *A Reinforcement Learning Approach to Synthesizing Climbing Movements*, 2019 IEEE Conference on Games (CoG), 2019.
* Zerun Cai, Yuehu Liu, and Yuchen Liang. *Accelerating Human Motion Imitation with Interactive Reinforcement Learning*, 2023 IEEE International Conference on Real-time Computing and Robotics (RCAR), 2023.
* Nayari Marie Lessa, Esther Luna Colombini, and Alexandre da Silva Simões. *SoccerKicks: a Dataset of 3D Dead Ball Kicks Reference Movements for Humanoid Robots*, 2021 IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2021.

## License

This repository is released under the MIT License.


