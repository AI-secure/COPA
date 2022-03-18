# COPA: Certifying Robust Policies for Offline Reinforcement Learning against Poisoning Attacks

We propose COPA, the first unified framework for certifying robust policies for general ofﬂine RL against poisoning attacks, based on certification criteria including *per-state action stability* and *the lower bound of cumulative reward*. Specifically, we propose new partition and aggregation protocols *(PARL, TPARL, DPARL)* to obtain robust policies and provide certification methods for them. More details can be found in our paper: 

*Fan Wu, Linyi Li, Chejian Xu, Huan Zhang, Bhavya Kailkhura, Krishnaram Kenthapadi, Ding Zhao, and Bo Li*, "COPA: Certifying Robust Policies for Offline Reinforcement Learning against Poisoning Attacks"

[ICLR 2022](https://openreview.net/forum?id=psh0oeMSBiF)

All experimental results are available at the website https://copa-leaderboard.github.io/.

## Code

In our paper, we conduct experiments on Atari games Freeway and Breakout, as well as an autonomous driving environment Highway. For each RL environment, we evaluate three RL algorithms (DQN, QR-DQN, and C51), three aggregation protocols and certification methods (PARL, TPARL, and DPARL), up to three partition numbers, and multiple horizon lengths. 

Reference implementation for experiments on Atari games can be found at https://github.com/AI-secure/COPA_Atari.

Reference implementation for experiments on Highway can be found at https://github.com/AI-secure/COPA_Highway.