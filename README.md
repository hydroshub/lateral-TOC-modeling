# Hydroclimate reshapes land carbon storage estimates through lateral organic carbon loss

## 1. Overview

This folder contains the key codes to generate the main figures in the preprint
Hydroclimate reshapes land carbon storage estimates through lateral organic carbon loss

Code for our proposed model will be made public after the paper is accepted

The folder is organized as follows:
```text
|----README.md                                                
|----environment.yml                            # the pypi dependencies
|----code_for_plotting.ipynb                    # the standalone script to plot the main figures
|----LICENSE                                    # Project license 
```



## 2. Quick Start

### 2.1. Download our provided data from Zenodo to the project directory (/path/to/lateral-TOC-modeling/):
**https://doi.org/10.5281/zenodo.18203739**


### 2.2. Install Miniconda

Download Miniconda for your operating system from:
https://docs.conda.io/en/latest/miniconda.html

Follow the installer instructions. Make sure to add Conda to your PATH if prompted.


### 2.3. Open a terminal / command prompt

Windows: Anaconda Prompt or Command Prompt
macOS / Linux: Terminal


### 2.4. Navigate to the project directory

> cd /path/to/lateral-TOC-modeling


### 2.5. Create the Conda environment

> conda env create -f environment.yml


### 2.6. Activate the environment

> conda activate lateral_TOC_modeling


### 2.7. Register the environment as a Jupyter kernel

> python -m ipykernel install --user --name=lateral_TOC_modeling --display-name "Python (lateral_TOC_modeling)"


### 2.8. Launch Jupyter Notebook

> jupyter notebook


### 2.9. Open the code_for_plotting.ipynb file and run



## 3. License

The project is licensed under the MIT License.
