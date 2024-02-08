# How to Install
Configure the `requirements.yml` file.
```
- name: apiclient
  src: https://github.com/nilsonvieira/ansible-role-apiclient
  version: main
```
In the Roles include:
```
  roles:
    - apiclient
```
Execute the command to install role.

```bash
ansible-galaxy role install -r requirements.yml