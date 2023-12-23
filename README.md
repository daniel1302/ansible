# Setup order

```shell
ansible-playbook playbooks/localhost.yaml -u daniel -k;

ansible-playbook playbooks/physical-servers.yaml -u root -k;

ansible-playbook playbooks/apps.yaml
``` 