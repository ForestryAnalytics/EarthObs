Enhanced vegetation index
From Wikipedia, the free encyclopedia


Jump to navigation
Jump to search
 

2011 Enhanced vegetation index based on MODIS Terra data
The enhanced vegetation index (EVI) is an 'optimized' vegetation index designed to enhance the vegetation signal with improved sensitivity in high biomass regions and improved vegetation monitoring through a de-coupling of the canopy background signal and a reduction in atmosphere influences. EVI is computed following this equation: 
E V I = G × ( N I R − R E D ) ( N I R + C 1 × R E D − C 2 × B l u e + L ) {\displaystyle EVI=G\times {\frac {(NIR-RED)}{(NIR+C1\times RED-C2\times Blue+L)}}} 
 
where NIR/red/blue are atmospherically-corrected or partially atmosphere corrected (Rayleigh and ozone absorption) surface reflectances, L is the canopy background adjustment that addresses non-linear, differential NIR and red radiant transfer through a canopy, and C1, C2 are the coefficients of the aerosol resistance term, which uses the blue band to correct for aerosol influences in the red band. The coefficients adopted in the MODIS-EVI algorithm are; L=1, C1 = 6, C2 = 7.5, and G (gain factor) = 2.5. 
Whereas the Normalized Difference Vegetation Index (NDVI) is chlorophyll sensitive, the EVI is more responsive to canopy structural variations, including leaf area index (LAI), canopy type, plant physiognomy, and canopy architecture. The two vegetation indices complement each other in global vegetation studies and improve upon the detection of vegetation changes and extraction of canopy biophysical parameters. .[1] 
Another difference between Normalized Difference Vegetation Index (NDVI) and EVI is that in the presence of snow, NDVI decreases, while EVI increases (Huete, 2002). 
Starting 2000, and after the launch of the two MODIS sensors on Terra (satellite) and Aqua (satellite) by NASA, EVI was adopted as a standard product by NASA and became extremely popular with users due to its ability to eliminate background and atmosphere noises, as well as its non saturation, a typical NDVI problem.[2] EVI is currently distributed for free by the USGS LP DAAC.[3] 
