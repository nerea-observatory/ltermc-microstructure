# ltermc-microstructure

# Licence : 
These data are under Creative Commons : Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)
Data are available under netcdf files 
https://en.wikipedia.org/wiki/NetCDF
https://unidata.github.io/netcdf4-python/netCDF4/index.html


# For any use of these data, please cite the related research study paper and the dataset DOI 

article
Kokoszka, F. and Conversano, F. and Iudicone, F. and Ferron, B. and Bouruet-Aubertot, P. and Mc Millan, J. (2020)
Microstructure observations of the summer-to-winter destratification at a coastal site in the Gulf of Naples
submitted to Journal Of Geophysical Research : Oceans.

dataset
https://zenodo.org/record/4306862#.X8q9PLIReHo
Publication date:
December 4, 2020
DOI:
10.5281/zenodo.4306862
Related identifiers:
Supplement to
https://github.com/nerea-observatory/ltermc-microstructure/tree/v1.0.0


# Global Attributes:
           netcdf4_classic
           Project            = 'Long-Term Marechiara (LTER-MC)'
           Research Institute = 'Stazione Zoologica Anton Dohrn (SZN), Napoli, Italy'
           Location           = 'Gulf of Naples'
           Deployment         = 'Weekly vertical profiles at a coastal fixed point'
           Instruments        = 'CTD Seabird 911+, VMP-250 Rockland'
           Period             = '07/07/2015-23/02/2016'
           Sampling location  = '14.25E, 40.80N (fixed point)'
           Bathymetry         = '75m'
           Ship               = 'R/V Vettoria'
           Chief Scientist    = 'Daniele Iudicone'
           Program PIs        = 'Fabio Conversano, Florian Kokoszka, Daniele Iudicone'
           Contact            = '[fabio . conversano @ szn . it]  [florian . kokoszka @ szn . it]'
           Citation           = 'For any use of these data, please cite the related paper: Kokoszka, F. and Conversano, F. and Iudicone, F. and Ferron, B. and Bouruet-Aubertot, P. and Mc Millan, J. (2020), Microstructure observations of the summer-to-winter destratification at a coastal site in the Gulf of Naples, submitted to Journal Of Geophysical Research : Oceans.'
      
      
      
# Data overview:

#CTD DATA 
#Seabird911+ Conductivity-Temperature-Depth data profiles (1m vertical regular grid)
ltermc_gon_mc1160_mc1190_CTD.nc
(longitude, latitude, temperature, salinity, depth, pressure, casts, and time)

#VMP GENERAL 
#VMP250 RSI high-resolution microstructure profiles (512 Hz)
ltermc_gon_mc1160_mc1190_VMP_meta.nc
(longitude, latitude, casts, time, and estimates of epsilon (dissipation rates of turbulent kinetic energy, W/kg)

#VMP_data
#VMP250 RSI high-resolution microstructure profiles (512 Hz)
...
ltermc_gon_mc1160_mc1190_VMP_xxx.nc
...
(512 Hz data : microstructure shears, accelerometers, micro-conductivity and fast thermistor, pressure, turbidity, time, sampling rates, 

#JAC CT
#VMP250 RSI - JFE Advantech micro-Conductivity-Temperature profiles (64 Hz) + VMP-250 RSI profiler cinematics
ltermc_gon_mc1160_mc1190_JAC_CT.nc
(64 Hz data : JAC-conductivity, temperature, pressure, time, sampling rates, falling velocity, inclinometers)


           

