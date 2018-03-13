# Summary #

Deploy provided application w/ end-to-end automation and auto-scaling capability.

# Exercise #

## Important Note ##

For infrastructure configurating should be used terraform tool 
Application should be packaged as docker image

## Details ##

### Create an AWS free tier account ###

* You may use EC2, or any other AWS free tier service for this exercise.
* VPC specific objects can be created manually (VPC, Route tables, Subnets, NAT's etc.)

### Create a Github (or other) source control account ##

* Create source repository for this exercise.
* Push docker image with application to DockerHub.
* Provide full source for all automation necessary to complete this exercise.
* Create a README for the source project, which includes some of the following information:
    * A summary of the exercise as executed.
    * Any important details (development, deployment, testing, etc.) in support of the exercise. 
    * URLs or sources of information used to create your work.
    * Any other information you think is pertinent.
* All best practices for source control should be utilized.

### Create application orchestration deployment process for the provided Go application ###

* The application must be deployed fully via an automated process.
 
### Deploy the provided Go application to AWS ###

* The AWS resources must be deployed fully via an automated process.
* The application must scale when placed under load. 
* The process to decide how and when to scale is also at your discretion.

### Be prepared to provide evidence of capabilities, such as auto-scaling ###

* Supply us with a functional FQDN/endpoint for the application.
    * This application should be accessible via the public internet.
* Supply us with the github (or other) source repository URL for review.
* Provide example or details as to how we can evaluate the success of your deployment.
