## Deploy a High Availability Web App using CloudFormation 
This is a project Related to the cloud devops nanodegree related to udacity. Here we are going to create
 1. VPC
 2. Public and private Network
 3. Load Balancer
 4. API Gateway
 5. Security Group
 6. EC2 Instances

Parameters:

  * $STACK-NAME: The unique Id that the stack got when it is created
  
  * $TEMPLATE-BODY: This is the .yml file which contains all the details related to how to create the network as VPC, Public and private networks, API Gate way, etc.
  
  * PARAMETERS: The parameters which are going to be used to set the network

Deploy Infrastructure:
```
./create.sh $STACK-NAME $TEMPLATE-BODY $PARAMETERS
```

Update Infrastructure:
```
./update.sh $STACK-NAME $TEMPLATE-BODY $PARAMETERS
```

Clean up when you're done:
```
./delete.sh $STACK-NAME
```
