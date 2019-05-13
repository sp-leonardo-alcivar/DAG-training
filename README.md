# DAG-training
A training on DAG models for causality discovery.

Before beginning with the training you should install the following software (in the order established below):

From the website:

- Anaconda with python 3.

On the terminal:
- curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
- python get-pip.py
- pip install rpy2
- pip install tzlocal

On R:
- install.packages("BiocManager")
- BiocManager::install("graph")
- BiocManager::install("RBGL")
- BiocManager::install("Rgraphviz")
- install.packages("pcalg")
- install.packages("SMPracticals")
