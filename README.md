# Reinforcement Learning Implementations

This repository contains notebook-based implementations and experiments for core reinforcement learning algorithms using Python, PyTorch, and Gymnasium.

## Algorithms and Experiments

- Tabular Q-learning for `Taxi-v3`, including action masking and statistical comparison notebooks.
- Deep Q-Network (DQN) for `LunarLander-v3`.
- REINFORCE policy gradient for `InvertedPendulum-v4`.
- Advantage Actor-Critic (A2C) experiments for `LunarLander-v3`.
- Introductory Gymnasium experiments with environments such as `Blackjack-v1`, `CartPole-v1`, and `CarRacing-v3`.

## Concepts Covered

- Markov Decision Processes (MDPs)
- Bellman updates
- Exploration vs. exploitation
- Q-tables and action masking
- Experience replay
- Target networks
- Policy gradients
- Actor-critic learning

## Tech Stack

- Python
- Jupyter Notebook
- Gymnasium
- PyTorch
- NumPy, pandas, matplotlib, and seaborn

## Project Structure

```text
RL/
|-- A2C/
|   `-- Lunar Lander/
|-- DQN/
|   `-- Lunar Lander/
|-- Project1/
|   |-- blac_jack.ipynb
|   `-- test.ipynb
|-- Reinforce/
|   `-- Invereted Pendulum/
|-- Tabular Q/
|   `-- Taxi agent/
|-- requirements.txt
`-- README.md
```

## Setup

Create and activate a virtual environment:

```bash
python -m venv .venv

# Windows PowerShell
.\.venv\Scripts\Activate.ps1

# macOS/Linux
source .venv/bin/activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Some Gymnasium environments used in this project require optional simulation dependencies:

- `LunarLander-v3` and `CarRacing-v3` use Box2D.
- `InvertedPendulum-v4` uses MuJoCo.
- Human rendering uses graphical packages such as pygame.

These extras are included in `requirements.txt`.

## How to Run

Start Jupyter Lab or Jupyter Notebook from the repository root:

```bash
jupyter lab
```

Then open one of the notebooks, for example:

- `Tabular Q/Taxi agent/Taxi_actionMask_agent.ipynb`
- `DQN/Lunar Lander/lunar_agent.ipynb`
- `Reinforce/Invereted Pendulum/pendulum_agent.ipynb`
- `A2C/Lunar Lander/lunar.ipynb`

Run the cells in order. For notebooks that render environments with `render_mode="human"`, make sure your environment supports opening a display window.

## License

This project is licensed under the MIT License.

## Author

Dulaksha Dulan  
Undergraduate - Artificial Intelligence  
University of Moratuwa
