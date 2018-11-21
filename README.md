# concentro.ai
Assigned Tasks as per my knowledge


Cloud Formation Automation

 Create a ECR repository, for pushing the docker image.

 Create EC2 instance for Jenkins job execution.

 Create EC2 instance for Deployment of docker image. This instance should have docker daemon running. And open the port to access the website publicly.

Jenkins Job to Build & Deploy Pipeline
Create a Jenkins job to automate the build and deploy process of deployment of Nginx container hosting
a website.



Build Step:
Use https://github.com/gothinkster/vue-realworld-example-app website to build and copy the
dist folder (generated artifact as part of npm build command), into the Nginx docker image.

Deploy Step:
Use Ansible to deploy the above docker image inside that EC2 instance running the docker daemon.
Note:
In order to build the https://github.com/gothinkster/vue-realworld-example-app project you will
require NodeJs Package Manager(npm) - v5.6.0 with NodeJs - v8.11.3. You can refer below link
to install the dependency softwares.
https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04

Once the dependency softwares are installed you can run the following command to build the project.
$ npm install
$ npm run build

Output of the above process results in a `dist` folder with website code (all static content). You can
refer below link to see how to host website in Nginx.
https://medium.com/@jasonrigden/how-to-host-a-static-website-with-nginx-8b2dd0c5b301
