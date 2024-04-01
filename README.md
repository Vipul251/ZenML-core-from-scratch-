As an ml practitioner i deep dive into building model using sklearn,pytorch,Tenserflow tools.An ml pipeline is simply an extension of a machine learning model including other steps befor or after bulidng a model like data acquistion,wrangling,preprocessing,model deployment or monitoring.The Ml pipeline essentially defines a step by step procedure of your work as an ml practitioner.Defining ml pipeline in code is great because:
1.We can easily rerun all of our work,not just the model, eliminating bags and
making our models easier to reproduce.
2.Data and model can be versioned and tracked so we can see glanced which dataset a model was trained and how it compares to other models.
3.If the entire pipeline is coded up,we can automate many operational tasks like retraining and redeploying model when problem or data changes or rolling out new and improved models with ci/cd workflows. bold text
So this is clear understanding of ml pipeline for ml teams so that we aim to serve models on large scales.


This repository showcases how ZenML can be used for machine learning with a GitHub workflow that automates CI/CD with continuous model training and continuous model deployment to production. This allows data scientists to experiment with data processing and model training locally and then have code changes automatically tested and validated through the standard GitHub PR peer review process. Changes that pass the CI and code review are then promoted automatically to production and can be used by end-users or other workloads relying just on the Production model stage.

This repository is also meant to be used as a template: you can fork it and easily adapt it to your own MLOps stack, infrastructure, code and data.

Throughout this series we wil define ml pipeline using zenml .Zenml is an excellent tool for this task and intutive to use and has integrations with most of the advanced mlops tools we will always want to use
