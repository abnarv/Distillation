Python toolkit for chemical process optimisation, applied to distillation columns. 
Includes thermodynamic modelling, numerical methods and optimisation algorithms to determine optimal column configurations.
Distillation column crop up in all chemical processes, and account for 40-50% of energy utilised in seperation process. 
Parameters such as reflux ratio, number of trays, feed tray location influence the trade off between capital cost and energy cost.
## Current Features
- **VLE Modeling**: NRTL activity coefficient model for non-ideal binary 
  mixtures, validated against experimental ethanol-water data (azeotrope 
  at x≈0.894)
- **Bubble Point Solver**: Newton-Raphson iterative solver for 
  vapor-liquid equilibrium temperature/composition
## Tech Stack
Python · NumPy · SciPy · Pandas · Matplotlib
