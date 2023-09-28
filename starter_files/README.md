*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Your Project Title Here

*TODO:* Write an overview to your project.
In this project we will perform a complete overview of the MLOps capabilities of AzureML tool, ranging from creating an AutoML experiment, publishing the best performing model through an endpoint, create a REST API documentation so as to know how to interact with the API, interact with the API, and finally encompass all this process in a pipeline that we can publish too.

## Architectural Diagram
*TODO*: Provide an architectual diagram of the project and give an introduction of each step.
In the next diagram, it is summarized the steps followed throughoyt this project.

![Architectural-Diagram](./screenshots/Udacity_project2_architecture.png)

The project could be divided in two differentiable parts:

 - The first one consisted of make use of the portal to register the data, create an AutoML experiment, publish the best model as an endpoint and consume it.
 - The second part, we make use of Python SDK to define a pipeline that consisted of two steps (read the data and execute AutoML model). Then we publish and consume this pipeline using Python SDK too.



## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screencasts required to demonstrate key steps. 

### Step 1: Authentication

### Step 2: AutoML Experiment

#### Screenshot 2.1: Registered dataset
We registered the input data as `project_data`, since the original name was too long, and in this project we only use this that for the whole process and there won't be problems of missundestanding.

![Dataset_v1](./screenshots/Registered_dataset_v1.PNG)

If we explore the content of the registered dataset we can see that the data is the same as the [Bankmarketing dataset](!https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv)

![Dataset_v2](./screenshots/Registered_dataset_v2.PNG)

#### Screenshot 2.2: Create AutoML Experiment

![AutoML_config](./screenshots/AutoML_config.PNG)

#### Screenshot 2.3: AutoML Job Completed

![AutoML_config](./screenshots/AutoML_run_Succesful.PNG)

#### Screenshot 2.4: Best Model

![Best_model_ranking](./screenshots/Best_model.PNG)

![Best_model_details](./screenshots/Best_model_details.PNG)

### Step 3: Best Model Deployment

#### Screenshot 3: Best Model Endpoint

![Best_model_endpoint](./screenshots/Best_model_endpoint.PNG)

### Step 4: Enable Logging

#### Screenshot 4.1: AppInsights logs

![AppInsights](./screenshots/AppInsights_ON.PNG)

![AppInsights_logs](./screenshots/AppInsights_logs.PNG)

### Step 5: Swagger Documentation

#### Screenshot 5.1: Swagger

![Swagger](./screenshots/Swagger_run1.PNG)

![Swagger_Example](./screenshots/Swagger_example_run.PNG)

### Step 6: Consume Model Enpoints

#### Screenshot 6.1: Swagger

![Endpoint](./screenshots/Endpoint_output_step6.PNG)

#### Screenshot 6.2: Benchmark [Optional] 

![Benchmark](./screenshots/Benchmark_v1.PNG) 

![Benchmark_tail](./screenshots/Benchmark_v2_tail.PNG) 

### Step 7: Create, Publish and Consume Pipeline




*TODO* Remeber to provide screenshots of the `RunDetails` widget as well as a screenshot of the best model trained with it's parameters.

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

[Youtube_video](https://youtu.be/xIrkuYJ_aoI)

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
