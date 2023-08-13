LONG NGUYEN HOANG - PROJECT 3 - UDACITY

INSTRUCTION TO RUN THIS PROJECT
1 - Create images for analytics API
    + Create dockerfile to build python project
    + Create buildspec file to automatic push images to ECR
    + Push the project to github
    + Create CodeBuild Pineline to push the github project to ECR
    + Get the Image URL to used in deployment file
2 - Configure help postgresql and deployment file
    + Create EKS cluster and node group
    + Add the cluster to kubectl config
    + Install helm chart postgresql and seed the data in db/ folder
    + Create deployment file to deploy app and service
    + Create db configmap file and db secret file to save enviroment variable
    and database password
    + Deploy these file using kubectl 

Note: Each time install the helm chart postgresql, the password 
of db will change, so make sure get it and save to used in deployment file