## Deploy Infrastructure as Code
# [Deploy a High-Availability Web App using CloudFormation](https://classroom.udacity.com/nanodegrees/nd9991-alg-t2/parts/cd0648/modules/31f7d825-c32d-4384-964b-007c8e732ce3/lessons/126449d6-3425-403d-b1cd-0d567fee635d/concepts/88c2e603-cdd1-4cda-966b-d3f7ea8b4104)

Project Submission

Deploy Network: 
`aws cloudformation create-stack --stack-name udacityProject --region us-east-1 --template-body file://network.yml --parameters file://network-parameters.json`

Deploy Server: 
`aws cloudformation create-stack --stack-name udacityProjectServer --region us-east-1 --template-body file://server.yml --parameters file://server-parameters.json`

Web App Link: http://udacityproject-81168769.us-east-1.elb.amazonaws.com/


![Infrastructure Diagram](diagram.png)


