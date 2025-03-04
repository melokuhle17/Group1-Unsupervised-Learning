# Anime Recommendation System

## Table of Content
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. MLFlow](#mlflow)
* [6. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

This project is an Anime Recommendation System that provides personalized anime suggestions based on user preferences. It integrates content-based filtering and collaborative filtering to enhance recommendations. The system uses Streamlit for the user interface and MLflow for model tracking.

## 2. Dataset <a class="anchor" id="dataset"></a>

The dataset is comprised of Anime dataset split into anime.csv, train.csv, test.csv and submission.csv.
 * [Anime.csv contains anime content information including id, name, genre, type, number of episodes (if applicable), an average rating based on views, and the number of members in the anime 'group'.] 
 * [Train.csv contains rating data, supplied by individual users for individual anime titles. It contains user_id information, the anime_id of the title watched.] 
 * [Test.csv contains a user_id and an anime_id column only and will be used for submission.] 
 * [submission.csv  shows the submission format for the final predictions.]
 You can find the `anime.csv`, `train.csv` and `test.csv` datasets [here](https://www.kaggle.com/t/dec21d5abc8c4d33bae9a25fbc3cfb7b).

## 3. Packages <a class="anchor" id="packages"></a>


## 4. Environment <a class="anchor" id="environment"></a>

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```

## 5. MLFlow <a class="anchor" id="mlflow"></a>

MLOps, which stands for Machine Learning Operations, is a practice focused on managing and streamlining the lifecycle of machine learning models. The modern MLOps tool, MLflow is designed to facilitate collaboration on data projects, enabling teams to track experiments, manage models, and streamline deployment processes. For experimentation, testing, and reproducibility of the machine learning models in this project, you will use MLflow. MLflow will help track hyperparameter tuning by logging and comparing different model configurations. This allows you to easily identify and select the best-performing model based on the logged metrics.

- Please have a look here and follow the instructions: https://www.mlflow.org/docs/2.7.1/quickstart.html#quickstart

## 6. Team Members <a class="anchor" id="team-members"></a>

| Name                                                                      | Email           
|---------------------------------------------------------------------------|--------------------
|1. Melokuhle Makhwasa                                                      |
|2. Kwanda                                                                  |
|3. Vuyiswa Ntshangase                                                      |
|4. Bonakele Mdletshe                                                       | Bonasiwe@gmail.com    

