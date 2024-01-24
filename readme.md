# UPV DPA example

## Setup evaluation environment

1. Clone this repo
2. Install python interpreter
3. Create python virtual environment
4. Download the traces dataset

### Downloading the traces dataset
Traces dataset is in a single file (TRS extension) you can download from [here](https://drive.google.com/file/d/1_N0S6lUC7ndGdgzkv1_9tVi0OznOmJVM/view?usp=sharing)

### Step 0: 
Check python version: Open a terminal, type: `python --version`. You should see the info regarding python interpreter

### Step 1: 
To create a virtual environment in python open a terminal and navigate to the directory where you will create your virtual env:

```bash
cd C:\Users\your_user\
mkdir upv_env
cd upv_env
python -m venv upv_dpa_ex
```

### Step 2:
Install the required python, but before, make sure you are in the virtual environtment you just created. In the same terminal you can type:

```bash
cd C:\Users\your_user
upv_dpa_ex\Scripts\activate # IMPORTANT: activate the virtual environtment first
```

packages to install:
- Install jupyterlab
- Install trsfile python package
- Install skitlearn
- Install numpy

You can also use the requirements.txt provide with this repo to install (virtually) automatically. Use the file to execute:

```bash
pip install -f requirements.txt
```

if not, then install the packages manually:

```bash
pip install jupyterlab
pip install trsfile
pip install numpy
pip install skitlearn
```

### Step 3:
After installing the requirements, JupyterLab should be ready to be used. But first, we have to be in the folder that contains the files of this repo, meaning the location where you clone this repo. Open a terminal and navigate to the location where you clone this repository:

```bash
cd C:\Users\your_user\..\UPV_DPA_Example # Find the location of the repo folder
jupyter lab # An browser should be open after this command
```