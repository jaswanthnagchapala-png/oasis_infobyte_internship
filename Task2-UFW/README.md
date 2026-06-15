# Task 2 - UFW Firewall Configuration

## Objective

Configure and manage firewall rules using UFW (Uncomplicated Firewall) in Kali Linux.

## Tool Used

- UFW (Uncomplicated Firewall)
- Kali Linux

## Commands Executed

### Enable Firewall

```bash
sudo ufw enable
```

### Allow SSH Connections

```bash
sudo ufw allow ssh
```

### View Firewall Rules

```bash
sudo ufw status numbered
```

## Results

- Firewall was enabled successfully.
- SSH access was allowed through port 22.
- Firewall rules were verified using numbered status output.

## Screenshots

See screenshots in the Pictures folder.

## Conclusion

UFW was successfully configured and verified. The firewall is active and SSH access is permitted according to the configured rules.
