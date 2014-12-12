cassandra-playbooks
===================

To run -
* update inventory - cassandra.hosts
* update cassandra.yaml template
* ansible-playbook -k -i cassandra.hosts setup.yml --tags "setup"

default ask-pass
