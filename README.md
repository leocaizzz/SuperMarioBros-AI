# Super Mario Bros AI: Reinforcement Learning with PPO

Welcome to the Super Mario Bros AI repository! This project showcases a sophisticated reinforcement learning agent that learns to play the iconic NES game, Super Mario Bros. The agent is trained using the Proximal Policy Optimization (PPO) algorithm from the Stable Baselines 3 library and interacts with the game environment provided by the `gym_super_mario_bros` package.

![Super Mario Bros AI Demo](demo.gif)

*The above demo showcases the AI agent playing Super Mario Bros after training.*

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)

## Features

- Reinforcement learning agent utilizing the state-of-the-art Proximal Policy Optimization (PPO) algorithm from the Stable Baselines 3 library.
- `gym_super_mario_bros` package integration for an authentic Super Mario Bros game environment.
- Simplified action space using the JoypadSpace wrapper from the `nes_py` library, streamlining the agent's decision-making process.
- Comprehensive training process with 1,000,000 (or more) timesteps, ensuring a well-trained and effective model.
- Visualization of the agent's in-game progress during both training and evaluation phases, allowing for performance analysis and demonstrations.
- Straightforward customization options for training parameters, model architecture, and more. 

## Requirements

- Python 3.6 or higher
- gym_super_mario_bros
- nes_py
- stable_baselines3

## Installation

1. Install the required dependencies:

```
pip install gym_super_mario_bros nes_py stable_baselines3
```

2. Clone this repository

```
git clone https://github.com/leocaizzz/super_mario_bros_ai.git
cd super_mario_bros_ai
```
## Usage

1. Run the script to train the agent and visualize its progress:

```
python mario.py
```

During the training phase, the agent will explore and learn from the Super Mario Bros game environment. It will make decisions that maximize its rewards, improving its performance over time.

After completing the training, the agent will load the saved model and transition to the evaluation phase. The agent's performance will be visualized as it navigates through the game environment, showcasing its learned behaviors and decision-making capabilities.

## Customization

To adjust training and evaluation parameters, modify the `main.py` script. You can change the number of timesteps for training, the learning rate, and the neural network's architecture. For more information on customizing the PPO algorithm's settings, refer to the [Stable Baselines 3 documentation](https://stable-baselines3.readthedocs.io/en/master/).

## Contributing

Any contributions to this project are welcomed! If you have ideas for improvements, bug fixes, or new features, please follow these steps:

1. Fork the repository and create a new branch with a descriptive name for your changes.
2. Make the desired changes, test them thoroughly, and ensure that the code is well-documented.
3. Submit a pull request to the main repository, providing a detailed description of your changes.

I will actively review pull requests and provide feedbacks. Once your changes are approved, they will be merged into the main repository. 
