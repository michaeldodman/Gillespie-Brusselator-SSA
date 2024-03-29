# Gillespie-Brusselator-SSA

## Description
An object-oriented MATLAB implementation of the Gillespie [1] and the 'Brusselator' [2] stochastic simulation algorithms.
<div style="display: flex; align-items: center; justify-content: center;">
    <img src="./Project Resources/graph1.png" alt="Graph 1" style="width: 49%; height: auto; max-height: 400px; margin-right: 10px;" />
    <img src="./Project Resources/graph2.png" alt="Graph 2" style="width: 49%; height: auto; max-height: 400px;" />
</div>




## Dependencies
This project requires only MATLAB to run the stochastic simulation algorithms, however the Signal Processing Toolbox and the Statistics and Machine Learning Toolbox are used for subsequent analysis of the simulations.

## Usage

Run the ```main.m``` file with the class file ```ChemicalReaction.m``` in the same directory, and the ChemicalReaction objects will be instantiated, calculations will be executed, and results of the simulation and analysis will be displayed.

## References

[1] Gillespie, D. T. (1977). “Exact Stochastic Simulation of Coupled Chemical Reactions”. The Journal of Physical Chemistry. 81 (25): 2340-2361. doi: 10.1021/j100540a008

[2] I. Prigogine, _From Being to Becoming: Time and Complexity in the Physical Sciences_, New York: W.H. Freeman and Company, 1980
