# 🐧 Penguin Slide RL  
### Reinforcement Learning Project using Q-Learning, SARSA, and Expected SARSA  
### Includes Interactive Jupyter UI + Pygame Animation

This project implements a Reinforcement Learning (RL) agent (a penguin) that learns to navigate an **8×8 gridworld** containing:

- Safe ice tiles  
- Holes (fall = terminal negative reward)  
- Rocks (blocked tiles)  
- A goal tile (terminal positive reward)

The environment is **randomly generated each training run**, and users can control the number of **holes** and **rocks** using sliders in the notebook.

The agent is trained using three RL algorithms:

1. **Q-Learning** (Off-policy)  
2. **SARSA** (On-policy)  
3. **Expected SARSA** (Expected TD update)

After training, the learned policy is visualized through a **Pygame animation**, where a small penguin moves across the grid following its optimal path.

---

## 🚀 Features

- Fully interactive **Jupyter Notebook UI**
- Slider controls for:
  - Episodes
  - Algorithm selection
  - Number of holes
  - Number of rocks
  - Animation speed
- Dynamically generated maps each run
- Three RL algorithms implemented:
  - Q-Learning  
  - SARSA  
  - Expected SARSA  
- Clean reward plots with **moving average visualization**
- Smooth Pygame animation of the learned policy
- Q-table saving and loading support
- Penguin drawn procedurally without external assets
- Fast, optimized training loop

---

## 🧠 Algorithms Implemented

### **Q-Learning**
- Off-policy TD control  
- Learns the optimal future reward  
- Fastest convergence

### **SARSA**
- On-policy TD control  
- Learns based on the action actually taken  
- More conservative

### **Expected SARSA**
- Uses expected return  
- Most stable on dynamic maps  
- Best overall success rate

---

## 📦 Installation

### 1. Create a virtual environment (recommended)

```bash
python -m venv penguin_env
