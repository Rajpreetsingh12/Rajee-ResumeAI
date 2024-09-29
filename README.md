# ResumeAI

## Overview

The project is a MEAN project and uses node version 18.


# 💫 About Me:
in hdfc life


## 🌐 Socials:
[![Behance](https://img.shields.io/badge/Behance-1769ff?logo=behance&logoColor=white)](https://behance.net/Rajpreetsingh12) [![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/rajpreet singh jahagirdar) [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/Rajpreetsingh12) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/raje_Hazurii) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/rajpreet singh jahagirdar) [![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@raje_Hazurii) [![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?logo=Pinterest&logoColor=white)](https://pinterest.com/rajpreet singh jahagirdar) [![Quora](https://img.shields.io/badge/Quora-%23B92B27.svg?logo=Quora&logoColor=white)](https://quora.com/profile/rajpreet singh jahagirdar) [![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?logo=Reddit&logoColor=white)](https://reddit.com/user/rajpreet singh jahagirdar) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/rajpreet singh jahagirdar) [![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white)](https://tiktok.com/@rajpreet singh jahagirdar) [![Twitch](https://img.shields.io/badge/Twitch-%239146FF.svg?logo=Twitch&logoColor=white)](https://twitch.tv/rajpreet singh jahagirdar) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/rajpreet singh jahagirdar) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@rajpreet singh jahagirdar) [![Codepen](https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white)](https://codepen.io/rajpreet singh jahagirdar) [![Mastodon](https://img.shields.io/badge/-MASTODON-%232B90D9?style=for-the-badge&logo=mastodon&logoColor=white)](https://mastodon.social/@rajpreet singh jahagirdar) 
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Rajpreetsingh12&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=Rajpreetsingh12&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Rajpreetsingh12&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=Rajpreetsingh12&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->


Practice Assignment on MEAN Project: - 

1) Create a fork of the project with a different name: - 

2) Write a docker file for each component (e.g front-end and backend both):- 

2.1 Backend Docker file: - 

Create a Dockerfile for the backend service in the root of your backend folder: 

NOte:- first check if the application is running on local via npm install 

                 1.by hitting npm install to install the necessary package managers for nodejs 

                 2.for running the build process of the index.js file 

                 3.now, you need to check the ls dist/main/index.js file if the build index.js exists. 

                 4.Now you need to hit the npm start to start the nodejs for running your backend      

                     Application. 

 

                  5.if you got the output as below which means the backend is allotted with the port  

                      4292 you can refer below ss for the more clarity:- 

                    

                    

                6.Now you need to dockerize the bakend image by building the docker file present 
                    in the backend root folder: - 

                    6.1 Hit the command “docker build –t resume-backend:latest “. 

                      

                    6.2 Now you need to containerize your docker image by hitting below command:  

                     “Docker run –p 3000:3000 resume-backend:latest” 

                      

                     As you can you can see the above ss show that the container is running on the 
                     port 3000 or 4292 you can check the same in your browser by hitting the below: - 

                      e.g:-  localthost:4292 

 

                   3)Frontend Dockerfile:- 

                      Create a Docker file for the frontend service: 

                      Now you need to navigate to your frontend directory for wiriting the below  

                      dockerfile with detailed layers: - 

                    

                      

                       For building the above docker image you need to hit the below command  

                      “Docker build –t resumeai-frontend:latest  .” 

                         

                          

 

 

 

 

                          Now you need to containerize the above docker image by hitting the below   

                         Command “docker run –p 4200:4200 resumeai-frontend:latest” 

                          

                          Note: - for accessing your frontend over the local host you need to hit below  
                          command “localhost:42000” 

                           

                         3. Write a docker-compose.yml File                

                          

 

                 4. Push the Docker Images into ECR: - 

                 4.1 pushing the frontend docker image into its repo on ecr:- 

                 Note:-for pushing the docker images build on local to your ecr repo 
                 on aws you need to follow the steps by clicking the view push 
                 command just in the top right corner of the each ecr repo: - 
                   

                      

                     Same you need to push the backend docker image by following the above steps  

                     In the ecr repo for backend: - 

                       

 

                     

                  To ensure the images you pushed are there in the respective ecr  
                   repos or not you can check by entering the repo: - 

                    

 

               5. Create a CI/CD Pipeline using Jenkins: - 

                   5.1) create the jenkins job a freesytle pipeline (job):- 

                    For automating the cloning of the project code from git-hub repo. 

                    Building the images for the frontend and backend and                        
                    containerizing the docker images and pushing them in the  
                    respected ecr repo on aws. 

                     

 

 

 

 

 

6. Deploy the Application using Minikube (Localhost) 

Installed Minikube: 

Installed the minikube by using the steps mentioned in the document: - 

https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download . 

 

6.1 Created Kubernetes Deployment Files: 

Deployment .yaml file for frontend: - 
 
 

 

 
           
                            

 

Deployment .yaml file for backend: - 

 

Deploy the application: - 

kubectl apply -f backend-deployment.yaml (deploying the backend on localhost) 

 

kubectl apply -f frontend-deployment.yaml (deploying the frontend on localhost) 

 

7. Create a Kubernetes Cluster and Deploy the Application using EKS: - 

7.1 Create an EKS cluster using the AWS Console or CLI: - 

7.1.1 Create IAM Roles for EKS: - 

 

 

 

7.1.2 Go to the IAM console: - 

 

7.1.3 Create two new IAM roles: - 

EKS Cluster Role: - 

7.1.4 Go to Roles → Create Role. 

 

7.1.5 Choose EKS service and select EKS - Cluster. 

 

 

7.1.6 Attach the policy AmazonEKSClusterPolicy. 

 

7.1.7 Name it something like EKS-Cluster-Role:- 

Inserting image... 

7.1.8 EKS Worker Node Role: - 

Go to Roles → Create Role. 

Choose EC2 service and attach the policy AmazonEKSWorkerNodePolicy, AmazonEC2ContainerRegistryReadOnly, and AmazonEKS_CNI_Policy. 

Name it something like EKS-Worker-Node-Role 

 

 

8.  Create a VPC for EKS: - 

If you don't have a VPC that meets the EKS requirements, you can create a VPC using the Amazon VPC Quickstart. It sets up subnets, route tables, and Internet gateways needed for EKS. 

You can follow the official guide for Creating a VPC for EKS 

 

8.1 Create the EKS Cluster: - 

Prerequisites: - you need to install aws cli and configure your local with your aws account and also you need to install eksctl on your local and minikube cluster needs to be there in the local. 

Use eksctl to create the EKS cluster. This command will create the control plane, networking, and worker nodes automatically. 

 

9) Deploy Application on Minikube(local host): - 

To build your Docker image inside Minikube: 

Hit the below command “eval $(minikube docker-env) docker build -t <your-image-name> .” 

9.1. Deploy the Application: - 

Frontend Deployment and Service: - 

 

9.1.2 frontend-service.yaml:- 

 

 

 

 

 

Prerequisites for deploying the project on Eks: - 

1.AWS CLI installed and configured -from google or aws guide 

2.kubectl installed (Installation Guide).- https://blog.knoldus.com/how-to-install-eksctl-the-official-cli-for-amazon-eks/#:~:text=download%20this%20cli.-,Downloading%20Eksctl%20on%20Ubuntu%2FDebian,eksctl%20with%20the%20following%20command.&text=Test%20that%20your%20installation%20was%20successful%20with%20the%20following%20command.&text=Now%20after%20finishing%20the%20setup,with%20this%20command%2Dline%20utility. 

3.eksctl installed for managing EKS clusters- 

4.Docker images pushed to Docker Hub (or another registry accessible to EKS). 

 

10. Steps for EKS Deployment: - 

10.1 Create an EKS Cluster: - 

Use eksctl to create a cluster in your AWS account:- 

eksctl create cluster \ 

--name resume-builder-cluster \ 

--region <your-aws-region> \ 

--nodegroup-name resume-builder-nodes \ 

--node-type t3.medium \ 

--nodes 2 \ 

--nodes-min 1 \ 

--nodes-max 3 \ 

--managed 

11. Configure kubectl:- 

Once the cluster is created, configure kubectl to interact with your EKS cluster. 

aws eks --region <your-aws-region> update-kubeconfig --name resume-builder-cluster 

 

Replace <your-aws-region> with the AWS region where you want the cluster (e.g., us-east-1). 

This command creates a managed EKS cluster with 2 nodes, with auto-scaling enabled. 

 

 

 12. Configure kubectl:- 

Once the cluster is created, configure kubectl to interact with your EKS cluster 

 

13.Apply Kubernetes manifests for your backend,frontend and database services:- 

Deployment: - 

Create a deployment.yml files backend,frontend,mongo-db and also you need to create the namespaces for all the frontend,backend & mongo-db and also you need to create theservice.yml for the frontend and backend as well 

And then you need to apply the deployment in the below manner: - 

-kubectl apply -f mongo-deployment.yml 

 

And then you need to apply your services using the below command: - 

-kubectl apply -f backend-service.yaml 

 

 

14. Create a ConfigMap for Environment Variables:- 

Create a configmap.yaml file to store environment variables, such as the backend URL:- 

 

 

15. Monitor the Application:- 

You can monitor the status of your deployments and services with these commands:- 

kubectl get pods -n frontendrb (it will display all the running pods inside your eks cluster) 

kubectl get svc -n frontendrb (it will deisplay the load balancer in the namespac) 

kubectl logs <pod-name> -n frontendrb (it will show you all the logs of your kubernetes pods in the eks cluster) 

 

 

 

 

                   

 

    

                   

                            

                        

                    
 
                      

                 

            
