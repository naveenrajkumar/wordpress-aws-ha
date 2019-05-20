# wordpress-aws-ha

## - Wordpress HA Stack, 
	Creates a New VPC with the Private and Public Subnet, The Bastion and ALB is hosted in Public Subnet and the wordpress app 
	and Aurora DB Cluster with Master and Read Replica created in Private Subnet
	Few things were omitted in interest of time, like CDN distribution, supporting all the regions.
	The reference architecutres stack that is publicly available was referred during creation 
	of this stack. 
	
Region -  ap-southeast-2 - AP (Sydney) - [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=ap-southeast-2#/stacks/new?stackName=WordPress&templateURL=https://s3-ap-southeast-2.amazonaws.com/nvn-wordpress/aws-wordpress-main.yml) |
