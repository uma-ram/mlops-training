pip install mlflow jupyter pandas numpy scikit-learn xgboost hyperopt 
wget https://raw.githubusercontent.com/DataTalksClub/mlops-zoomcamp/refs/heads/main/02-experiment-tracking/duration-prediction.ipynb


jupyter notebook

mlflow server \
    --backend-store-uri sqlite:///mlflow.db