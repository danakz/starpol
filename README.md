# starpol
Contains starlight extinction polarization data of LMC foreground stars with updated distances using Gaia data

------------------------------------------------------------------------------------------------------------------------------------
Description
------------------------------------------------------------------------------------------------------------------------------------
This repository contains 2 files:

 - lmc_foreground_stars_s76_IAU_Gal_newdist.txt    --> this file contains the polarization data of foreground stars from the Schmidt (1976) catalogue with distance estimates from Gaia data when available --> polarization data taken from Table 6 of the paper, rotated to Galactic frame, coordinates in Galactic coordinate system  
 - lmc_foreground_stars_mf70_IAU_Gal_newdist.txt      --> this file contains the polarization data of foreground stars from the Mathewson & Ford (1970) catalogue with distance estimates from Gaia data when available --> polarization data rotated to Galactic frame, coordinates in Galactic coordinate system 

------------------------------------------------------------------------------------------------------------------------------------
Legend description
------------------------------------------------------------------------------------------------------------------------------------
#num: number
glon: galactic longitude
glat: galactic latitude
P(%): starlight polarization (V filter).
sP(%): starlight polarization error (V filter).
PA(deg): starlight polarization angle in equatorial system (V filter).
sPA(deg): starlight polarization angle error (V filter).
HD: HD number
dist(pc): distance in parsecs, updated using Gaia data if available (Gaia Collaboration et al. 2016, Gaia Collaboration et al. 2018, Bailer-Jones et al. 2018, Anders et al. 2019)
no: (only for Schmidt catalogue) name in the original article if HD number is missing

------------------------------------------------------------------------------------------------------------------------------------
