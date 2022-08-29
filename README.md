# simple-docker-pipeline-ecs-cv-app

<p>Add Three Environment variables on build machine 

1) AWS_DEFAULT_REGION <br>
  
2) AWS_ACCOUNT_ID <br>
  
3) IMAGE_REPO_NAME



#Create A Pipeline On CodePipeline & Deploy a Simple web app on elastic container service(ECS) | AWS

1) Create CodeBuild Project
2) Add Environment Variable
3) Create Repositories on Amazon Elastic Container Registry (ECR)
4) Manual Build Test 
5) Add ECR Access Permission to Build Machine Policies 
6) Manual Build Test Again 
7) Check Image on Repositories of Amazon Elastic Container Registry (ECR) 
8) Create Amazon Elastic Container Service (ECS) Cluster
9) Configure task definition and containers
9.1) Put container Name & Image URL
10) Deploy Services
10.1) Add a Security group that port are Enable HTTP TCP [80] ports
10.2) Create Application Load Balancing & Target Point
11) Check the Security group which port Enable HTTP TCP [80]
12) Check Application by public IP
13) Check Application by  Load Balancing DNS
14) Create a Pipeline
14.1) Add Source Stages [Github]
14.2) Add Build Stages [previous create project]
14.3) Add Deploy Stages [previous create Deploy (ECS)]
15) Update imagedefinitions.json [container_name and image_url]
16) Check Deploy Pipeline Successfully   
17) Check Site load Successfully
18) Update Code on Github and Cheke Pipeline
19) Check Deploy Pipeline Successfully Again
20) Load Site from Load Balancing DNS Again
