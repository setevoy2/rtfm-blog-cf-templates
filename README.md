## rtfm.co.ua blog CloudFormation templates

Blog: https://rtfm.co.ua

### Files

* [rtfm-jenkins-stack.json](https://github.com/setevoy2/rtfm-blog-cf-templates/blob/master/rtfm-jenkins-stack.json) - Jenkins CI stack provisioning
Will provision AWS EC2 t2.micro (default) instance and attach existing EBS with Jenkins data as `/dev/xvdb`.

* [rtfm-blog-cf-template.json](https://github.com/setevoy2/rtfm-blog-cf-templates/blob/master/rtfm-blog-cf-template.json) RTFM blog stack provisioning
Will create CloudFormation stack with:

  - Public subnet
  - Private subnet
  - Bastion host in Public subnet
  - Services host in Private subnet
  - DB host in Private subnet

Related blog posts (in russian only for now):

1. [AWS: миграция RTFM 2.1 – CloudFormation для EC2 c Jenkins](https://rtfm.co.ua/aws-cloudformation-dlya-ec2-c-jenkins/)
2. [Ansible: миграция RTFM 2.2 – RTFM Jenkins provision](https://rtfm.co.ua/ansible-rtfm-jenkins-provision/)
3. [AWS: миграция RTFM 2.3 – инфраструктура для RTFM и создание CloudFormation шаблона – VPC, subnets, EC2](https://rtfm.co.ua/aws-infrastruktura-dlya-rtfm-i-sozdanie-cloudformation-shablona-vpc-subnets-ec2/)
4. [Jenkins: миграция RTFM 2.4 – Jenkins Pipeline для CloudFormation RTFM стека](https://rtfm.co.ua/jenkins-migraciya-rtfm-2-4-jenkins-pipeline-dlya-cloudformation-rtfm-steka/)
5. [AWS: миграция RTFM 2.5 – настройка NAT на Bastion EC2 как замена NAT Gateway](https://rtfm.co.ua/aws-migraciya-rtfm-2-5-nastrojka-nat-na-bastion-ec2-kak-zamena-nat-gateway/)
6. [Jenkins: миграция RTFM 2.6 – Jenkins Pipeline для Ansible](https://rtfm.co.ua/jenkins-migraciya-rtfm-2-6-jenkins-pipeline-dlya-ansible/)
7. [AWS: миграция RTFM 2.7 – CloudFormation и Ansible – наcтройка NAT](https://rtfm.co.ua/aws-migraciya-rtfm-2-7-cloudformation-i-ansible-nactrojka-nat/)
8. [Ansible: миграция RTFM 2.8 – logrotate, unattended-upgrades и Let’s Encrypt для Bastion хоста](https://rtfm.co.ua/ansible-migraciya-rtfm-2-8-logrotate-unattended-upgrades-i-lets-encrypt-dlya-bastion-xosta/)
9. [Ansible: миграция RTFM 2.9 – монтирование EBS и настройка NGINX на Bastion](https://rtfm.co.ua/ansible-migraciya-rtfm-2-9-montirovanie-ebs-i-nastrojka-nginx-na-bastion/)
10. [Ansible: миграция RTFM 2.10 – Let’s Encrypt, NGINX SSL, hostname и exim](https://rtfm.co.ua/ansible-migraciya-rtfm-2-10-lets-encrypt-nginx-ssl-hostname-i-exim/)
11. in progress
