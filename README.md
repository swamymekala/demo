# Setting-Up environments
Unit Testing, Functional/Integration, Automation of above:-  QA needs to have a clean, untouched environment to test on, to make sure the product deploys correctly. Setup a build server, where you can build the code and run the application to test. For example, use Jenkins for checking out code and building for you. - Install Jenkins, SonarQube, selenium, Nagios and Jira.
UAT  and Production are alike environments: Must have same OS, Installed packages, Application and security setup as in production environment. - Install tomcat, Nagios.
Pre-Prod : Install docker, Nexus, Nagios
