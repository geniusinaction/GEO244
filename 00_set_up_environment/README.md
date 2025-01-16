# 00_set_up_environment
Some resources for setting up 

[GEO244.yml](GEO244.yml) : a YML file with the packages required to run the notebooks for the course. If you are conda-cognizant, then you will know that you can install all the packages and the whole environment using this command:

    conda env create -f InSAR.yml
    
...although if you are really conda aware, you'll know that a mamba runs a lot faster than a conda! You can save yourself a lot of time if you install using this:

    mamba env create -f InSAR.yml

[GEO244 environment setup in WSL2.pdf](GEO244%20environment%20setup%20in%20WSL2.pdf) : instructions for installing the conda environment on Windows PCs (and the instructions also work for Linux)
