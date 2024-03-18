# Kidney-Disease-Classification

## Workflows

1.Update config.yaml

2.Update secrets.yaml [Optional]

3.Update params.yaml

4.Update the entity

5.Update the configuration manager in src config

6.Update the components

7.Update the pipeline

8.Update the main.py

9.Update the dvc.yaml

/## How to run?

STEPS:
### Clone the repository

https://github.com/feyisayoav/Kidney-Disease-Classification
#### STEP 01- Create a conda environment after opening the repository

conda create -n cnncls python=3.8 -y

conda activate cnncls
#### STEP 02- install the requirements

pip install -r requirements.txt
#### Finally run the following command

python app.py

Now,

open up you local host and port

DVC cmd

dvc init

dvc repro

dvc dag

data link: https://drive.google.com/file/d/1_y7Yhg9ozIO6OyKP8lZEeGGa3NEz1iut/view?usp=sharing

## MLFLOW
-mlflow ui


### Dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/feyisayoav/Kidney-Disease-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=feyisayoav \
MLFLOW_TRACKING_PASSWORD=************************
python script.py

Run this to export as env varaible

....bash

export MLFLOW_TRACKING_URL=https://dagshub.com/feyisayoav/Kidney-Disease-Classification
export MLFLOW_TRACKING_USERNAME=feyisayoav
export MLFLOW_TRACKING_PASSWORD=********************