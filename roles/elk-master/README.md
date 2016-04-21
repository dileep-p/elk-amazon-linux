Ansible role to install ELK stack in Amazon Linux


How to run the playbook
-----------------------
ansible-playbook -e target=127.0.0.1 -e elasticsearch_install=true -e kibana_install=true -e logstash_install=true -e elasticsearch_host=localhost elk.yml
