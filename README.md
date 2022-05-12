# Trajectory Planning using HER & Reward Engineering

Trajectory planning based on Reinforcement Learning with Hindsight Experience Replay, Prioritized Experience Replay & Dense Reward Engineering to solve openai-gym robotics "FetchReach-v1" environment using PyTorch & Tensorflow2.

## Reinforcement Learning Algorithms

1. Dense Reward Engineering: Engineered vector based distance measure to replace sparse rewards.

2. Hindsight Experience Relay (HER): Implemented HER Future Strategy based goal sampling for buffer augmentation.

3. Prioritized Experience Relay (PER): Samples and optimizes the past experiences ended with errors to get better future rewards.

## Agent Profiles

1. Dense Reward Engineering

    |DDPG Agent|PER + DDPG Agent|
    |:--:|:--:|
    |<img src="dense_rewards/uniform/data/DDPG with Dense Rewards.png" width="400">|<img src="dense_rewards/prioritized/data/PDDPG with Dense Rewards.png" width="400">|

2. Hindsight Experience Repay

    |DDPG Agent|PER + DDPG Agent|
    |:--:|:--:|
    |<img src="sparse_rewards/prioritized/data/HER + PDDPG with Dense Rewards.png" width="400">|<img src="sparse_rewards/uniform/data/HER + DDPG with Dense Rewards.png" width="400">|

## Play Preview

## Dependencies

Install dependencies using:

```bash
pip3 install -r requirements.txt 
```

1. Additionally install 'mujoco_py' according to 'https://github.com/openai/mujoco-py'

## Developer

* Name: Kanishk Navale
* Email: navalekanishk@gmail.com
* Website: <https://kanishknavale.github.io/>
