# P2: Continuous control project
I will train agents to track balls with different speed.

![Continuous control](giphy.gif)

The goal of my agents is to keep the goal state hitting balls.
- Reward = +0.1 for each step being in the goal position.
- The state space: 33 dimension
- algorithm modulates: position, rotation, velocity, and angular velocities of the arm

For actions, a vector corresponding to two joints' torque 
- the number between -1 and 1.

## Getting started:
```bash
pip install -r requirements.txt
```

## Intructions
Please check the detail in 'Continuous_Control.ipynb' file.
