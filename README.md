# README

Devops Exercise: 

The candidate should set up a continuous build pipeline using Jenkins, Github and Amazon EC2 service.

Some requirements are left intentionally vague:

There must be a hello world web application in your personal Github account. The language doesn't matter, e.g. ruby, python, java, etc.
There must be a running instance of Jenkins in AWS with a public DNS name
There must be a running instance of your application in AWS with a public DNS name
Github must be configured to notify the Jenkins instance on every commit
Jenkins must be configured to build and deploy a Docker image on every commit notification from Github
Your application instance must reflect changes from every commit pushed to Github
Bonus points for use of configuration management and database

