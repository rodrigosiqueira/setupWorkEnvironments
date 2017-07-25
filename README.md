----
# My Ansible stuffs

> Here I have some ansible playbooks for configure some small environments.

> Just run:

```
ansible-playbook <any_specific_target>.yml -i <specific_inventory>
```

> Where:

* _any_specific_target_: a single playbook that describe one sort of environment
* _specific_inventory_: any inventory, maybe you have to adapt it

# Environments

1. Debian Packaging Environment (debian_package): Sometime time I have to pack
some Debian package, and this file just configure the basic stuffs for that
