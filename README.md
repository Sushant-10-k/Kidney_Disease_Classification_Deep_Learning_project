# Kidney_Disease_Classification_MLflow_DVC
## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Sushant-10-k/Kidney_Disease_Classification_Deep_Learning_project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n krishna python=3.9 -y
```

```bash
conda activate krishna
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```
## MLflow

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Sushant-10-k/Kidney_Disease_Classification_Deep_Learning_project.mlflow \
MLFLOW_TRACKING_USERNAME=Sushant-10-k \
MLFLOW_TRACKING_PASSWORD=834f4d0154d10dc596a8ad186bd59f744b0b0224 \
python script.py

Run this to export as env variables:

```bash

set MLFLOW_TRACKING_URI=https://dagshub.com/Sushant-10-k/Kidney_Disease_Classification_Deep_Learning_project.mlflow

set MLFLOW_TRACKING_USERNAME=Sushant-10-k 

set MLFLOW_TRACKING_PASSWORD=834f4d0154d10dc596a8ad186bd59f744b0b0224

```
### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag

