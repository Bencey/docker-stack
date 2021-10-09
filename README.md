# Network IPAM Configuration


| Network        | Subnet         |
|----------------|----------------|
| Traefik        | 172.16.200.0/24   |
| Portainer      | 172.16.13.0/24  |
| Duplicati      | 172.16.55.0/24  |



# Docker Node Information

All docker nodes are running as virtual machines with the following specs


Ubuntu 20.04 Server
10GB RAM
20 Processors each (10 processors x 2 sockets)
50GB Storage


| Hostname     | IP            |
|--------------|---------------|
| Node1        | 192.168.2.10  |
| Node2        | 192.168.2.11  |
| Node3        | 192.168.2.12  |
| Node4        | 192.168.2.13  |
| Node5        | 192.168.2.14  |
| Node6        | 192.168.2.15  |





# Services currently running

Docker Services

- Authelia
- Duplicati
- Docker container cleanup
- Bitwarden
- Uptime Kuma
- Portainer
- Traefik (Version 2)
> phpmyadmin + mysql

Non Docker Services

- Grafana
- Proxmox
- Pihole



