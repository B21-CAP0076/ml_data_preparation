# Habitech Machine Learning Repository: Data Preparation Repository for Match Making Feature

## What is this repository about?
This repository contains Jupyter notebook for data preparation. Data that has been prepared will be used for clustering in match making feature as initial data. 

*   Dataset for  User Preference: https://www.kaggle.com/ruchi798/bookcrossing-dataset
*   Dataset for Book Database: https://www.kaggle.com/lukaanicin/book-covers-dataset

## Who are we?
```
Setiaki - A0101049@bangkit.academy
Hira - A0101023@bangkit.academy
Navi - M0101012@bangkit.academy
Alka - M0101050@bangkit.academy
Greg - C0101013@bangkit.academy
```

## How to run it?
There are two ways to run this notebook. By using **Google Colab** or run it on **Local**.

### Google Colab (Recommended)
1. Open Google Colab in research.google.com/colaboratory/
2. Access Github Tab
3. Search B21-CAP0076
4. Choose B21-CAP0076/ml_data_preparation as repository and master as branch to create new notebook
5. Download data files in this repository (Preprocessed_data.zip and main_dataset.csv.zip)
6. Upload those two data files to the Colab environment by accessing Files Menu on the left navigation bar
7. Click Run All in Runtime Tab
8. Now, you can wait for the notebook to finish its jobs! Happy Hacking!

### Local
1. Install Anaconda in your Local (docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
2. Open Anaconda Navigator application
3. Run CMD.exe Prompt from Anaconda Navigator
4. Create and activate environment by running this script in CMD.exe Prompt (without "-")
```
- conda create -n habitech-data-prep python=3.7
- conda activate habitech-data-prep
```
5. Download required files from this repository and put in the same folder
```
- Data_Preprocessing_for_Initial_Cluster_Dataset.ipynb
- Preprocessed_data.zip
- main_dataset.csv.zip
- requirements.txt
```
6. Move your CMD.exe Prompt directory to the directory where those four files existed
7. Install requirements by running this script in CMD.exe Prompt (without "-")
```
- pip install -r requirements.txt
```
8. Install and run Jupyter Notebook by running this script in CMD.exe Prompt (without "-")
```
- conda install jupyter
- jupyter notebook  
```
9. Open Data_Preprocessing_for_Initial_Cluster_Dataset.ipynb
10. Now, you can run this notebook through Jupyter Notebook! Happy Hacking!
