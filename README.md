# Ansible Role: jellyfin

Install Jellyfin media server using upstream packages from the Jellyfin repositories.

## Requirements

None.

## Role Variables

See the role [vars](vars/main.yml)

## Example Playbook

```yaml
- hosts: jellyfin
  roles:
    - role: bleetube.jellyfin
      become: true
```