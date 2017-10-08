## rtfm.co.ua blog CloudFormation templates

Blog: https://rtfm.co.ua

### rtfm_jenkins_stack.json - Jenkins CI stack provisioning

**Description**

Will provision AWS EC2 t2.nano (default) instance and attach existing EBS with Jenkins data as /dev/xvdb.

### rtfm_stack_2017.json RTFM blog stack provisioning

**Description**

Will create CloudFormation stack with:

* VPC
  * Public subnet
  * Private subnet
* EC2
  * Bastion host in Public subnet
  * Services host in Private subnet
  * DB host in Private subnet
