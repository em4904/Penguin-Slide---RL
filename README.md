# 🧠 Reinforcement Learning GridWorld Simulator

A customizable 8×8 GridWorld environment built to experiment with Q-Learning, SARSA, and Expected SARSA. The project allows visualizing how RL agents learn optimal paths under different conditions, obstacles, and reward settings.

# 🚀 Features

Interactive 8×8 GridWorld with start, goal, obstacles, and reward states

# Supports three RL algorithms:

Q-Learning

SARSA

Expected SARSA

## Adjustable training settings (episodes, exploration rate, learning rate, discount factor)

## Moving-average reward smoothing for clearer convergence analysis

## Visual performance charts showing reward trends and stability

## Ability to add and modify obstacles dynamically

# Final report comparing accuracy and learning behavior of each algorithm


# 📘 How It Works

The agent learns to navigate the environment using reinforcement learning:

Takes an action based on an ε-greedy policy

Receives a reward from the environment

Updates its Q-values using the selected RL algorithm

Repeats for many episodes until it converges on an optimal policy

Each algorithm differs in how it updates Q-values, making their behaviors and stability interesting to compare.

# 📊 Results & Observations

Q-Learning typically converged the fastest and found shorter paths.

SARSA produced safer, more conservative policies depending on ε.

Expected SARSA showed smoother learning curves due to expected policy updates.

Increasing episodes improved stability, shown clearly through moving-average plots.

More obstacles increased exploration time and affected early convergence.

(Diagrams, accuracy charts, and comparisons can be added inside your report/ folder.)

# 🧪 How to Run
pip install -r requirements.txt
python trainer.py


# To change algorithms:

alg = "q_learning"     # or "sarsa", "expected_sarsa"


## To modify episodes or obstacles, adjust parameters in trainer.py.

# 🎯 Future Enhancements

Add Deep Q-Network (DQN) version

Add GUI for easier grid editing

Add heatmaps for learned Q-values

Add stochastic transitions and variable rewards

# 📄 License

This project is open-source and available under the MIT License.
