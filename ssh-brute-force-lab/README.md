# SSH Brute Force Detection Lab

## Objective

Simulate failed SSH login attempts and analyze Linux authentication logs.

## Environment

- Kali Linux
- Ubuntu Server
- VirtualBox

## Commands Used

```bash
sudo journalctl -u ssh
```

```bash
grep "Failed password" /var/log/auth.log
```

