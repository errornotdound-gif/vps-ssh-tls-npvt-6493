# VPS tunnel configs

## WireGuard (download)
https://github.com/errornotdound-gif/vps-ssh-tls-npvt-6493/raw/main/VPS-WireGuard.conf

Raw:
https://raw.githubusercontent.com/errornotdound-gif/vps-ssh-tls-npvt-6493/main/VPS-WireGuard.conf

### AWS Security Group (required)
EC2 → instance → Security → Security Group → Edit inbound rules → Add:
- Type: **Custom UDP**
- Port: **51820**
- Source: **0.0.0.0/0**
- Save

Without UDP 51820 open: phone shows Active but NO internet (no handshake).
