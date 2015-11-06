
# Usage

Ubuntu 14.04

```shell
  $ sudo apt-get update
  $ sudo apt-get install ssh
  $ sudo apt-get install ansible
```

```shell

  $ ansible-playbook -K -i inventory playbook.yml

  # If you want to override the user name in the playbook.yml.
  $ ansible-playbook -u <use_name> -K -i inventory playbook.yml
```
