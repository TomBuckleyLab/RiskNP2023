# RiskNP2023
Julia code and associated files for dynamic physiological simulations in:

TN Buckley, EH Frehner, BN Bailey (2023) Kinetic factors of physiology and the dynamic light environment influence the economic landscape of short-term hydraulic risk. New Phytologist (in press)

This code was written and implemented using Julia v1.5.3 in the Atom editor V 1.50.0 x64, in Windows 10 Pro, in 2021 and 2022.

The code refers to several external objects:
 - c:/rootdir.jl: Julia file containing reference to root directory for research files on any given computer
 - parameter.csv: file containing default simulation parameter values
 - times.txt: file containing times of day for rows in Helios (light model) output files
 - positions.txt: same, for leaf positions
 - positions.csv: same but for special light output file containing artificial sunflecks of fixed duration and intensity
 - many files each named timeseries_leafNNNNNN.txt, where NNNNNN is the leaf number (between 000000 and 009999 in this study). Twenty sample input files are included here; more can be generated using Helios (https://github.com/PlantSimulationLab/Helios).
 
 Explanation of the mathematical basis of these simulations and their application in the study reference above can be found in the published paper itself and its accompanying Supporting Information. This read-me file will be updated with a doi to the paper once I have it.
 
 
