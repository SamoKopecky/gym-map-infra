# About

Gym map infra setup

## Ansible

To run ansible

```bash
ansible-playbook site.yml --ask-vault-pass
```

TODO:

- add cron to certbot
- backups
- hide kc admin behind vpn

## Firewall

Docker allows exposed porst

- 80
- 443
- 10.0.0.1:3000

UFW handles other blocking/allowing like ssh and wireguard
