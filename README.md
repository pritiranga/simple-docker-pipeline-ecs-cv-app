# simple-docker-pipeline-ecs-cv-app

<p>Add Three Environment variables on build machine 

<b>1) AWS_DEFAULT_REGION <br></b>
  
<b>2) AWS_ACCOUNT_ID <br></b>
  
<b>3) IMAGE_REPO_NAME</b>



#Create A Pipeline On CodePipeline & Deploy a Simple web app on elastic container service(ECS) | AWS

1) Create CodeBuild Project <br>
2) Add Environment Variable <br>
3) Create Repositories on Amazon Elastic Container Registry (ECR) <br>
4) Manual Build Test <br>
5) Add ECR Access Permission to Build Machine Policies <br>
6) Manual Build Test Again <br>
7) Check Image on Repositories of Amazon Elastic Container Registry (ECR) <br>
8) Create Amazon Elastic Container Service (ECS) Cluster <br>
9) Configure task definition and containers <br>
9.1) Put container Name & Image URL <br>
10) Deploy Services <br>
10.1) Add a Security group that port are Enable HTTP TCP [80] ports <br>
10.2) Create Application Load Balancing & Target Point <br>
11) Check the Security group which port Enable HTTP TCP [80] <br>
12) Check Application by public IP <br>
13) Check Application by  Load Balancing DNS <br>
14) Create a Pipeline <br>
14.1) Add Source Stages [Github] <br>
14.2) Add Build Stages [previous create project] <br>
14.3) Add Deploy Stages [previous create Deploy (ECS)] <br>
15) Update imagedefinitions.json [container_name and image_url] <br>
16) Check Deploy Pipeline Successfully <br>
17) Check Site load Successfully <br>
18) Update Code on Github and Cheke Pipeline <br>
19) Check Deploy Pipeline Successfully Again <br>
20) Load Site from Load Balancing DNS Again <br>
