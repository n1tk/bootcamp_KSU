# Data Science Programming Bootcamp for Kennesaw State University. Python: Afternoon session Part#2

### Environment preparation: Anaconda "use".
With Anaconda use, path setup and conda ready. 
Installation Documentation: 

* https://conda.io/docs/user-guide/install/index.html#

* https://www.anaconda.com/download/#windows

###### macOS conda path: _https://stackoverflow.com/a/35375476/2027457_


#### Option1: 

* _ipython kernel install --user --name=bootcamp_conda_ksu # when is already installed the ipykernel_

#### Option2:


##### Create new environment 
* _conda create -n bootcamp_ksu python=3.6_

##### Than update the conda:
* _conda update -n base -c defaults conda_

##### Activate new environemnt and install dependencies: 
* _source activate bootcamp_ksu_  **# On Windows, remove the word 'source'.**
* _conda install pip or conda update pip_ **or** _conda upgrade pip_
* _conda install ipykerne_ #or _pip install ipykernel_
* _conda install -y --name bootcamp_ksu numpy scipy matplotlib pandas sympy seaborn scikit-learn_ **# all Linear algebra we can do with the numpy library but installing all the dependencies from begining.**
* _conda update -y --name bootcamp_ksu numpy scipy matplotlib pandas sympy seaborn scikit-learn_ **# if you have already installed the libraries.**
* _conda upgrade -y --name bootcamp_ksu numpy scipy matplotlib pandas sympy seaborn scikit-learn_ **# if you have them already installed and want to upgrade to lates and greatest.**

#### Orange Installation (usually Anaconda has the Orange installed by default or is easy to install thru navigator)_ I'm using macOS for this part: 
**Documentation:** _https://orange.biolab.si/download/_
* conda config --add channels conda-forge
* conda install -y --name bootcamp_ksu orange3
* conda install -c defaults pyqt=5 qt

##### Kernel for conda environments
* _python -m ipykernel install --user --name bootcamp_conda_ksu --display-name "Python36 (bootcamp_conda_ksu)"_ **# display name is for what we will see in the jupyter under the kernels.**

##### Documentation:
https://ipython.readthedocs.io/en/stable/install/kernel_install.html

