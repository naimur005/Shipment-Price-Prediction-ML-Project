# Shipment-Price-Prediction-ML-Project
**Artwork Logistics Cost Estimation Model**
> A predictive modeling project aimed at estimating the total cost of shipping and installing sculptures. The project involves building a regression pipeline that handles mixed data types—engineering physical features (dimensions, weight, material) and operational logistics variables (express shipping, remote locations, transport type)—while dropping high-cardinality identifiers to minimize data leakage and maximize model generalizability.
## How to run
Before you run this project make sure you have MongoDB Atlas account and you have the shipping dataset into it.

Step 1. Cloning the repository.
```
git clone git clone https://github.com/naimur005/Shipment-Price-Prediction-ML-Project.git
```
Step 2. Create a conda environment.
```
conda create -n shipment python=3.11 -y
```
```
conda activate shipment
```
Step 3. Install the requirements
```
pip install -r requirements.txt
```
## Workflow
1. Constants
2. Config_entity
3. Artifacts_entity
4. Components
5. Pipeline
6. main.py