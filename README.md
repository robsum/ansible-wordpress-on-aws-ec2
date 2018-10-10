# ansible-wordpress-on-aws-ec2

This is my first approach to setup Wordpress on AWS EC2 Red Hat 7.5 t2.micro instance.

## Getting Started

You need to create hosts file in ini format, ex:

[targets]
host0.example.com ansible_connection=ssh    ansible_user=host0-user   ansible_ssh_private_key_file=~/.ssh/host0.pem


### Prerequisites

The only prerequisite is Ansible. Configuration tested with Ansible version 2.7.0.

### Usage 

ansible-playbook -i hosts site.yml

## Author

* **Robert Sumara** - *Initial work* - [robsum](https://github.com/robsum)

No other contributors so far :-)

