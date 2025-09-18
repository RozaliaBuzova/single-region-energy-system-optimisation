# Single Region Energy System Optimisation Project

A modelling project to create a simple energy system. 

Using linear optimisation to determine electricity generation portfolio and electricity dispatch, whilst minimising cost under constraints.

## Model Inputs

Input data (e.g., technology costs, capacity factor, etc.) and modelling guidance taken from the Massice Online Open Course (MOOC) on Modelling & Measuring the Energy Transition by Politecnico di Milano on Coursera. 

Space resolution - single-region

Time resolution - years

## Model Outputs

Key outputs:

- Amount of new technology capacities required to be built
- Yearly dispatch values of each technology

## Solver

Solver - CBC, used directly through Pulp in Python
