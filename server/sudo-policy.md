# Sudo Policy

## admin
Full sudo access via wheel group.

## netops
Allowed:
- ip
- firewall-cmd
- systemctl (network services only)

## readonly
Allowed:
- journalctl
- cat
- ip (read-only usage)

## Goal
Implement role-based access control on RILA server.
