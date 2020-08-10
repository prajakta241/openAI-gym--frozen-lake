FROZENLAKE-GAME
Now, lets see what is the FrozenLake game.
Imagine, you are standing on a frozen lake. The lake is not all frozen, there are some parts where the ice is very thin. You goal is to go from place S to G without falling into the holes.
Here, S is the starting point, G is the goal, F is the solid ice where the agent can stand and H is the hole where if the agent goes, it falls down.
The agent has 4 possible moves which are represented in the environment as 0, 1, 2, 3 for left, right, down, up respectively.
For every state F, the agent gets 0 reward, for state H it gets -1 reward as in state H the agent will die and upon reaching the goal, the agent gets +1 reward.
