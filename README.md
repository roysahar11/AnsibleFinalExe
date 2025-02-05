# Ansible Final Exercise - Roy Sahar
**Prequisities:**
In order for this playbook to run, the control node must have:
- Ansible installed, including all dependencies.
- AWS CLI installed, and AWS credentials updated under the _default_ profile (stored in _~/.aws/credentials_ on Linux)
- SSH keypair or keypairs configured between the control node and the host EC2 instances, and you should point to the SSH private key in the Ansible configuration file (_~/.ansible.cfg_)
  
To run the playbook, you should use this command:
_ansible-playbook site.yml -i ec2.aws_ec2.yml_
