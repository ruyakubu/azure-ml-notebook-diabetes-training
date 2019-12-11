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


## To run on a Cloud-based Nookbook VM

Here are the following theses you need to follow:
1. Clone this github repository
2. Create an [Azure Machine Learning service workspace](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-manage-workspace)
3. Create a cloud notebook server in your workspace.
   1. [Sign in to Azure Machine Learning studio.](https://ml.azure.com/)
   2. Select your subscription and the workspace you created.
   3. Once on the ML studio page, select **Compute** on the left.
   4. Select **+New** to create a notebook VM.
   5. Provide a name and select configuration for your VM. Then click **Create**.
   6. Wait until the status changes to **Running**
4 Select **Notebooks** on the left.
5. On the Notebooks page, click on the *Upload files* (the up arrow) icon to upload the **demo-diabetes-experiment-sdk-train.ipynb** file from the github repository   


