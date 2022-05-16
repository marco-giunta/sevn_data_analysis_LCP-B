# SEVN data analysis (LCP-B exam)
 
This repository contains a backup of the pull request with the final version of the assignment delivery.

We analyzed data of simulated star binary systems obtained using SEVN to study the impact of metallicity and common envelope parameters on the probability of producing a significant GW emission via merger. 
Highlights of this project include:
- we preprocessed data to select potentially merging systems using a parallel, fast dask-based pipeline;
- we accurately computed merge times using a variety of numerical integration techniques to solve GR equations;
- we used info. theory to determine the impact of (Z,a) on the merge probability, using mutual information as a more general correlation coefficient (capable of detecting nonlinear dependences, too).
