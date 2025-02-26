WG4GEE
=
WG4GEE is a wheat growth simulation model, which is constructed based on the GEE(Google Earth Enigne) computing API, and runs based on the Google Colab environment without the need of local arithmetic support.WG4GEE is able to simulate the growth of winter wheat in China's winter wheat region of  based on GEE directly, and finally outputs the raster type of winter wheat single yield.

Usage
=
WG4GEE.ipynb contains the complete code needed to run WG4GEE. With the exception of the management measures and breed parameters, the data required for model runs are publicly available datasets mounted by GEE. Therefore, only the storage path and simulation year of the simulation results need to be modified before the simulation can be run.

Specifically, complete the following specific steps to begin the simulation:   
(1) Open WG4GEE.ipynb in Google Colab  
(2) Find the code in the 'Before simulation' module  
`username = 'yourself'`  
change 'yourself' to your own GEE username  
(3) Find the code in the 'Before simulation' module  
`sowingYEAR = 2014`  
change 2014 to the year you want to  start simulation

Then, you can run the entire model

The simulation results will be exported to your GEE asset list every 20 days, see the ‘Export data to GEE asset list’ module for specific file naming, and the default naming is ‘'WG_’ + str(N)+ str(sowingYEAR)'. It takes about 7 hours to complete the simulation for the whole region at 1km spatial resolution.

Examples
=
You can find out how to view the simulation results of the model at the following link. In addition, the simulation data and cultivar parameter data used for the model are also open source and can also be viewed at that link.
https://code.earthengine.google.com/6324ec3dcc2002202b1e5eb4caf91346
