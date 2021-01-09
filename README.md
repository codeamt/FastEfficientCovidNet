# Fast Efficient CovidNet -  An End-to-End Pipeline
This GitHub Repository contains my final project for Udacity's Machine Learning Engineer Nanodegree

## About 
This is a Chest X-Ray (CXR) classification API. Building on previous work of [[1]](https://arxiv.org/pdf/2003.09871v3.pdf), the CovNet model for this ML project utilizes a pre-trained EfficientNet-b1 to extract features and a fine-tuned Fast.ai classifier to differentiate between infection classes (Normal, Viral Pneumonia, or COVID-19) with 95% test accuracy. 
 
 ## Repo Contents: 
 - [mle-capstone-data (submodule)](https://github.com/codeamt/mle-capstone-data/tree/59e37548c295c7afba448c156c7a96382da10152)
 - [mle-capstone-modeling (submodule)](https://github.com/codeamt/mle-capstone-modeling/tree/7cc4429ef62183be9caf23cb4d811fea2e640081)
 - [mle-capstone-deployment (submodule)](https://github.com/codeamt/mle-capstone-deployment/tree/6113dab8602c224f534b8f048b7e52618a229331)
 - [project propsal (pdf)](https://github.com/codeamt/udacity-mle-capstone-project/blob/master/proposal.pdf)
 - [project report (pdf)](https://github.com/codeamt/udacity-mle-capstone-project/blob/master/report.pdf)
 - [README.md (here)]()
 
 ## Instructions: 
Each submodule provides an .ipynb file for a detailed walkthrough of that project phase.

In the data submodule, to generate the COVIDx dataset, you'll neet a kaggle account. If you don't have an account, you can create one at [kaggle.com](https://www.kaggle.com/). From there, from the top right menu, visit My Account > API > create New API Token > ... to get a JSON  hardfile of your API Token.

In the deployment submodule, if you'd like to run the quick start demo notebook, you'll also need to create a [ngrok]() account and API token.  
 
 
