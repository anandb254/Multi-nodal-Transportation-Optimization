# Multimodal Transportation Optimization

## Project Overview
This project focuses on optimizing delivery services by minimizing transportation costs through the use of various transportation tools like trucks, airplanes, and ships. It considers factors such as goods consolidation, different transportation costs, and delivery time constraints. The project utilizes mathematical programming to model the situation and find a cost-minimizing solution. Two frameworks, **DOcplex** (by IBM) and **CVXPY** (open-source by Stanford), are used for the model construction.

## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Assumptions](#assumptions)
- [Dimension & Matrixing](#dimension--matrixing)
- [Decision Variables](#decision-variables)
- [Parameters](#parameters)
- [Mathematical Modelling](#mathematical-modelling)
- [Optimization Result & Solution](#optimization-result--solution)
- [Model Use & Extension Guide](#model-use--extension-guide)
- [Acknowledgements](#acknowledgements)

## Problem Statement
The goal is to optimize transportation costs by choosing the most efficient routes and transportation tools while meeting delivery time constraints and considering goods consolidation.

## Assumptions
The model makes certain assumptions, such as specific transportation costs, time constraints, and goods consolidation scenarios.

## Dimension & Matrixing
The model includes dimensions like ports, goods, and time. It uses matrixing to represent the transportation scenarios.

## Decision Variables
Decision variables include transportation routes, tools, and goods consolidation choices.

## Parameters
Parameters in the model consist of transportation costs, delivery times, and constraints related to goods and routes.

## Mathematical Modelling
The project employs mathematical programming to construct a model that minimizes transportation costs. It sets up objective functions and constraints to represent the transportation scenarios.

## Optimization Result & Solution
The model's results, including the minimized cost value and optimal routes for all goods, are processed using the **txt_solution()** function and saved in a text file called [**Solution.txt**](https://github.com/hzjken/multimodal-transportation-optimization/blob/master/Solution.txt).

## Model Use & Extension Guide
To use the model, download the [**multi-modal transportation.py**](https://github.com/hzjken/multimodal-transportation-optimization/blob/master/multi-modal%20transportation.py) and [**model data.xlsx**](https://github.com/hzjken/multimodal-transportation-optimization/blob/master/model%20data.xlsx) files from the repository. Users can modify the parameters in the Excel file to fit their case, run the Python file, and generate the **Solution.txt**. The code is written in an object-oriented format, making it easy to modify or extend for more complex situations.
