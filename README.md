# ansible-monero-node
# work in progess
Ansible role to install and configure a [Monero node](https://www.getmonero.org/) on Debian-like systems.

![ansible-lint](https://github.com/sleepy-nols/ansible-monero-node/actions/workflows/ansible-lint.yml/badge.svg)
![push-galaxy](https://github.com/sleepy-nols/ansible-monero-node/actions/workflows/ansible-galaxy-push-role.yml/badge.svg)
![Ansible Galaxy](https://img.shields.io/badge/Ansible_Galaxy-sleepy--nols.monero--node-blue)


---
## Role Variables and Defaults






---
## Installing

Install via Ansible Galaxy or clone the Repo
```
ansible-galaxy role install sleepy-nols.monero-node

git clone git@github.com:sleepy-nols/ansible-monero-node.git
```
---
## Example Playbook

```yml
- hosts: monero-nodes
  roles:
    - sleepy-nols.monero-node
```

---
## Contributing

Contributions on are welcome. :)

---
## License
GPLv3
