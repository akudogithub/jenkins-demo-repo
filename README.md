# jenkins-demo-repo
#This is a repo to demo a jenkins pipeline build using a webhook
#The steps involve;
#step1: write a Jenkinsfile 
#step2: create a repository in github to warehouse the codes (Jenkinsfile)
#step3: create a pipeline job in jenkins & give jenkins the github credentials to enable pulling of the codes from github. Ensure all the plugins are downloaded including blueocean plugin, to visualize the build on a web dashboard
#step4: create a connection between jenkins and github by configuring a webhook that will trigger a build automatically & define the build trigger
#step5: push the codes (Jenkinsfile) from vscode to the remote repository
#step6: if all is properly configured, jenkins will pull the codes and run the pipeline based on the defined build trigger
#step7: view the console output for details of the build in case of success or failure.
