# VPS WireGuard

Download: https://github.com/errornotdound-gif/vps-ssh-tls-npvt-6493/raw/main/VPS-WireGuard.conf

## Important (AWS)
In EC2 → Security Group of the instance, add inbound rule:
- Type: Custom UDP
- Port: 51820
- Source: 0.0.0.0/0

Without this rule the phone shows Connected but there is NO Internet (no handshake).
