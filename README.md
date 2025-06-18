# Description
Python code to generate JONSWAP wave spectrum in OrcaFlex and locate the maximum Hs based on certain location of the vessel. This is practical to cut down the simulation time when running analysis using irregular wave. The simulation will then run by taking the *exact same seed number* for that particular wave height, and run it only at the time of the maximum wave height ±300s before and after the maximum Hs. 

# Software Integration
OrcaFlex
OrcaWave
