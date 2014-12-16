cassandra-playbooks
===================

default ask-pass

To install cassandra nodes run -
* update inventory - cassandra.hosts
* update cassandra.yaml template
* ansible-playbook -k -i cassandra.hosts setup.yml --tags "setup"


To install opscenter server run -
* update inventory - opscenter.hosts
* ansible-playbook -k -i opscenterserver.hosts setup.yml --tags "opscenter-server"

To install opscenter agents run -
* ansible-playbook -k -i cassandra.hosts setup.yml --tags "opscenter-agents"


