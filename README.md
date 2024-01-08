
# Retreival Augmented Generation

A friendly chatbot to reduce your boilerplate development and increase your productivity.

## Prerequisites

* Open AI Account (Get an **API Key**)
* Qdrant Cloud Account (Keep Handy of Qdrant Cloud **API Key** and **URL**)
* Create a collection in Qdrant Cloud (Default name: **my_documents**) for this Project

## Steps to Follow

* Clone the repository - https://github.com/varunmayaluru/RAG-DOC-APP.git

* Use docker-compose Commands to keep the application up and running. 

    * docker-compose up 
    * docker-compose up --build (Incase if you eant to rebuild)
    * docker-compose down 

* Use the following URL to browse the application

http://localhost:8501 


## Commands to clean up house

### Stop and remove all running containers
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
### Remove all Docker images
docker rmi $(docker images -a -q)
### Remove all Docker networks
docker network rm $(docker network ls -q)
