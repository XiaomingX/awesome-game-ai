# Awesome-Game-AI

A curated list of game AI resources on **multi-agent** learning, focusing on recent advances and impactful projects.

## What is Game AI?

Game AI focuses on predicting which actions should be taken based on current conditions. For popular games like [Starcraft](https://en.wikipedia.org/wiki/StarCraft) and [Dota 2](https://en.wikipedia.org/wiki/Dota_2), developers have designed sophisticated AI systems to enhance player experience.

## Single-Agent vs. Multi-Agent

Single-agent environments involve one player, like [Deep Q-learning](https://www.nature.com/articles/nature14236) applied to Atari Games. Multi-agent environments are more complex since each player must consider other players' actions. Notable breakthroughs include [AlphaGo](https://en.wikipedia.org/wiki/AlphaGo), [AlphaZero](https://deepmind.com/blog/article/alphazero-shedding-new-light-grand-games-chess-shogi-and-go), and expert-level performance in poker with [Libratus](https://science.sciencemag.org/content/359/6374/418) and [DouZero](https://github.com/kwai/DouZero). Human-level AI has been achieved in [Dota 2](https://openai.com/five/) and [Starcraft 2](https://deepmind.com/blog/article/alphastar-mastering-real-time-strategy-game-starcraft-ii).

## Perfect Information vs. Imperfect Information

Perfect information games (e.g., Chess, Go) allow each player access to all game information. In imperfect information games (e.g., Poker), players have limited information, making these games more challenging.

## Open-Source Projects

### Unified Toolkits
- **RLCard**: A Toolkit for Reinforcement Learning in Card Games [[paper](https://arxiv.org/abs/1910.04376)] [[code](https://github.com/datamllab/rlcard)].
- **OpenSpiel**: A Framework for Reinforcement Learning in Games [[paper](https://arxiv.org/abs/1908.09453)] [[code](https://github.com/deepmind/open_spiel)].
- **Unity ML-Agents Toolkit** [[paper](https://arxiv.org/abs/1809.02627)] [[code](https://github.com/Unity-Technologies/ml-agents)].
- **Alpha Zero General** [[code](https://github.com/suragnair/alpha-zero-general)].

### Texas Hold'em Projects
- **DeepStack-Leduc** [[paper](https://arxiv.org/abs/1701.01724)] [[code](https://github.com/lifrordi/DeepStack-Leduc)].
- **DeepHoldem** [[code](https://github.com/happypepper/DeepHoldem)].
- **OpenAI Gym No Limit Texas Hold 'em Environment** [[code](https://github.com/wenkesj/holdem)].

### Dou Dizhu Projects
- **PerfectDou**: Dominating DouDizhu with Perfect Information Distillation [[code](https://github.com/Netease-Games-AI-Lab-Guangzhou/PerfectDou)].
- **DouZero**: Mastering DouDizhu with Self-Play Deep Reinforcement Learning [[code](https://github.com/kwai/DouZero)].

### Starcraft Projects
- **StarCraft II Learning Environment** [[paper](https://arxiv.org/abs/1708.04782)] [[code](https://github.com/deepmind/pysc2)].
- **A reimplementation of Alphastar based on DI-engine with trained models** [[code](https://github.com/opendilab/DI-star)].

## Review and General Papers
- **Deep reinforcement learning from self-play in imperfect-information games**, arXiv 2016 [[paper](https://arxiv.org/pdf/1603.01121.pdf)].

## Research Papers

### Dou Dizhu
- **PerfectDou**: Dominating DouDizhu with Perfect Information Distillation, NeurIPS 2022 [[paper](https://arxiv.org/abs/2203.16406)] [[code](https://github.com/Netease-Games-AI-Lab-Guangzhou/PerfectDou)].
- **DouZero**: Mastering DouDizhu with Self-Play Deep Reinforcement Learning, ICML 2021 [[paper](https://arxiv.org/abs/2106.06135)] [[code](https://github.com/kwai/DouZero)].

### Mahjong
- **Suphx**: Mastering Mahjong with Deep Reinforcement Learning, arXiv 2020 [[paper](https://arxiv.org/abs/2003.13590)].

### Go
- **Mastering the game of Go without human knowledge**, Nature 2017 [[paper](https://www.nature.com/articles/nature24270)].

### Starcraft
- **Grandmaster level in StarCraft II using multi-agent reinforcement learning**, Nature 2019 [[paper](https://www.nature.com/articles/s41586-019-1724-z)].

## Conferences and Workshops
- **IEEE Conference on Games (CoG)**: Latest developments in computational intelligence and AI applied to games [[website](http://ieee-cog.org/2020/)].

## Competitions
- **Annual Computer Poker Competition**: Highlights advancements in AI for imperfect-information games [[website](http://www.computerpokercompetition.org/)].

## Related Lists
- **Awesome StarCraft AI** [[GitHub](https://github.com/SKTBrain/awesome-starcraftAI)].
