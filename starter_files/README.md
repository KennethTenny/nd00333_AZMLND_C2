*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Your Project Title Here

*TODO:* Write an overview to your project.

## Architectural Diagram
*TODO*: Provide an architectual diagram of the project and give an introduction of each step.

## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screencasts required to demonstrate key steps. 

*TODO* Remeber to provide screenshots of the `RunDetails` widget as well as a screenshot of the best model trained with it's parameters.


The bankmarketing dataset is present in the registered datasets:

![Registered Datasets](screenshots/1-registered-datasets.png)

An autoML experiment is completed. The column used for classification: 'y'

![AutomL Experiment](screenshots/2-experiment-completed.png)

The best model turns out to be VotingEnsemble after conducting the experiment:

![Best Model](screenshots/3-best-model-after-experiment-completed.png)

"Application Insights enabled" is disabled before running the logs.py.

!["Application Insights enabled" is disabled](screenshots/4-application-insights-enabled-before-running-logs-script.png)

We enalbed application insights (logging):

![app_insights](screenshots/insights_enabled.png)

Next we run logs.py and enable logging, then get the current logs:

![logs](screenshots/run_logs.png)

We then download swagger.json and examine the swagger docs in the swagger UI:

![swagger](screenshots/swagger_running.png)

We test that endpoint.py works and we can access the API:

![endpoint-py](screenshots/endpoint-py.png)

We create a pipeline:

![pipeline](screenshots/azure_pipeline_section.png)

with a pipeline endpoint that is active...

![pipe-end](screenshots/pipeline_endpoint.png)

with the bankmarketing dataset and automl module...

![data module](screenshots/data-module.png)

The pipeline overview shows the REST endpoint:

![published pipeline](screenshots/published_pipeline.png)

The RunDetails widget through the Python SDK shows the step runs:

![rundetails](screenshots/rundetails.png)

We can also schedule pipelines to run periodically with the SDK.  In ML studio, we can see the scheduled run:

![scheduled_run](screenshots/scheduled_run.png)



## Screen Recording
The screencast has been uploaded to YouTube: [Screencast](https://youtu.be/M8ON4RzZuWI)
