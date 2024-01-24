# Quantitativ-Trading
This repository contains all projects belonging to part 1 of Udacity's "AI for Trading Nanodegree".

## Installation, Dependencies and Starting the Notebook
The code of these projects was tested on Linux (Ubuntu 20.04). To get the code running on your local system, follow these steps which are base on Anaconda, pip and git:

### Download Repository
1. Go to a folder where you want to clone the repository
2. `git clone https://github.com/rp-dippold/Quantitativ-Trading.git`

### Setting up the Python environment
The Python environment created by the following steps works for every project.

Enter the following commands in a bash terminal:
1. `cd Quantitative-Trading`
2. `conda create --name aitrading_p1 python=3.6.3 -c conda-forge`
3. `conda activate aitrading_p1`
4. `python -m pip install --upgrade pip` 
5. `python -m pip install --upgrade wheel setuptools build`
6. `python -m pip install -r requirements_p1.txt`
7. `python -m ipykernel install --user --name aitrading_p1 --display-name "ai-trading-p1"`

### Start a Jupyter Notebook
1. Navigate to a project's folder, e.g. by `cd p1_trading_with_momentum`
2. Start the notebook by entering `jupyter-notebook` into the bash terminal.
3. Copy one of the displayed URLs, e.g. 'http://127.0.0.1:8888/?token=78c...' in a browser tab.
4. Select the corresponding notebook, e.g. `project_1_starter.ipynb` in your browser.
5. Select the kernel "ai-trading" before running the cells.
