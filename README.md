# Single Region Energy System Optimisation Project
![Python](https://img.shields.io/badge/Python-3.14-blue)
![Static Badge](https://img.shields.io/badge/Status-In_Progress-orange)
## Project Overview

This project implements a linear optimisation model of an electricity system for a single region.
The model determines the cost-optimal generation mix and dispatch under different policy and system constraints.

It was developed to demonstrate skills in:
- Python programming
- Data analysis & processing
- Mathematical optimisation (linear programming)
- Scenario modelling
- Data visualisation

## Objectives

The goal of the model is to:
   
  *Minimise total system cost while meeting electricity demand
    subject to technical, economic, and policy constraints.*

The optimisation considers:
- Generation technologies (e.g., wind, solar, fossil)
- Capacity limits
- Demand balance
- Policy constraints (carbon tax, land limits, subsidies)

## Methodology
The model is formulated as a linear programming (LP) problem and solved using:
- PuLP – optimisation modelling
- pandas – data handling
- matplotlib – visualisation
- Solver - CBC, used directly through Pulp in Python

Core Components
* Decision variables:
    * Installed generation capacity
    * Electricity dispatch
* Objective function:
    * Minimise total system costs
* Constraints:
  * Demand satisfaction
  * Capacity limits
  * Policy scenarios

## Scenarios Analysed
The project evaluates how different constraints affect the optimal system design:
* Baseline scenario
* Carbon tax scenario
* Land constraint scenario
* Subsidy scenario

This enables comparative policy analysis.

## Example Outputs
