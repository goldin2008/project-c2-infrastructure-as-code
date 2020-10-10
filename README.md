## ND9991 - C2- Infrastructure as Code - Supporting Material and Starter Code
This folder provides the supporting material and starter code for the "ND9991 - C2- Infrastructure as Code" course. This folder contains the following folders:
1. project_starter - It contains the starter code.
2. supporting_material - It contains the essential files (.yml, .json, .bat, .sh, and .jpeg) that were referred in the different lessons of this course.


### Dependencies
##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).

##### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com](www.lucidchart.com) is required to be able to draw the web app architecture diagrams for AWS.
# project-c2-infrastructure-as-code

# Project 2 - Deploy a High-Availability Web App using CloudFormation 

>I have successfully deployed a High availability Web App for Udagram using cloudformation from ground up.

>URL to the deployed site: http://d2bil30o98pymr.cloudfront.net/index.html

## The files included are:

* Screenshots of Udagram App : Screenshot the result of deploy.
* Udagram Web App : Udagram App Code (Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function etc ...)
* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* udagram-networkandserver.yml : Udagram Project's CloudFormation script.
* udagram-networkandserver.json : Udagram Project's CloudFormation script parameters.
```

## Commands
### CloudFormation Network Stack creation & Update commands
```sh
$ sh create.sh <cloudformation_network_stack_name> network.yml network-parameters.json
$ sh update.sh <cloudformation_network_stack_name> network.yml network-parameters.json
```
### CloudFormation Server Stack creation & Update commands
```sh
$ sh create.sh <cloudformation_server_stack_name> servers.yml server-parameters.json
$ sh update.sh <cloudformation_server_stack_name> servers.yml server-parameters.json
```
### CloudFormation delete stack command
```sh
$ aws cloudformation delete-stack --stack-name <cloudformation_stack_name>
```
