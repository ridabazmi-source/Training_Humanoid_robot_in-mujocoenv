# Training_Humanoid_robot_in-mujocoenv
This project demonstrates the training of a Humanoid agent in the Mujoco environment using Deep Reinforcement Learning (DRL) with the Stable-Baselines3 PPO (Proximal Policy Optimization) algorithm. The agent learns to walk and perform movements within the Humanoid-v5 environment, aiming for efficiency, balance, and faster movement
 FeatureKeys:
Mujoco Humanoid-v5 Environment: Used for simulating humanoid robots and enabling realistic physical interactions in a virtual environment.
Reinforcement Learning (RL): The agent uses Proximal Policy Optimization (PPO), a powerful model-free DRL algorithm, for training the agent.
Training Process: The agent is trained using up to 2 million timesteps to learn walking behaviors, balance, and faster movement.
Video Generation: The project includes a video generation pipeline where the trained agent's movements are captured and saved as a video using Gymnasium and MoviePy.
Rewards: The reward function is designed to incentivize the agent to walk faster while maintaining balance.
Training Setup:
Training Algorithm: Proximal Policy Optimization (PPO)
Environment: Mujoco Humanoid-v5 environment
Framework: Stable-Baselines3, Gymnasium
Reward Shaping: Velocity and balance-based rewards to encourage faster walking while maintaining stability.
Results:
The agent can successfully learn to walk and balance in the humanoid environment.
The project includes videos showing the agent's progress and performance throughout training.
