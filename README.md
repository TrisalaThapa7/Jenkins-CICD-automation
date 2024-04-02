# Jenkins-CICD-automation

1. Step1: Deploy the sample application on EC2 Server and test if it is working.
   > Create an Ubuntu EC2 Instance
   > Login to the Ec2 instance
   > Clone the application code from the GitHub Repo
   > Run the application code (To run, we need python and pip3 installed. so check if you have it if not then install it. #sudo apt install python3-pip)
      (#pip3 install flask)
   
2. Containerise the application using Docker container
   > For this we need to install docker on our EC2 instance
   > Write Dockerfile which is needed to build the image

3. Time to Automate: Use Jenkins CICD Pipeline to Automate the process
   > Need Jenkins server.
   > need dockerhub account
   > Create new Jenkins pipeline
   > Create the Jenkinsfile with different stages to automate the process.
   > Check if everything is working fine.
