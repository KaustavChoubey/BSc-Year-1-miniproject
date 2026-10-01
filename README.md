# miniproject

# Random Walk on Polygons 🐜

This repository contains a **first-year BSc Mathematics mini-project** exploring a simple random walk on the vertices of a polygon through both simulation and combinatorial analysis.

The original problem considers **Annie the Ant**, who starts at vertex $0$ of a pentagon. At every step, she independently moves one vertex clockwise or anticlockwise with equal probability.

## The Problem

For a walk of seven steps on a pentagon, the project asks:

> **What is the probability that Annie finishes at each vertex?**

A Python simulation of **1,000,000 random walks** was used to estimate the endpoint distribution.

The probabilities are then derived analytically by representing a clockwise step by $+1$ and an anticlockwise step by $-1$ and counting the corresponding sequences using binomial coefficients.

For the seven-step pentagon problem, the analysis explains why **vertices 1 and 4 are the most likely final positions**.

## Generalisations

The project also considers a walk of $n$ steps on a polygon with $s$ sides and explores:

- the endpoint distribution for general $n$ and $s$;
- parity restrictions for random walks on polygons with an even number of sides;
- the behaviour of the distribution as the number of steps becomes large.

For a pentagon, the endpoint probabilities approach one another as the number of steps grows, illustrating the approach toward a uniform distribution over the vertices.

## Tools

**Python · Probability · Combinatorics · Random Walks**

## Project

**Kaustav Choubey**  
*BSc Mathematics — Year 1 Mini Project*  
2020
