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
