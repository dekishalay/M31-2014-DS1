# Failed supernova identification and interpretation of M31-2014-DS1 and NGC 6946-BH1

Code and data to reproduce results on the disappearance of M31-2014-DS1 and its interpretation with NGC 6946-BH1 as a failed supernova. 

## Data
All the photometry of the object is provided in photometry.csv. The photometry include flux measurements and their errors in epochs where the source was detected; otherwise the flux error column is empty and the is_limit flag is set to 1. 

## Models
The MESA models for both M31-2014-DS1 and NGC 6946-BH1 are in the folder mesaruns/ 
The python notebook MESAfailedSN.ipynb uses the MESA model outputs to reproduce figures for the interpretation.
