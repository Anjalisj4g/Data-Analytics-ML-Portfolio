# Business Optimization Using Linear Programming
### Project Overview

This project demonstrates how optimization techniques can be used to solve real-world business problems. Using Linear Programming and the PuLP library in Python, the project determines the optimal production quantities for two products to maximize profit while satisfying resource constraints.

Optimization models like this are widely used in industries such as manufacturing, logistics, finance, and supply chain management.

### Business Problem

A manufacturing company produces two products:

Product A – Electronic Component

Product B – Mechanical Component

The company has limited resources such as labor hours and raw materials. The objective is to determine how many units of each product should be produced to maximize total profit.
| Resource      | Product A | Product B | Total Available |
| ------------- | --------- | --------- | --------------- |
| Labor Hours   | 2         | 1         | 40              |
| Raw Materials | 1         | 3         | 60              |

| Product   | Profit |
| --------- | ------ |
| Product A | $20    |
| Product B | $30    |

### Objective

Maximize total profit:

Profit = 20A + 30B

Subject to:

2A + B ≤ 40
A + 3B ≤ 60
A ≥ 0, B ≥ 0

### Technologies Used :

* Python

* PuLP (Linear Programming Library)

* NumPy

* Matplotlib

* Jupyter Notebook

### Project Workflow

- Define the business problem

- Formulate the optimization model

- Implement the model using PuLP

- Apply constraints

- Solve the optimization problem

- Visualize the feasible region

- Interpret the results and derive business insights

### Results

The optimization model determines the optimal production strategy.

Optimal Production Plan:

Product A: 12 units

Product B: 16 units

Maximum Profit Achieved:

$720

This solution ensures that all resource constraints are satisfied while maximizing profit.

### Visualization

The project also includes a visualization of the constraint lines and feasible region, helping to better understand how the optimal solution is determined.

### Installation

Install the required libraries using:

pip install pulp numpy matplotlib

### Applications of Optimization

Optimization techniques like Linear Programming are used in:

* Production planning

* Supply chain optimization

* Transportation and logistics

* Resource allocation

* Financial portfolio optimization

#### Author

#### Anjali J
