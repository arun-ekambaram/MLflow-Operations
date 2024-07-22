# MLflow-Operations

## For Dagshub

import dagshub
dagshub.init(repo_owner='arun-ekambaram', repo_name='MLflow-Operations', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)