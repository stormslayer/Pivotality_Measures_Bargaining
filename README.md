# Pivotality Measures
Calculate Shapley, Banzhaf, minimum integer weights, and other pivotality measures for bargaining / coalition games

Email: de Marchi, Scott (scott.demarchi@gmail.com)  
Cite: de Marchi, Scott, Max Gallop, and Michael Laver. "Pivotality Measures". https://github.com/stormslayer/Minimum_Integer_Weights. 2023
and, de Marchi, Scott, and Michael Laver. The Governance Cycle in Parliamentary Democracies. Cambridge University Press, 2023.

# To use:
* install Anaconda (3.x): https://www.anaconda.com/products/individual
* install pulp: https://pypi.org/project/PuLP/
* Legacy code miw3.1.py: input list (line 16) or edit miw3.1.py (line 17) -- code expects a list of raw seats in a legislature.  Entering a system with a majority party will cause unexpected results.
* Current code shapley_plus_individualweights_1.4: edit list of datafiles in model_params_measures_example.xlsx and change name to model_params_measures.xlsx.  Outputs to a flat file. 
* For more information, see:https://www.journals.uchicago.edu/doi/abs/10.1086/706462 and https://www.cambridge.org/core/books/governance-cycle-in-parliamentary-democracies/A2FDF6AEE7F9C5E9C67B43E7333E5BF1
* Data files are found in https://github.com/stormslayer/replication_data_parliamentary_democracies

