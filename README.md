# Report of Reinforcement Learning Experimentation 

>
> *This repository is forked from https://github.com/rlcode/reinforcement-learning*
>-

## Prerequiesites

### Dependencies
1. Python 3.5x
2. Tkinter
3. PIL

Before installing these, i suggest to setup a python environment:

```
python -m venv env
```

Activate it:

* Windows

```
env/Scripts/activate
```

* Linux

```
source /path/to/ENV/bin/activate
```

Install all prerequisites:

```
pip install -r requirements.txt
```

## How to run

Run python file related to name of model, e.g grid world with policy iteration:

```
python policy_iteration.py
```

# Explanation of running program


1. [Grid World with Policy Iteration](./1-grid-world/1-policy-iteration)
2. [Grid World with Value Iteration](./1-grid-world/2-value-iteration)
3. [Grid World with Monte Carlo](./1-grid-world/3-monte-carlo)
4. [Grid World with SARSA](./1-grid-world/4-sarsa)
5. [Grid World with Q-Learning](./1-grid-world/5-q-learning)