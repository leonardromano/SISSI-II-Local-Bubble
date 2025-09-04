SISSI II. Star formation near the Sun is quenched by expansion of the Local Bubble
==================================================================================

All code is made publicly available. The code is made available in Jupyter Notebooks written in Julia for reproducing the analysis outlined in the accompanying paper. 

## Requirements

Julia is required.   
A manifest file is provided to ensure that the identical environment can be used.   
For Analysis of 3D-Dust-Maps, the dataset from Edenhofer et al. 2024 is required: https://doi.org/10.5281/zenodo.8187943
For Analysis of Stellar Clusters, the dataset from Swiggum et al. 2024 is required: https://doi.org/10.7910/DVN/VYBZQS

The 3D-model of the LB shell, derived from the mean 3D-dust map, can be obtained as a .csv file by initialising and updating the corresponding submodule:
	
    git submodule init
    git submodule update

## Installation

1. Clone the repository:

    git clone https://github.com/leonardromano/SISSI-II-Local-Bubble.git

2. Start the Jupyter Notebooks and recreate the environment by executing the first two lines of the notebook.

## Usage

Start the Jupyter Notebooks and execute all cells line by line.
Be aware that due to the large size of the datasets some operations might be quite computationally expensive and require generous ressource allocations (>200 GB RAM).
    
## Supporting and Citing

To give proper academic credit, follow the link to Zenodo: [https://doi.org/10.5281/zenodo.17054923](https://doi.org/10.5281/zenodo.17054923)

## License

The converter is distributed under the terms of the GPL license.
Please see `LICENSE.txt` for further details.
