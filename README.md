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
1. Clone this github repository
2. [Create an Azure Machine Learning service workspace](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-manage-workspace)
3. Create a cloud notebook server in your workspace.
⋅⋅a. [Sign in to Azure Machine Learning studio.](https://ml.azure.com/)
⋅⋅b. Select your subscription and the workspace you created.
⋅⋅c. On in the ML studio, select Compute on the left.
⋅⋅d  Select +New to create a notebook VM.
⋅⋅e  Provide a name and select configuration for your VM. Then click Create.
⋅⋅f	 Provide a name for your VM. Then select Create.
⋅⋅g	Wait until the status changes to Running
⋅⋅h Select Notebooks on the left.
⋅⋅i On the Notebooks page, click on the "Upload files" icon to upload this jupyter notebook file

