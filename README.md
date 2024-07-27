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

# How to run?
### STEPS:
 
Clone the repository

```bash
https://github.com/feyisayoav/Kidney-Disease-Classification
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```
```bash
conda activate cnncls
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```
```bash
### Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag

```bash
data link: https://drive.google.com/file/d/***************************
```
## MLFLOW



### Dagshub
```bash
[dagshub](https://dagshub.com/)
```
#### MLFlow Tracking
```bash
MLFLOW_TRACKING_URI=https://dagshub.com/feyisayoav/Kidney-Disease-Classification.mlflow \
```

### Run this to export as env varaible


#### export 
```bash
MLFLOW_TRACKING_URL=https://dagshub.com/feyisayoav/Kidney-Disease-Classification
```
