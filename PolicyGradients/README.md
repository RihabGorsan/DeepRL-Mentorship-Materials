# REINFORCE

### Instructions

Open `REINFORCE->PPO.ipynb` to see a detailed implementation of REINFORCE (also known as Monte Carlo Policy Gradients) with OpenAI Gym's Cartpole environment.
At the end of the notebook, we will cover the main problems of REINFORCE such as:
* High variance gradients.
* Credit Assignement.
* Update inefficiency.

And then we'll see how to mitigate these problems using importance sampling, a tricky approximation of policy steps as well as a clipping step resulting at the end in creating a new objectif funtion called **Clipped Surrogate Function** that introduces to us **Proximal Policy Optimization** algorithm.

Implementation of PPO is covered in `pong-PPO.ipyng`, check how to train agent to play pong using PPO. 
