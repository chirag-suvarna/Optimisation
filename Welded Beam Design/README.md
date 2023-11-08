Welded Beam Design Optimization
This project optimizes the design of a welded beam using metaheuristic algorithms. It is implemented as a university assignment in a Jupyter notebook.

Problem Definition
The goal is to minimize the cost function f(x) subject to 4 constraints g1(x), g2(x), g3(x), g4(x).

The design variables are:

x1 = beam height
x2 = beam length
x3 = beam thickness
x4 = beam breadth
The full problem is defined in problem-spec.pdf.

The key constraints are:

g1(x) = Shear stress limit
g2(x) = Normal stress limit
g3(x) = Weld height limit
g4(x) = Buckling load limit
See the assignment specification for full mathematical definitions.

Algorithms
Two optimizers are implemented:

Random search
Simulated annealing
The code is in optimization.ipynb.

Key techniques used:

Constraint handling via feasibility checks
Stochastic sampling within variable bounds
Objective function and constraint evaluations
The notebook also contains performance analysis and visualizations.

Usage
The code requires Python 3 and common packages like NumPy and Matplotlib.

See requirements.txt for the full list.

Simply run the notebook cells to execute the optimization and see the results.

Results
The simulated annealing algorithm converges to better optima than random search. See the notebook for full details.

References
Gong W., Cai Z., Zhu L. (2009) An efficient multiobjective differential evolution algorithm for engineering design. Struct Multidisc Optim 38, 137–157.
