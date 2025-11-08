# Benders Algorithm with GLPK Implementation

## Intialization
To install `swiglpk` please run the command in your terminal:

`pip install swiglpk-5.0.5-cp310-cp310-win_amd64.whl`

Then using:

`import swiglpk as glpk`

## Functionality
This project fulfills functions for solving the decomposition problem by Benders algorithm:
- Solving the `master` and `sub-problem`
- Providing unbounded ray when a `feasible cut` is required for certain iterations
- Generating cuts for each iteration

## Copyrights
This project is finished and published by KAS Wei