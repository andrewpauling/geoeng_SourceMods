# geoeng_SourceMods
Source code modifications for the model runs in "Geoengineering by optimally flooding the Arctic sea ice with seawater reduces future sea ice thinning" by Andrew G. Pauling and Cecilia M. Bitz, submitted to Geophysical Research Letters in July 2019

The directory 'icepack" contains the modified source code for the Icepack experiments run for the paper. Get the Icepack model here: https://github.com/CICE-Consortium/Icepack
Files beginning with "icepack_" should be copied into the columnphysics directory. Files beginning with "icedrv_" should be pasted into the configuration/driver directory. The code currently introduces 20cm/yr total flooding in September and October only. Modify the floodice subroutine to change the flooding scenario.

The directory CCSM contains the modified source code for the CCSM4 experiments run for the paper. After creating a new case, the files should be copied into the SourceMods/src.cice directory before building. The code currently introduces 20cm/yr total flooding in September and October only. Modify the floodice subroutine to change the flooding scenario.


