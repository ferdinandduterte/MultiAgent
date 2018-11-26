# Multi-Agent Reinforcement Learning
## Using tensorflow
[DQN](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf), [DDPG](https://arxiv.org/abs/1509.02971) and [MADDPG](https://arxiv.org/abs/1706.02275) implementations to play tag in OpenAI's [multi-agent particle environment](https://github.com/openai/multiagent-particle-envs).

  DQN 1 vs 1  |   DQN 1 vs 2  |   DQN 2 vs 1
:------------:|:-------------:|:-------------:
![](gifs/dqn_1vs1.gif "1 vs 1") | ![](gifs/dqn_1vs2.gif "1 vs 2") | ![](gifs/dqn_2vs1.gif "2 vs 1")
  DDPG 1 vs 1 |  DDPG 1 vs 2  |  DDPG 2 vs 1
![](gifs/ddpg_1vs1.gif "1 vs 1") | ![](gifs/ddpg_1vs2.gif "1 vs 2") | ![](gifs/ddpg_2vs1.gif "2 vs 1")
MADDPG 1 vs 1 | MADDPG 1 vs 2 | MADDPG 2 vs 1
![](gifs/maddpg_1vs1.gif "1 vs 1") | ![](gifs/maddpg_1vs2.gif "1 vs 2") | ![](gifs/maddpg_2vs1.gif "2 vs 1")

## Implementations : Commands
    DQN 1 vs 1 : python dqn_tag.py --render 
    DQN 1 vs 2 : python dqn_tag.py --render --env  simple_tag_guided_1v2
    DQN 2 vs 1 : python dqn_tag.py --render --env  simple_tag_guided_2v1
    DDPG 1 vs 1 : python ddpg_tag.py --render 
    DDPG 1 vs 2 : python ddpg_tag.py --render --env  simple_tag_guided_1v2
    DDPG 2 vs 1 : python ddpg_tag.py --render --env  simple_tag_guided_2v1
    MADDPG 1 vs 1 : python maddpg_tag.py --render 
    MADDPG 1 vs 2 : python maddpg_tag.py --render --env  simple_tag_guided_1v2
    MADDPG 2 vs 1 : python maddpg_tag.py --render --env  simple_tag_guided_2v1


## CREDITS:
    - Codes from: https://github.com/rohan-sawhney/multi-agent-rl
