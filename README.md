# data-test
repository for datasets used for testing the functions used in the various phenological packages


## nmr-ivdr


## nmr-spectra

- NMR_1D_rat_urine_spectra

rat urine 1D spectra data with no eretic factor correction

calibration to alanine, baseline correction and pqn were applied

selected ppm ranges from 2.0 to 3.99 only

Y which corresponds to the 2 groups of the spectra data set "L" and "N"

you can use this for PCA and OPLS-DA study


-  NMR_1D_Paracetamol_urine_spectra_raw.rda

total of 20 spectra collected from 5 individuals at 4 time points (baseline, 2,4,6 hours post-paracetamol)

Eretic factor correction has been applied

ppm ranges from -0.1 to 10 with total 44079 data points


-  NMR_1D_Paracetamol_urine_spectra_pqn.rda

using the NMR_1D_Paracetamol_urine_spectra_raw data

calibration to alanine doublet is applied

ppm < 0.5, 4.6 < ppm < 5.0, 9.5 < ppm were removed

baseline correction and PQN applied

total ppm data points are 37531 
