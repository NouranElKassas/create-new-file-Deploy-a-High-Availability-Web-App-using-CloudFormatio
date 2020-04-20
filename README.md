# create-new-file-Deploy-a-High-Availability-Web-App-using-CloudFormatio
This is a project Related to the cloud devops nanodegree related to udacity.
Parameters:
  * $STACK-NAME: The unique Id that the stack got when it is created
  * $TEMPLATE-BODY: This is the .yml file which contains all the details related to how to create the network as VPC, Public and private networks, API Gate way, etc.
  * PARAMETERS: The parameters which are going to be used to set the network

Deploy Infrastructure:

./create.sh $STACK-NAME $TEMPLATE-BODY $PARAMETERS

Update Infrastructure:

./update.sh $STACK-NAME $TEMPLATE-BODY $PARAMETERS

Clean up when you're done:

./delete.sh $STACK-NAME

