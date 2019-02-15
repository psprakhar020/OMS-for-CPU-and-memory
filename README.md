# Script to set high CPU and Memory alerts on WINDOWS and LINUX machines.
    
## Description
The script will trigger the ARM template stored in the storage account and pass the array in order to deploy the
high CPU and Memory alerts on Windows and linux VM's for RIM DEV2.
     
## Author:     Prakhar Sharma
    
## Inputs
$WorkspaceName = Name of the workspace in which the machine has been on-boarded.
$SubscriptionName = Name of the subscription in which the Workspace is created.
$ActionGroupName = Name of the action group to which the alert email needs to be triggered.

## Outputs
High CPU and Memory Alerts would be applied on the mentioned resources.

## Note 
All the modules should be updated in the automation account.
    
