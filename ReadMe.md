# Predicting Stock Price using Machine Learning
This repo contains series of notebooks, which are my submissions to a online Hack-a-thon : **Code-2-ML** hosted by [**CodeChef Chapter VIT AP**](https://codechefvitapchapter.tech) and [**ML Club VIT AP**](https://www.instagram.com/mlcvitap/).

## Problem Overview
Initially I was given two datasets namely `Train_dataset_ - Train_Aug10.csv` and `Test_dataset - Put-Call_TS.csv`.
##### `Train_dataset_ - Train_Aug10.csv`
This dataset contains various stock's fractors (features) and the respective stock price. The Problem is to make an Machine Learning Regression Model that first learns on the training dataset and then predicts the value for the test dataset. The predicted .csv file is saved as `file_01.csv`

> **Algorithm used :** Random Forest Regressor
##### `Test_dataset - Put-Call_TS.csv`
This dataset contains a single stock's PutCall Ratio parameter, but on 5 different consecutive days. The Problem is to make an efficient Machine Learning Time Series Model that first learns on the training dataset and then predicts the value on test dataset. The predicted .csv file is saved as `file_02.csv`

> **Algorithm used :** VAR : Vector Auto Regressor

<br>
  

## How to use the Notebooks in this repository

#### 1. Install the requirements.txt

```bash
pip install -r requirements.txt #Preferable to install on a Virtual ENV
```

> **If OSx / Linux use pip3 instead of pip**

#### 2. Running the Notebooks

##### Problem 01 :

There are 2 Notebooks  `problem_01.ipynb`   and  `test_dataprep.ipynb`.

`problem_01.ipynb` is the actual problem notebook

`test_dataprep.ipynb` is to clean the test Dataset. Which is then exported to be used by the main Notebook.

This all could have avoided and made into a single Notebook but it was clumsy. So for better readability we had to make two Notebook.

##### Problem 02 :

Run the `problem_02.ipynb` and the solution will be outputted.

#### 3. Answer Folder

After the execution of both the notebooks the .csv file solutions wil be exported.

These .csv files (solutions) are present into the Answer_files.

## Update

This Project has secured **1st Place 🥇** in the Code-2-ML Hack-a-thon.

> This [repo](https://github.com/Avhijit-codeboy/Code-2-ML-stage-3) contains other participant's submissions for the Hack-a-thon.


<img src="data/1615360662934.jpeg" alt="drawing" width="50%"/>

