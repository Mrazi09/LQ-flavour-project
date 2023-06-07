# Leptoquark-project---Data
Data for the Leptoquark research project, which corresponds to the paper: "On interplay between flavour anomalies and neutrino properties" by myself and collaborators (Felipe F. Freitas, António Morais, Werner Porod and Roman Pasechnik). arXiv:2206.01674 

---> Data: Data from first version

---> Data_v2: Data from second version. Corresponds to the data of the submitted version

---> Data_v3: Data from the third version. Corresponds to the data of the resubmitted version

---> Best_v2: Best fit points from the second version. Corresponds to the data of the submitted version

---> Best_v3: Best fit points from the third version. Corresponds to the data of the resubmitted version

---> Some companion jupyter notebooks for the inversion of the neutrino mass matrix such that the PMNS and neutrino mass differences are inputs (Neutrino_inversion.ipynb) as well as additional codes for how to determine the PMNS and neutrino masses from available data files (Read_neutrino_v2.ipynb and Read_neutrino_v3.ipynb)

---> ```flavio```, in its current version, does not calculate the CP angle $\phi_s$ due to new physics contributions in $B_s - \overline{B}_s$ mixing. However, all the ingredients are there and it is not difficult to add the observable. To this end, one must replace ```observables.py``` located in ```flavio/physics/mesonmixing``` with the one on this repo. The new functions are marked with the comment ```#Joao```   

**Important note** Data from the first versions (Data folder) and second version (Data_v2 and Best_v2) are outdated. Should only be used for testing purposes and may be removed from the repo in the near future. The current data is Data_v3 and Best_v3 !!
    

For additional information, feel free to contact me (jpedropino@ua.pt or johnppg5@gmail.com)
