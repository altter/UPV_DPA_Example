# UPV DPA Example

## Phase 1: Setup testing environment

- 1.0. Install python interpreter
- 1.1. Create python virtual environment
- 1.2. Install jupyterlab
- 1.3. Install trsfile python package
- 1.5. Install skitlearn
- 1.6. Install numpy
- 1.7. Download the traces dataset

### Downloading the traces dataset
Traces dataset is in a single file (TRS extension) you can download from [here](https://drive.google.com/file/d/1_N0S6lUC7ndGdgzkv1_9tVi0OznOmJVM/view?usp=sharing)

### Note 0: 
Check python vervion: Open a terminal, type: `python --version`. You should see the info regarding python interpreter
### Note 1: 
To create a virtual environment in python open a terminal and navigate to the directory where you will create your virtual env:

```bash
cd C:\Users\your_user\
mkdir python_env
cd python_env
python -m venv upv_dpa
upv_dpa\Scripts\activate # (hit enter after this line)
```

### Note 2: 
To perform steps `1.2` to `1.5` (virtually) automatically, you can use the requirements.txt filed provide with this repo. Use the file to execute:


```bash
pip install -f requirements.txt
```

After installing the requirements, JupyterLab should be ready to be used. Open a terminal in the 