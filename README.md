# azure-ml-notebook-diabetes-training
In this tutorial, you will create an experiment that connects to Azure Machine Learning workspace; train a simple scikit-learn model based on the diabetes data set, register a model; deploy the model to a container instance; and test the trained model. After completing this tutorial, you will have the practical knowledge of the SDK to scale up to developing more-complex experiments and workflows. 

In this tutorial, you learn the following tasks:

* Connect your workspace and create an experiment 
* Load data and train a scikit-learn model
* View training results in the portal
* Retrieve the best model
* Register the model to your workspace
* Create the scoring script for your web service
* Create environment file for a Docker image
* Deploy the model to ACI
* Test the deployed model using the HTTP web service end point


Before you can run this experiment, you need to first do the following:
1. Create an Azure Machine Learning service workspace
2. Create a cloud notebook server in your workspace.
