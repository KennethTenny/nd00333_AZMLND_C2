# Operationalizing Machine Learning

With a help of a Bank marketing dataset, a ML model is created to predict if customers will avail term deposit, based on oyher parameters available for customers.  
Here is a brief overview of what is estabilished:
1. A model is trained using AutoML
2. the model is deployed as a REST endpoint.
3. The pipeline is created for the same.

## Improvements

Use of neural networks and training of the model with more compute and more training time can be of help in achieving a better accuracy.

## Architectural Diagram


![Architectural Diagram representation](screenshots/architectural_diagram.png)


## Key Steps

The bankmarketing dataset is present in the registered datasets:

![Registered Datasets](screenshots/1-registered-datasets.png)

An autoML experiment is completed. The column used for classification: `y`

![AutomL Experiment](screenshots/2-experiment-completed.png)

The best model turns out to be `VotingEnsemble` after conducting the experiment:

![Best Model](screenshots/3-best-model-after-experiment-completed.png)

"Application Insights enabled" is disabled before executing `logs.py`.

!["Application Insights enabled" is disabled](screenshots/4-application-insights-enabled-before-running-logs-script.png)

Executing `logs.py`: which is responsible for enabling "Application Insights enabled".

![Execution of logs.py](screenshots/5-executing-logs-script.png)

"Application Insights enabled" is disabled before executing `logs.py`.

![Before executing `logs.py`](screenshots/6-executing-logs-script-second.png)

Application Insights enabled" is enabled before executing `logs.py`.

![After executing `logs.py`](screenshots/7-application-insights-enabled-after-running-logs-scriptpng)

Then, the Swagger UI hosted on port 9000 of `localhost` with the Docker container: 

![Swagger UI](screenshots/8-swagger-ui-running-on-local-host.png)

Representation of methods in Swagger UI are represented here:

![HTTP-API methods in Swagger UI](screenshots/9-swagger-ui-http-api-methods.png)

Executing `endpoint.py` to fetch the desired JSON response, which translates to consumption of endpoints here:

![Executing `endpoint.py`](screenshots/10-executing-enpoint-script.png)

(OPTIONAL) Executing `benchmark.sh`, which shows if the endpoint adheres a certain benchmark:

![Executing `benchmark.sh`: Log 1](screenshots/11-executing-benchmark-script.png)

![Executing `benchmark.sh`: Log 2](screenshots/12-executing-benchmark-script-second.png)

The pipeline is created using the scripts in Notebook and here is representation of a completed pipeline:

![Completed Pipeline](screenshots/13-pipeline-created-and-completed.png)

Here are the pipeline endpoints:

![Pipeline Endpoints](screenshots/14-pipeline-endpoints.png)

Representation of the Bankmarketing dataset with AutoML module:

![Bankmarketing dataset with AutoML module](screenshots/15-bank-marketing-dataset-automl-module.png)

The published pipeline overview shows that the pipeline is finished(which further corresponds to an ACTIVE status):

![Published Pipeline Overview](screenshots/16-published-pipeline-overview-finished.png)

The execution of `RunDetails` widget in Notebook, along with Python SDK:

![rundetails](screenshots/17-Run-Details-Widget.png)

Representation of the scheduled run of Pipeline in ML studio:

![Scheduled Run](screenshots/18-ml-studio-scheduled-run.png)



## Screen Recording
The screencast has been uploaded to YouTube: [Screencast](https://youtu.be/M8ON4RzZuWI)
