# home-lab-infrastructure
## Day 1
- Installed VirtualBox and Ubuntu Server 24.04 LTS
- Created non-root user with sudo access
- Fixed SSH installation (openssh-server wasn't installed by default)
- Connected remotely via SSH from host machine
- Hardened SSH: disabled root login (PermitRootLogin no)
## Day 2
- Installed UFW firewall
- Allowed SSH (port 22) before enabling firewall
- Enabled UFW
- Verified firewall status (port 22/tcp: ALLOW)
## Day 3
- Generated SSH key pair (ed25519) on host machine
- Copied public key to server's authorized_keys
- Verified key-based login works
- Disabled password authentication (PasswordAuthentication no)
## Day 4
- Opened HTTP (80) and HTTPS (443) ports on firewall
- Registered free domain via Duck DNS (behzad-homelab.duckdns.org)
## Clone Repository fro Github
