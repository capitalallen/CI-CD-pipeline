# CI/CD pipeline
 A full CI/CD pipeline

## ./cicd-pipeline-train-schedule-gradle
- a simple gradle build for node.js web app
- build.gradle: install node.js and npm, run test and then generate a zip archive 

Running the app

You need a Java JDK 7 or later to run the build. You can run the build like this:
  
  ./gradlew build

You can run the app with:
  
  ./gradlew npm_start
  
  
 # Install Jenkins in Centos Linux environment via the YUM package manager. 
 ## configure the Jenkins YUM repositories 
 ### You can install Jenkins like so:
     sudo yum -y install java-1.8.0-openjdk epel-release
     sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat-stable/jenkins.repo
     sudo rpm --import https://jenkins-ci.org/redhat/jenkins-ci.org.key
     sudo yum -y install jenkins-2.190.1-1.1
