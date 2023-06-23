It's a machine learning training method based on rewarding desired behaviours and punishing undesired ones.

There are basically four factors to take into account:

1. State (s): a possible state the system can be at
2. Action (a): an action that can happen upon the system
3. Reward (R(s)): a reward from state s
4. State prime (s-prime): a new state after action a

On top of those factors, the algorithm makes several calculations, for example the returns for each state and subsequent actions.

Return = R1 + gamma * R2 + gamma^2 * R3 + ...

Here the gamma variable is called as discount factor. Below there is an example calculating the returns (in red) for each state (1 to 6) based on the actions (yellow arrow).

![[Reinforcement Learning example of return.png]]

Thus the goal in reinforcement learning is to find a policy (pi) that tells you what action (a = pi(s)) to take in every state (s) so as to maximize the return.

The state of each system will vary according to the problem, on the previous example this was a discrete case. Now, for a continuous case, for example, if you are dealing with the control of a moving truck, the state might have 6 numbers looking like:

- x: the x position
- y: the y position
- theta: the orientation angle
- x-dot: how quickly the x coordinate is changing
- y-dot: how quickly the y coordinate is changing
- theta-dot: how quickly the angle is changing

So basically, position and speed.

One possibility to train a reinforcement learning algorithm is to use a neural network, where the input x would be the state (s) and the action (a) and the target would be the [[Bellman Equation]] (Q(s, a)), illustrated below.

![[Reinforcement Learning - deep learning structure.png]]

Learning the algorithm would look like this:

1. Initialize the neural network randomly as guess of Q(s, a).
2. Repeat the following steps:
	1. Get (s, a, R(s), s-prime)
	2. Store 10K cases of the tuple of 1.
	3. Train the NN with those 10K cases
		1. x = (s, a)
		2. y = R(s) + gamma * max Q(s-prime, a-prime)
	4. Train Q_new such as Q_new(s, a) approximates to y