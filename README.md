# mlflows_tutoring


import dagshub
dagshub.init(repo_owner='fosetorico', repo_name='mlflows_tutoring', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)