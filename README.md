# ageres210784/vmagent

An Ansible role which installs and configures [vmagent] on Linux

## Requirements

Ansible 2.8+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure prometheus_alertmanager DB
  hosts: vmagents
  remote_user: root

  roles:
    - ageres210784.vmagent
```

## License

Apache 2.0

## Author Information

This role was created by [Sergey Evseev].
