# concentro.ai
Assigned Tasks as per my knowledge

1. Create EC2 instance for Jenkins job execution.

  I have created an EC2 instance and installed the all the required application for the  buil and deployment process:
  
      Installed application are:
      1. Git
      2. Tomcat
      3. Nodejs
      4. NPM Package
      5. Jenkins
      
   Also, started the service on the port 8080 for jenkins
   
2. Create EC2 instance for Deployment of docker image. 
    This instance should have docker daemon running. And open the port to access the website publicly.
   
   I have created the EC2 machine and installer docker and created nginx container. Also, I have stared the service to access our instance public DNS name in your browser.
   
Jenkins Job to Build & Deploy Pipeline
Create a Jenkins job to automate the build and deploy process of deployment of Nginx container hosting
a website.

Build Step:
Use https://github.com/gothinkster/vue-realworld-example-app website to build and copy the
dist folder (generated artifact as part of npm build command), into the Nginx docker image.

I have used the git hub repository to build the job.

I have used the following command to build 
npm install
npm run build

Deploy Step:
Use Ansible to deploy the above docker image inside that EC2 instance running the docker daemon.

After the Build to deploy I have used Ansible to write a playbook to install Nginx and deploy


