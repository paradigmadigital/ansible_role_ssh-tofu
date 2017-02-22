# ssh-tofu

Add unknown ssh server keys to your known_hosts

# Role Variables

* `ssh_known_hosts_command` : ssh-keyscan command to discover hosts
* `ssh_known_hosts_file`    : Full path to the known_hosts file

# Example playbook

```yaml
- hosts: all
  gather_facts: false
  roles:
    - ssh-tofu
```

# License

GPLv2

# Author Information
jamatute (jamatute@paradigma)
