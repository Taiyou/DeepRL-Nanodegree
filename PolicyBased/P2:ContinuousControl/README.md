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
1. first install all the requirements from the requirements.txt
```bash
pip install -r requirements.txt
```
2. install the Unity environment
Version 2: Twenty (20) Agents
Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

3. start the program
Please check the detail in 'Continuous_Control.ipynb' file.
