---
title: "Constructing Ancestral Recombination Graphs through Reinforcement Learning"
authors : Mélanie Raymond, Marie-Hélène Descary, Cédric Beaulac and Fabrice Larribe
collection: publications
permalink: /publication/ARGRL
status : Published
venue : Frontiers in Genetics - Computational Genomics
date: 2025-04-28
paperurl: 'https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2025.1569358/full'
---

Published in [Frontiers in Genetics - Computational Genomics](https://www.frontiersin.org/journals/genetics).

### Abstract :

*Introduction: Over the years, many approaches have been proposed to build ancestral recombination graphs (ARGs), graphs used to represent the genetic relationship between individuals. Among these methods, many rely on the assumption that the most likely graph is among those with the fewest recombination events. In this paper, we propose a new approach to build maximum parsimony ARGs: Reinforcement Learning (RL).*

_Methods: We exploit the similarities between finding the shortest path between a set of genetic sequences and their most recent common ancestor and finding the shortest path between the entrance and exit of a maze, a classic RL problem. In the maze problem, the learner, called the agent, must learn the directions to take in order to escape as quickly as possible, whereas in our problem, the agent must learn the actions to take between coalescence, mutation, and recombination in order to reach the most recent common ancestor as quickly as possible._

_Results: Our results show that RL can be used to build ARGs with as few recombination events as those built with a heuristic algorithm optimized to build minimal ARGs, and sometimes even fewer. Moreover, our method allows to build a distribution of ARGs with few recombination events for a given sample, and can also generalize learning to new samples not used during the learning process._

_Discussion: RL is a promising and innovative approach to build ARGs. By learning to construct ARGs just from the data, our method differs from conventional methods that rely on heuristic rules or complex theoretical models._

Download a pre-print of the paper [here](https://arxiv.org/pdf/2406.12022). The official paper is available [here](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2025.1569358/full). 
