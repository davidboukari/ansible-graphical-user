# ansible-graphical-user


## Playbook sample for a role

```bash
cat playbook.yml
---
 - name: Install Graphical Mode and vnc tools
   become: true
   hosts: localhost
   roles:
    - {role: graphical-user}
```
