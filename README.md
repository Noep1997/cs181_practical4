# Harvard CS181 - Practical 4 - Team Les_Caribous
# Philippe Noël, Jorma Görns, Arjun Verma

We implemented Q-Learning to train an agent to perform well on the game SwingyMonkey, which is a replica of the popular smartphone game Flappy Bird. We added multiple layers of thinking over Q-Learning, including a discretization of the state space, an approximation of gravity, a decaying epsilon-greedy policy and a decaying learning rate based on how many visits the current state has received.

In order to run our model, simply download the repository and run "python stub.py". If you want to play the game for yourself, run "python SwingyMonkey.py"
