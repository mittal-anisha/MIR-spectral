# MIR spectral
Analysis of MIR spectral data extracted from milk samples

## About data
The initial columns in the dataset contain details (i.e. covariates) of the cows which produced the milk samples and the protein and technological traits measured on the milk samples. 
The data in the nal 531 columns are the MIR spectra, with the the first row of these columns detailing the wavenumber (measured in cm^-1). 
The spectral values in the dataset are the absorbance values (the log10 of the reciprocal of the transmittance value). 

## Objective
1. Perform some data visualization and exploration (e.g. outlier removal) for the protein traits and the technological traits. 
2. Are there clusters of similar MIR spectra? If so, do the clusters relate to any of the categorical covariates?
3. Using its MIR spectrum, can you classify a milk sample as having heat stability of less than 10 minutes?
