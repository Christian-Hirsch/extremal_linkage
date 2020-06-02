# Extremal linkage network
[This notebook](./simulation.ipynb) provides the Python code for simulating [Extremal linkage networks](https://arxiv.org/abs/2006.00747).

<p align="center">
<img src="ELN.png" /></a>
</p>

We define a random network on an infinite set of layers, each consisting of <img src="http://latex.codecogs.com/svg.latex?N \ge 1" /> nodes. The node <img src="http://latex.codecogs.com/svg.latex?i \in  \{0, \dots, N - 1\}" /> in layer <img src="http://latex.codecogs.com/svg.latex?h \in \mathbb{Z}" /> has a fitness <img src="http://latex.codecogs.com/svg.latex?F_{i, h}" />, where we assume the family <img src="http://latex.codecogs.com/svg.latex?\{F_{i, h}\}_{i \in \{0, \dots, N - 1\}, h \in \mathbb{Z}}" /> to be independent and identically distributed (i.i.d.).

Then, the number of nodes on layer <img src="http://latex.codecogs.com/svg.latex?h+1" />  that are visible for the <img src="http://latex.codecogs.com/svg.latex?i" />th node in layer <img src="http://latex.codecogs.com/svg.latex?h" /> , which we call the *scope* of <img src="http://latex.codecogs.com/svg.latex?(i,h)" /> , is given by <img src="http://latex.codecogs.com/svg.latex?\varphi(F_{i, h}) \wedge" />  <img src="http://latex.codecogs.com/svg.latex?N" />, where

<img src="http://latex.codecogs.com/svg.latex?\varphi(f) = 1 + 2\lceil " /> <img src="http://latex.codecogs.com/svg.latex? f \rceil." /> 


Henceforth, we assume the fitnesses to follow a Fréchet distribution with tail index 1. That is,

<img src="http://latex.codecogs.com/svg.latex?\mathbb{P}(F \le"/><img src="http://latex.codecogs.com/svg.latex? s) = \exp(-s^{-1})." /> 



