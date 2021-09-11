**DEPRECATED** in favor of [ansible-role-packages](https://github.com/Allaman/ansible-role-packages)

# ansible-role-gui

Configure specific settings and applications that usually requires a running display server.

## Requirements

- sudo permissions

## Role Variables

No variables

## Dependencies

- ansible-role-basic

## Example Playbook

```
---
- name: Playbook
  hosts: localhost
  connection: local
  roles:
    - ansible-role-gui
```

## License

MIT
