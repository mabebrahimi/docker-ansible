# docker-ansible

An Ansible Playbook that installs [Docker](https://www.docker.com/) on debian base Linux.

## Requirements

- [Ansible](https://www.ansible.com/)

## Running the playbook

- Create [Inventory](http://docs.ansible.com/ansible/intro_inventory.html) of cluster hosts:

```
$ vi ~/hosts.ini

[backend_server]
host1.example.com
host2.example.com

[db_server]
host3.example.com
```

- Run playbook

```
ansible-playbook -i hosts.ini -b playbook.yml
```

## CI Robots

[@dwsclass](https://github.com/dwsclass) dws-ops-002-ansible

## How to contribute

All contributions are welcomed. If you find any bugs, please file an issue.

## License

[APACHE LICENSE, VERSION2.0](https://www.apache.org/licenses/LICENSE-2.0)
