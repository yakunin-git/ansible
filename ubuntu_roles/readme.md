### Ubuntu roles repository.

This repository contains a more correct format for using ansible, named roles. You can run all roles at once, by default. Or use tags as hooks to complete specific items.

### Get started.

To launch all roles, use the classic way to launch a playbook.

```
ansible-playbook --inventory=hosts.yaml install.yaml
```

To use tags, specify them as one or more arguments.

```
ansible-playbook --inventory=hosts.yaml install.yaml --tags ssh --tags docker
```
