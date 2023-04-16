# Super Mario Bros AI

This repository features a reinforcement learning agent that learns to play the classic NES game Super Mario Bros using the Proximal Policy Optimization (PPO) algorithm. The agent is trained using the game environment provided by the `gym_super_mario_bros` package and the PPO algorithm from the Stable Baselines 3 library.

## Key Features

- Reinforcement learning agent based on the Proximal Policy Optimization (PPO) algorithm from the Stable Baselines 3 library.
- Utilizes the `gym_super_mario_bros` package for creating a Super Mario Bros game environment.
- Employs the JoypadSpace wrapper from the `nes_py` library to simplify the action space for the agent.
- Agent is trained for 1,000,000 timesteps and the trained model is saved for later use.
- Visualization of the agent's progress in the game environment during both the training and evaluation phases.

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

2. Clone this repository:

```
git clone https://github.com/yourusername/super_mario_bros_ai.git
cd super_mario_bros_ai
```

## Usage

1. Run the script to train the agent and visualize its progress:
```
python main.py
```

The script will train the agent using the Super Mario Bros environment and the PPO algorithm. During the training phase, the agent will explore the game environment, learning to make decisions that maximize its rewards.

After training is complete, the agent will load the saved model and begin the evaluation phase. The agent's performance in the game will be visualized as it navigates through the game environment, demonstrating its learned behaviors and decision-making skills.

## Customization

You can modify the `main.py` script to adjust the training and evaluation parameters, such as the number of timesteps for training, the learning rate, and the size of the neural network. Refer to the [Stable Baselines 3 documentation](https://stable-baselines3.readthedocs.io/en/master/) for more information on customizing the PPO algorithm's settings.
