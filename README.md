# Linear-Programming-Solver

`variables.txt`
  List all variable names each in one line.
  
`constraints.txt`
  Each constraint in one line.
  Follow the spacing.
  ex: 2x+3y-4z >= 5 should be written as (2)(x)+(3)(y)+(-4)(z) >= 5
  
`objective.txt`
  'Max' in first line if the objective function is to maximize, else 'Min'
  objective funtion in next line with proper spacing.
  ex: Maximize 2x+3y-4z show be written as
  Max
  (2)(x)+(3)(y)+(-4)(z)
  
Command to run: python3 custom_solver.py

Requirements: Goolge OR-Tool (`pip3 install --upgrade --user ortools`)

