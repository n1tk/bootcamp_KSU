# Bootcamp in Data Science for Kennesaw State University

### Environment preparation: Anaconda "use".
#### Option1: 

* ipython kernel install --user --name=bootcamp_conda_ksu # when is already installed the ipykernel

#### Option2:


##### Create new environment 
* conda create -n bootcamp_ksu python=3.6

##### Than update the conda:
* conda update -n base -c defaults conda

##### Activate new environemnt and install dependencies: 
* source activate bootcamp_ksu  # On Windows, remove the word 'source'.
* conda install pip or conda update pip or conda upgrade pip
* conda install ipykerne  #or pip install ipykernel

##### Kernel for conda environments
* python -m ipykernel install --user --name bootcamp_conda_ksu --display-name "Python36 (bootcamp_conda_ksu)" # display name is for what we will see in the jupyter under the kernels. 

##### Documentation:
https://ipython.readthedocs.io/en/stable/install/kernel_install.html

