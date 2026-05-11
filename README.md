# pands-project

**This is the repository for my project for my Programming & Scripting module at [ATU](https://www.atu.ie/courses/higher-diploma-in-science-data-analytics). This work is presented in a Jupyter notebook and demonstrates basic data analysis, visualisation and modelling using Python.**

Here you will find:
1. Dataset Summary
2. Environment & Installation Instructions
3. Contents

## Dataset
This analysis uses the Fisher's Iris Dataset, accessed from the *'sklearn.datasets'* module using *'load_iris'* [1]. It can also be downloaded/imported from [UV Ivine's Machine Leanring Repository](https://archive.ics.uci.edu/dataset/53/iris) [2]

This dataset is from 1936, containing 50 samples from three iris flower species. It is widely used in the education of data analysis, visualisation and machine learning due to it's simple structure that is suitable for beginners - similar to 'Hello World' in programming. [3] https://www.kaggle.com/datasets/uciml/iris



## Repository Structure
- `analysis.ipynb`- Jupyter notebook containing all analysis and explanations
- `requirements.txt` - Dependencies required to run the notebook
- `.gitignore` - Files and folders excluded from version control
- `README.md` - Project overview and instructions (you are here)

## Running the Notebook (Installation)
```bash
git clone <https://github.com/leahchristina/pands-project.git>
cd pands-project
pip install -r requirements.txt
```

## Environment
I recommend using Visual Studio Code and Anaconda to run the notebook. 

## Contents
- Step 1: Importing the dataset & packages
- Step 2: Loading the Dataset & Viewing the Structure
- Step 3: Summary of each Variable
- Step 4: Histograms
- Step 5: Scatter Plots
- Step 6: Other Analysis (Box Plots)
- Step 7: Conclusion of Analysis

## References
[1] https://www.geeksforgeeks.org/machine-learning/iris-dataset/
[2] Fisher, R. (1936). Iris [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C56C76.
[3] https://www.kaggle.com/datasets/uciml/iris