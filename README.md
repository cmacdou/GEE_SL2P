The SLP2 code contains the Google Earth implemtation of the SLP2 Matlab neural networks which use the google earth satallite image collections for reflectance inputs to apply slected canopy variable outputs. The global network solution requires the parsing of the Matlab networks through the 'TOee' folder 'shortcut' function which iterates over a list of your networks in an index table to export each to a seperate output and error network csv file. These files can then be downloaded as assets to your GEE environement and entered into the code. Otherwise, there is a global network provided as well as error network for both Sentinel 2 and Landsat data. Lastly, the domain list is also required from the Matlab code which is used for the quality layer. 
The Multiple Network code is an iteration of first GEE code which applies numerous shallow neural networks based off the input imdex layer for landclass.
The assets folder contains the assets used in the code however, these can be switched out for new assets with the same format. 
