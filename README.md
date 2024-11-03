# Emeowtions Machine Learning
## Introduction
This repository contains the codebase for the machine learning tasks of the final year project titled "Cat Body Language Recognition using Computer Vision in an Android Application".

## Setup
Run these commands in the terminal.
#### Create Virtual Environment
```
python -m venv venv
```
#### Activate Virtual Environment
```
venv\Scripts\activate
```
#### Install Python Dependencies
```
pip install -r requirements. txt
```
#### Update Python Dependencies
Used when new dependencies are added.
```
pip freeze > requirements.txt
```

## Project Structure
### Directory Structure
```
root
|   data
    |   external
    |   interim
    |   processed
    |   raw
|   models
    |   checkpoints
    |   emeowtions
    |   reports
    |   yolov8n_saved_model
|   notebooks
```
### Directory Description
| Directory | Description |
| - | - |
| root | Root folder |
| data | Dataset folders |
| data/external | External datasets |
| data/interim | Interim datasets for preprocessing checkpoints |
| data/processed | Processed datasets ready for model training |
| data/raw | Raw datasets that have not undergone preprocessing |
| models | Model files and folders |
| models/checkpoints | Exported models from training checkpoints |
| models/emeowtions | Finalized Emeowtions model folder with TFLite model and labels file |
| models/reports | Classification reports from Scikit-Learn |
| models/yolov8n_saved_model | Finalized YOLOv8n model folder with TFLite model and labels file |
| notebooks | Jupyter Notebook files used for data collection, EDA, data preprocessing, model training, evaluation, etc. |

## Technology Stack
<div style="display: flex; gap: 1rem;">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/640px-Python-logo-notext.svg.png" width="150" height="150" alt="Python" />

<img src="https://miro.medium.com/v2/resize:fit:1400/1*YQWYPi4uoT8RcG6BPbUoVw.png" width="300" height="150" alt="Ultralytics YOLOv8" />

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwOX_n_7qurFQxghhS8HOBMnEPQjlY1l9Jmw&s" width="300" height="150" alt="PyTorch" />

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Keras_logo.svg/1200px-Keras_logo.svg.png" width="150" height="150" alt="Keras" />

</div>