# MLflow-Operations

## For Dagshub

import dagshub
dagshub.init(repo_owner='arun-ekambaram', repo_name='MLflow-Operations', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


  MLFLOW_TRACKING_URI = https://dagshub.com/arun-ekambaram/MLflow-Operations.mlflow \

  MLFLOW_TRACKING_USERNAME = arun-ekambaram \

  MLFLOW_TRACKING_PASSWORD = 7b1a782894e4efccf58800da2b89c0ab4417f878 \
  python script.py

'''bash 

export MLFLOW_TRACKING_URI =https://dagshub.com/arun-ekambaram/MLflow-Operations.mlflow 
 
export MLFLOW_TRACKING_USERNAME =arun-ekambaram 

export MLFLOW_TRACKING_PASSWORD = 7b1a782894e4efccf58800da2b89c0ab4417f878 

'''
