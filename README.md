# sample-java-deployment-jenkins-sonartube
Sample Java Pipeline Deployment  with Jenkins and Monitor with SonarQube

Idea Credit - https://www.youtube.com/watch?v=wn9wWYAShag
https://github.com/ravdy/DevOps
 
 
Prerequisites and Testing Environment!
AWS Account
EC2 Instance
Required routes connection and security process between EC2 instances

1. Install Jenkins server in EC2.
https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/

2. Install Sonarqube in EC2.
https://docs.sonarqube.org/latest/setup/install-server/

3. After successfully login to Sonarqube dashboard, you must get token for authentication process from Sonarqube to Jenkins. (screenshot in sonarqube-01).

4. Go back to Jenkins and do the following process.
 4.1 Login the Jenkins dashboard
 4.2 Install Sonarqube plugins 
 4.3 Add the credentials from Sonarqube in Jenkins system
 4.4 Configure SonarScanner
 4.5 Create item and run a simple java pipeline job
 


