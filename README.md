
# **PPO** Agent playing **LunarLander-v2**
This is a trained model of a **PPO** agent playing **LunarLander-v2** using the [stable-baselines3 library](https://github.com/DLR-RM/stable-baselines3).

Using Google Colab, I trained my first Deep Reinforcement Learning agent, a Lunar Lander agent that will learn to land correctly on the moon using Stable-Baselines3.

I trained the agent for 1,000,000 timesteps, resulting in a mean award of 206.92 +/- 53.53.

To improve the model:
- Train more steps
- Try different hyperparameters for PPO. Check out: https://stable-baselines3.readthedocs.io/en/master/modules/ppo.html#parameters.
- Try another model such as DQN

# Visual of agent
https://github.com/rishisim/LunarLander-v2/assets/86998121/7838a5e9-2854-4d0c-bcf5-13036a7bc359

# Information about the model
Environment: [LunarLander-v2](https://gymnasium.farama.org/environments/box2d/lunar_lander/)
Library: [stable-baselines3](https://github.com/DLR-RM/stable-baselines3)
Model: Proximal Policy Optimization (PPO)
Mean Reward +/- Std. Dev.: 206.92 +/- 53.53

