# AWS Utility Scripts
## To automate long aws commands into small utilities.

 Each script can be started as `$sh <scriptname>.sh`

### [instanceId.sh](/instanceId.sh) 
 - Purpose - To get the Instance Id of the EC2 Instance
 - Prerequisite - AWS CLI must been installed and working.
 - Condition - At present it support only single EC2 Instance, getting multiple EC2 Instance Ids is in future scope.
  
### [start.sh](/start.sh)
 - Purpose - To start the single EC2 instance
 - Prerequisite - AWS CLI must been installed and working. instanceId.sh shoudl be present in current directory.
 - Condition - At present it support only single EC2 Instance, getting multiple EC2 Instance Ids is in future scope.

### [stop.sh](/stop.sh)
 - Purpose - To stop the single EC2 instance
 - Prerequisite - AWS CLI must been installed and working. instanceId.sh shoudl be present in current directory.
 - Condition - At present it support only single EC2 Instance, getting multiple EC2 Instance Ids is in future scope.

### [ip.sh](/ip.sh)
 - Purpose - To give the public IP of running single EC2 instance
 - Prerequisite - AWS CLI must been installed and working. instanceId.sh shoudl be present in current directory.
 - Condition - At present it support only single EC2 Instance, getting multiple EC2 Instance Ids is in future scope.
