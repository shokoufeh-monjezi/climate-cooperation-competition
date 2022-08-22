## Training Reinforcment Learning Agent with Simulation Code
Comprehensive global cooperation is essential to limit global temperature increases while continuing economic development, e.g., reducing severe inequality or achieving long-term economic growth. Achieving long-term cooperation on climate change mitigation with n strategic agents poses a complex game-theoretic problem. 
The RICE-N IAM is an agent-based model that incorporates **DICE climate-economic dynamics** and **multi-lateral negotiation protocols** between several fictitious nations.

**Tutorial.ipynb**: It provides examples on modifying the code to implement different negotiation protocols. It describes ways of changing the agent observations and action spaces corresponding to the proposed negotiation protocols and implementing the negotiation logic in the provided code. It has a walkthrough of how to train RL agents with the simulation code and how to visualize results from the simulation after running it with a set of agents.

In this notebook two examples of GPU-based training with WarpDrive are presented:

1. The first example does not include negotiation between regions. Since there is no direct interaction between the different regions without negotiation, total runtime is ~2 minutes.

2. The second example includes negotiations between regions. These negotiations take place according to the negotiation protocol outlined in rice.py. Total runtime is 15~20 minutes.


## About Quick Deploy
The quick deploy feature automatically sets up the Vertex AI instance with an optimal configuration, preloads the dependencies, runs the software from NGC without any need to set up the infrastructure.
