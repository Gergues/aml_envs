# aml_envs
Azure Machine Learning Environments

This repository contains the yaml file definitions of the conda environments used on the Azure Machine Learning compute instances

I do find it important at time to rebuild those on non Azure environments and need to export and import those environments for development purposes

Please note : AML is a Azure Machine Learning - a platform offered and maintaine and updated periodically by Microsoft Azure , this is only a copy for faster development

Please update this as needed



#How to export a conda  environment 

Normally you would 


conda env export --no-build > environment.yml
