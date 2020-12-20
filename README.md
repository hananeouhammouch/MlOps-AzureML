# Operationalizing Machine Learning in Azure

## Summary of the project

**This project is part of the Udacity Azure ML Nanodegree.**

The main object of this project is to predict if a client will subscribe to a term deposit product related to direct marketing campaigns of a Portuguese banking institution by creating a model and deploying it into production using Azure ML

Dataset: https://www.kaggle.com/henriqueyamahata/bank-marketing 

Where we apply MLOps principle by starting  with the authenticating to Azure Machine Learning services, then the creation of an Automated ML experiment , the deployment of the best model, after that we enable the loging to review important log information, then we consum the model endpoint and finelly we create and publish the pipeline to automate all this previous step.

![projectdiagrame](Main-step-project.png "projectdiagrame")

## Architectural Diagram
The architectual diagram of the project with the main step of each critical phase to the overall flow is described bellow:

![architector](architector.png "architector")


## Key Steps
The Key steps of the project are demonstrated bellow (screenshots included)

**Step 1:Authentication** : Skiped because i used the provided Udacity Lab 

**Step 2:Automated ML Experiment**

Where we start first by the registration of the dataset into Azure ML Studio:

![Bank-Marketing-Dataset](Bank-Marketing-Dataset.png "Bank Marketing Dataset")

we next create the compute cluster using Standard_DS3_V2 as the virtual Machine Size

![Compute-cluster](Compute-cluster.png "Compute-cluster")

we then configure and run the Automated ML Classification Experiment

![Experiment-completed](Experiment-completed.png "Experiment-completed")

we then configure and run the Automated ML Classification Experiment

![Experiment-completed](Experiment-completed.png "Experiment-completed")

To finally retrieve the Best Model after the expirement completed 

![Best-Model](Best-Model.png "Best-Model")




## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
