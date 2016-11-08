# recsys-course
This is the official repository for the 2016 Recommender Systems course at Polimi.

### READ CAREFULLY THE INSTALLATION PROCEUDURE
There have been some slight changes since the last version (mainly to avoid an excessive pollution of the main directory of the project).
We **strongly** advise you to clean your local version of the repository and to clone and install this new version
from scratch. Thank you!


## Install

###Requirements:
- C++ compiler, like **gcc4.8+** or **clang**
- On Linux, ensure that you have packages **libc6-dev** and **build-essentials** 
(run `apt-get install -y libc6-dev build-essentials` to install them)

###Installation instructions:
1. Install Miniconda for Python3.5 [link](http://conda.pydata.org/miniconda.html)
2. Create the virtual environment: `conda create -n recsys-env --file recpy/requirements.txt`
3. Activate the virtual environment: `source activate recsys-env`
4. Install recpy: `cd recpy; sh install.sh; cd ..`
5. Run one example: `sh run_top_pop.sh`

NOTE: to deactivate the virtual environment run: `source deactivate recsys-env`

# Packages
- `recpy`: main package
- `recpy/recommenders`: recommendation algorithms
- `recpy/utils`: dataset management and split utils
- `recpy/_cython`: Cython code



