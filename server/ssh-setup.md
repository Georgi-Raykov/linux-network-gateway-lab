# SSH Setup

## Goal
Passwordless SSH access from clients to server.

## Clients
- PIRIN → RILA
- VITOSHA → RILA

## Method
- Key type: ed25519
- Authentication: public key
- Authorized keys stored on RILA

## Result
Clients can connect without password:
ssh linuxlabs@192.168.50.101
