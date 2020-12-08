# rr_gage_binder_jetting

### Installation Instruction
Download and Install [Anaconda python](https://www.anaconda.com/products/individual) 

#### Dependencies installation
1. Start Anaconda prompt 
  * You can find it by searching `Anaconda Prompt` in the windows search bar
  * Or you can start the Anaconda Navigator and go to Environments -> click green arrow -> select open in terminal

2. Install dependencies

* cd into the code directory run the command `conda env create -f ./dependencies.yml`. This will install all the libraries inside a virtual environment called `pymc3_dep`. This is so that if you have a python environment installed already, whatever I install won't affect it. 

#### Running Jupyter notebook
1. Activate the environment by running the command `conda activate pymc3_dep`. Alternatively, you can activate the environmment by selecting the environment name through the Anaconda Navigator. You must activate the environment before going to the next step or running anything that requires the library I previously installed. 


2. All the analytic are stored in `*.ipynb` files. It's in essence the same thing as R markdown. You can start jupyter notebook by selecting the environment and starting jupyter notebook through the anaconda navigator. Or through command line by running `jupyter notebook` in the directory after you activated the environment
