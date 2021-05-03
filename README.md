# Deploy-a-High-Availability-Web-App-using-CloudFormation
The project contains infrastructure as code for project on udacity "Deploy a High-Availability Web App using CloudFormation"

![alt text](https://github.com/Ticlla/Deploy-a-High-Availability-Web-App-using-CloudFormation/blob/main/VPC-Server%20Udagram.png?raw=true)


Index.html /index.zip needs to be uploaded to correspondant S3 AWS account so that IAC perfomrs all actions and builds successful architecture

to create the Infrastructure please run

```
./create.sh Stack final-project.yml final-project-parameters.json

```

Where <StackName> is any stack you want to creaet then files on repo
  
  
![alt text](  https://github.com/Ticlla/Deploy-a-High-Availability-Web-App-using-CloudFormation/blob/main/Screenshot%20from%20April%2018%2C%202021%206_20%20AM.png?raw=true)

you will have an DNS on output e.g

http://vpc-s-webap-xiy5j8ao241j-24743260.us-west-2.elb.amazonaws.com/
