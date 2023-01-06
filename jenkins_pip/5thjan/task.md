# Build a continuous Integration:
----
* Build a sonarcube ,jfrog artifictory,jfrog xray to scan docker images and also message notification settings 'mail trap'.
* write pipeline for any 3 applications like java, NodeJS, python , dotnet …etc.
* Requirement:
              GitHub, Jenkins server, JFrog, SonarQube, build machine
* Name of Docker Image: repo name or app Name
 Ex: ram-repo/test è ram-repo-test
* If branch is master or main need get image tag as build Number.
* If branch is bugfix/ or feature/ then need to tag {branch name}-{build Number}
 Ex: bugfix/test =è bugfix-test= {build Number}
* If release tag build, then need to pass release version as tag
Ex: release/1.0.0 then tag 1.0.0 is required
----
* follow the link to integrate sonarqube cloud with jenkins:`https://docs.sonarcloud.io/advanced-setup/ci-based-analysis/jenkins-extension-for-sonarcloud/`.
* read this to understand the sonarcube code analysis sysntax in jenkins  `https://www.jenkins.io/doc/pipeline/steps/sonar/`.
* read the following link to under-stand artifactory upload and download form jfrog artifactory `https://www.jfrog.com/confluence/display/JFROG/Scripted+Pipeline+Syntax`.
*  Refer the link to watch videous for jfrog xray and jfrog artifactory `https://www.jfrog.com/confluence/display/JFROG/JFrog+Cloud`.
*  