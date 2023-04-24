# PIPP-PD-sampling

Proposition of a variety of Pairwise Interacting Point Processes (PIPP) models for representig Persistence Diagrams(PD) are studied to compare and contrast with an existing PIPP. 
To evaluate the efficiency of these point process models, we generate samples of PDs using a reversible
jump Markov chain monte carlo approach. 
We find that two other point process models provide similar efficiency regarding the accuracy and computational cost.

PD_generation.ipynb is used to create synthetic PD example. this may be omited if you input a PD as a kx2 numpy array file. If omited, all codes must be screened to adjust the emperically chosen parameters.

Naming convention for the RJ-MCMC samplers is 'interaction'-'spatial'.

If recreating, run RunningAvg_Gauss.ipynb before RunningAvg_Voro.ipynb to transfer over data files for images
To run only the runnign averages, files in PDchains folder must be unzipped and be placed in the PDchains folder.

The existing PIPP in referce is from  Papamarkou 2021 'A Random Persistence Diagram Generator' https://arxiv.org/abs/2104.07737
