# Fretica
Fretica is a user-extendable toolbox for analyzing single-molecule fluorescence data. It is a Wolfram Mathematica package with a backend written in C++, which has been actively developed since 2010 by D. Nettels, B. Schuler, and co-workers. From within Mathematica Notebooks, raw data can be accessed and analyzed with almost three hundred highly optimized commands provided by the package on top of the vast number of commands provided by Mathematica itself, which enable versatile high-level coding and cover many fields of mathematics, data science, visualization, machine learning, etc.

Fretica supports both the analysis of experiments on freely diffusing and immobilized molecules. For free-diffusion experiments, functions range from photon burst identification, corrections, and analysis in the spirit of multi-parameter fluorescence detection (MFD), to PIE/ALEX data analysis, PCH, FIDA, PDA, recurrence analysis, fluorescence lifetime fitting, FLIM, etc., global analysis schemes for equilibrium and time-resolved data (e.g. from microfluidic mixing experiments), and many correlation techniques, such as multi-channel FCS, Fluorescence Lifetime Correlation Spectroscopy (FLCS), dual-focus FCS, and nsFCS. For immobilized molecules, both photon-by-photon and binned trajectories can be analyzed using hidden Markov models (HMMs) with arbitrary numbers of states and detection channels. Model parameters can be found by maximum-likelihood optimization. For testing purposes, Fretica can simulate realistic photon data given any HMM with Poissonian or super-Poissonian photon statistics, both for immobilized and freely diffusing molecules, including mixtures of species with heterogeneous diffusion coefficients in open or confined volumes.

Fretica’s extensive documentation is integrated into the Mathematica documentation system. Notebooks (and raw data) can be easily shared or deposited on archives. All analysis steps from loading the raw data to the final results are well documented and can be re-executed any time. Fretica reads data in the PTU file format developed by PicoQuant, Berlin.

For installing Fretica, simply execute within Mathematica:
PacletInstall["https://schuler.bioc.uzh.ch/fretica/"]
(For uninstalling PacletUninstall["Fretica"].)

Fretica is started by executing: Needs["Fretica`"]
Type “Fretica” and press F1 to open the documentation.

Alternatively, Fretica can be downloaded and installed manually following the instructions in the ReadMe file.
Fretica is only available for Windows.

Fretica by Daniel Nettels and Ben Schuler is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License
