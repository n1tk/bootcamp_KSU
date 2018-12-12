# Data Science Programming Bootcamp for Kennesaw State University. Python: Afternoon session Part#2

### Environment preparation: Anaconda "use".
With Anaconda use, path setup and conda ready.

Installation Documentation:
* https://conda.io/docs/user-guide/install/index.html#

* https://www.anaconda.com/download/#windows

###### macOS conda path setup: _https://stackoverflow.com/a/35375476/2027457_


#### Option1(used comandline manual setup):
##### Update the conda:
* _conda update -n base -c defaults conda_

##### Update or upgrade pip
* _conda install pip or conda update pip_ **or** _conda upgrade pip_

##### Create new environment
* _conda create -n bootcamp_DS python=3.6_

##### Activate new environemnt and install dependencies:
* _source activate bootcamp_DS_  **# On Windows, remove the word 'source'.**

##### Install the kernel for the jupyter notebook
* _conda install ipykernel # or pip install ipykernel_
* _python -m ipykernel install --user --name bootcamp_DS --display-name "Python36(bootcampDS)"_ #than once opening jupyter notebook, select Kernel/Change Kernel and select "Python36(bootcampDS)"

##### Install, Update or upgrade required packages:
* _conda install -c https://conda.anaconda.org/anaconda seaborn_ #seaborn is required the latest version.
or
* _pip install git+https://github.com/mwaskom/seaborn.git #https://seaborn.pydata.org/installing.html

* _conda install -y --name bootcamp_DS numpy scipy matplotlib pandas sympy scikit-learn statsmodels pandasql_ **# all Linear algebra we can do with the numpy library but installing all the dependencies from begining.**
* _conda update -y --name bootcamp_DS numpy scipy matplotlib pandas sympy scikit-learn statsmodels pandasql_ **# if you have already installed the libraries.**
* _conda upgrade -y --name bootcamp_DS numpy scipy matplotlib pandas sympy scikit-learn statsmodels pandasql_ **# if you have them already installed and want to upgrade to lates and greatest.**




#### Orange Installation (usually Anaconda has the Orange installed by default or is easy to install thru navigator) I'm using macOS for this part:
**Documentation:** _https://orange.biolab.si/download/_
* conda config --add channels conda-forge
* conda install -y --name bootcamp_DS orange3
* conda install -c defaults pyqt=5 qt

#### Pytorch GPU Linux install for me ###############

* conda install -y --name spinningup pytorch torchvision cuda100 -c pytorch



##### Documentation:
https://ipython.readthedocs.io/en/stable/install/kernel_install.html
