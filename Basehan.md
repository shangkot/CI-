*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Operationalizing Machine Learning  

In this project we used azure machine learning studio to perform all the tasks. Firstly we selected the bankmarketing dataset and created a autoML module. After that, we ran it and find out the best model and deploy it. We enabled application insight and logging for this and consumed the model endpoint. Finally we created a pipeline and consumed the pipeline. 

## Architectural Diagram
*TODO*: Provide an architectual diagram of the project and give an introduction of each step.

<img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/architectural%20diagram.PNG"
     alt="Diagram"
     style="float: left; margin-right: 10px;" />

## Key Steps
- Authorization  
I used the provided Lab and skipped this step.

- Automated ML Experiment  
Firstly, I have created a new AutoML and then uploaded the dataset. 
<img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/registered%20dataset.PNG"
     alt="dataset"
     style="float: left; margin-right: 10px;" />
     
- Deploy the Best Model  
After uploading the data successufully I ran the experiment and found the best model suited for that particular dataset. Then, I deployed the best model.
<img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/model%20deployed.PNG"
     alt="model deployed"
     style="float: left; margin-right: 10px;" />
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/best%20model.PNG"
     alt="best model"
     style="float: left; margin-right: 10px;" />
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/experiment%20completed.PNG"
     alt="completed"
     style="float: left; margin-right: 10px;" />
     
     
- Enable Application Insights  
After deploying the best model I enabled the Application Insight to understand and collect the logs.

<img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/application%20insight%20enabled.PNG"
     alt="app insight"
     style="float: left; margin-right: 10px;" />
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/log%20enabled.PNG"
     alt="app log"
     style="float: left; margin-right: 10px;" />
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/log%20details.PNG"
     alt="logr"
     style="float: left; margin-right: 10px;" />
     
- Swagger Documentation  
Then I opened swagger and checked if it is working properly or not.

<img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/swagger%20api.PNG"
     alt="swagger"
     style="float: left; margin-right: 10px;" />
     
- Consume Model Endpoints  
After that we consumed model endpoint by running a script

<img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/endpoint%20json.PNG"
     alt="consume endpoint"
     style="float: left; margin-right: 10px;" />
     
- Create, Publish and Consume a Pipeline  
Finally I created a pipeline and published it and consumed it. 

<img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/pipeline.PNG"
     alt="pipeline"
     style="float: left; margin-right: 10px;" />
     
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/active%20pipeline%20endpoint.PNG"
     alt="completed"
     style="float: left; margin-right: 10px;" />
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/published%20pipeline%20overview%201.PNG"
     alt="BMD automl"
     style="float: left; margin-right: 10px;" />
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/ML%20Studio%20Run.PNG"
     alt="completedd"
     style="float: left; margin-right: 10px;" />
     
 <img src="https://github.com/Gil-Joa/nd00333_AZMLND_C2/blob/master/starter_files/ml%20studio%20completed.PNG"
     alt="completedd"
     style="float: left; margin-right: 10px;" />

## Screen Recording
https://youtu.be/DOZ6nEW_wuk

## Standout Suggestions
In future we can include data validation to make the process more robust and accurate.
