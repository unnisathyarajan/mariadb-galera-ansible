### Deploy the Galera cluster from scratch(on first run).

```shell
ansible-playbook -i inventories/galera/test/hosts galera.yml -e 'first_time=true'
```

### Just run the below command for any configuration changes.

```shell
ansible-playbook -i inventories/galera/test/hosts galera.yml
```
