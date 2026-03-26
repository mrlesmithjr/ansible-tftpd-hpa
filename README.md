> [!CAUTION]
> **This project is archived and no longer maintained.**
> Archived: 2026-03-26
> Reason: Low community usage; no longer maintained# ansible-tftpd-hpa

An [Ansible](https://www.ansible.com) role to install/configure `tftpd-hpa`.

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
---
- hosts: tftp_servers
  become: true
  vars:
  roles:
    - role: ansible-tftpd-hpa
  tasks:
```

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- [EverythingShouldBeVirtual](http://www.everythingshouldbevirtual.com)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)