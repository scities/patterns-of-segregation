# Socio Spatial Stratification in cities

Python scripts and data necessary to reproduce the results from the paper "Socio-spatial stratification in cities"

[citation here]

**Important note:** If you want to apply the methodoly used in the paper rather than simply reproduce the results, have a look at marble, a python library to analyse residential segregation.

## Dependencies

You will need to have GNU Make and curl installed on your machine (this should be the case if your machine on linux. Otherwise google is your best friend).
This was tested on Arch Linux and Python 2.7.9. Feel free to start an issue if you cannot run the code.

To install the python libraries necessary to run the code, go to the cloned folder and type in command line

> pip install -r dependencies.txt

## Use

Clone the repository, go into the corresponding folder and type 'make' in the console. The programme will prepare the data, perform the analysis and plot the figures in the folder 'figures'.
This has only been tested in Arch Linux, it should work for Mac Users as well. I have no idea for Windows users.

## Authors and License

Author: Rémi Louf <remi.louf@cea.fr>  
License: MIT
