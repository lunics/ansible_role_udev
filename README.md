# Ansible role: UDEV

Role to manage udev rules.

## Usage
Override [defaults](https://github.com/lunics/ansible_role_udev/blob/master/defaults/main.yml)
```yaml
udev_rules:
  - name:        file_name.rules        # file_name.rules must be a template in inventory/files/udev/file_name.rules
    env_product: "1020/406"
    path_script: /path/script.sh
```
