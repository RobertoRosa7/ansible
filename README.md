# ansible

#### Primeiro comando com ansible
`ansible wordpress -u vagrant --private-key .vagrant/machines/wordpress/virtualbox/private_key -i hosts shell - a "echo Hello World"`


#### Ansible Playbook
`ansible-playbook provisioning.yml -u vagrant -i hosts --private-key .vagrant/machines/wordpress/virtualbox/private_key`