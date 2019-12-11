# azure-ml-notebook-diabetes-training
In this tutorial, you will create an experiment that connects to Azure Machine Learning workspace; train a simple scikit-learn model based on the diabetes data set, register the model; deploy the model to an Azure Container Instance; and test the trained model. After completing this tutorial, you will have the practical knowledge of the SDK to scale up to developing more-complex experiments and workflows. 

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

Here are the following steps you need to take:
1. Clone this github repository
2. Create an [Azure Machine Learning service workspace](https://aka.ms/aml-workspace/?WT.mc_id=azueMLstudio-webinar-ruyakubu)
3. Create a cloud notebook server in your workspace.
   1. [Sign in to Azure Machine Learning studio.](https://aka.ms/aml-studio/?WT.mc_id=azueMLworkspace-webinar-ruyakubu)
   2. Select your subscription and the workspace you created.
   3. Once on the ML studio page, select **Compute** on the left.
   4. Select **+New** to create a notebook VM.
   5. Provide a name and select configuration for your VM. Then click **Create**.
   6. Wait until the status changes to **Running**
4 Select **Notebooks** on the left.
5. On the Notebooks page, click on the *Upload files* (the up arrow) icon to upload the **demo-diabetes-experiment-sdk-train.ipynb** file from the github repository
6. Execute the Jupyter notebook script by either clicking on the **Run** link on the run Notebook server page, or Click on the **...** link to open in Jupyter and run the script.


