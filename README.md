This application deployment is designed, built and configured in such a way that every part of it can be used in CICD pipeline automation
Also the deployment is done in such a way that it can horizontally scale in case of failure or excessive loads

Tools used:

Docker: for containerization and build image
Ansible: To automate the image building process and Push to the DockerHub
DockerHum: To store the images
Kubernetes: To deploy the DB and App pods in the cluster 

Please go to each folder to understand more in details:

Read the README file for steps and understanding
Images are attached to show that deployment was tested.
