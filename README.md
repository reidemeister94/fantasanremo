
# FantaSanremo 2023

A little experiment for predicting the best team of 5 performers for the 2023 edition of the Italian Festival of Sanremo, with python.

The game is explained in detail at [fantasanremo.com](https://fantasanremo.com/), but the main rules are like any other fantasy game: you have X credits (100 in this case) for building your team, composed by N singers (5 in this case).

For the computation of the costs and scores of the singers, some data is collected from:

- [fantasanremo.com](https://fantasanremo.com/)
- [goldbet.it](https://www.goldbet.it/)
- [unibet.com](https://www.unibet.it/)

The task is, in the end, an [optimization problem](https://en.wikipedia.org/wiki/Optimization_problem) that I solved using [Pulp](https://coin-or.github.io/pulp/), which is one of the best LP modelers written in Python.

## Requirements

-------------
In order to use the notebook, first install the necessary packages with

```bash
pip install -r requirements.txt
```
