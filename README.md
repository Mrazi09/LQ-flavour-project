#  LQ-flavour-project
Auxiliar codes and data for the Leptoquark research project, which corresponds to the paper: "On interplay between flavour anomalies and neutrino properties" by myself and collaborators (Felipe F. Freitas, António Morais, Werner Porod and Roman Pasechnik). arXiv:2206.01674 

**Data** Dataset used in this work. Contains various ```.csv``` files which contain information on masses of particles, couplings and relevant observables. To manipulate the data inside a ```python``` environment, an auxiliar ```jupyter``` notebook ```Read_neutrino.ipynb``` is provided in the **Auxiliar_codes** folder.

**Best_Data** ```.csv``` files corresponding to the best-fit points described in the paper. Scenario a) corresponds to the folder All_SM, scenario b) corresponds to the folder SM_plus_NP and scenario c) corresponds to folder All_NP

**Auxiliar_codes** Additional auxiliar ```jupyter``` notebooks written in ```python```. Contains ```Read_neutrino.ipynb``` which allows to properly read the ```.csv``` files and then use them for numerical manipulations. In ```Neutrino_inversion.ipynb```, a numerical implementation of the inversion procedure in the neutrino sector is provided, such that the PMNS and neutrino mass differences are given as inputs. The codes require ```scipy```, ```numpy``` and ```pandas```. Contains addtional functions needed to be added into ```flavio```. In its current version, the CP angle $\phi_s$ due to new physics contributions in $B_s - \overline{B}_s$ mixing is not calculated. However, all the ingredients are there and it is not difficult to add this observable. To this end, one must replace ```observables.py``` located in ```flavio/physics/mesonmixing``` with the one on this repo. The new functions are marked with the comment ```#Joao```. Can then be calculated as ```flavio.np_prediction("phi_s", wc_obj)```.     

To download this repo, click on ```<> Code``` on top of the page and select ```Download ZIP```. One can also use git to clone the repo to your local machine as ```git clone https://github.com/Mrazi09/LQ_flavour-project.git``` in the terminal. The later option requires ```git``` to be installed in your system. Alternatively, to download a single folder, one can use ```DownGit```. For details, see https://github.com/MinhasKamal/DownGit/



For additional information or questions, feel free to contact me by email (jpedropino@ua.pt, joao.goncalves@hep.lu.se or johnppg5@gmail.com)
