Lab - Register and deploy a ML model

Lab Objectives:

In this lab, you will:

Train your model using the Azure Machine Learning service.
Register the model you created to the registry in the workspace
Create a model scoring script
Create a YAML file configuring Python module dependencies
Create a container image
Deploy a model as a web service
Score new data with the deployed model
Introduction

In this lab, you will train the model you developed in the last lab on Azure using the Azure Machine Learning service and its Python SDK. After it has been trained, you will register the model to the registry and perform the steps necessary to deploy your model to Azure Machine Learning service where it can be used.

Lab 2: Resources

You will use the following files from the lab folder:

Name	Description
Starter_Lab2_Notebook.ipynb	The lab notebook you should use. Import this into your Notebook project and open it.
For help on creating Azure Notebook projects and importing notebooks see: https://docs.microsoft.com/en-us/azure/notebooks/quickstart-migrate-local-jupyter-notebook

For help on uploading data into Azure Notebook see: https://docs.microsoft.com/en-us/azure/notebooks/work-with-project-data-files

Prerequisites

Before you can do this lab, you need to have:

Signed Up for the free Azure Notebook Service.
An Azure subscription that can provision an Azure Machine Learning service workspace.

Check here for the solution file - [![Azure Notebooks](https://notebooks.azure.com/launch.svg)](https://notebooks.azure.com/CodeSizzler/projects/dp100-lab-2-train-and-deploy-a)
