This folder contains the following:
Dockerfile : The main docker file     
requirements.txt: Docker file depenedencies
iris_EDA.ipynb:  EDA on the iris dataset
CreateAll.ipynb :  Creates the 4 models and saves the pickled version of the model. 
deployAPI.ipynb: Deployment notebook (for Reference)

Recommended to use Git Bash. (Should also work from windows CMD shell)
Build the docker image :
docker build . -t jupyter_nb
Run the docker image:
docker run -it -p 8888:8888 jupyter_nb 

