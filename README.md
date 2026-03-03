# Monitoring Mission 

Server monitoring project using **Prometheus & Grafana** on VirtualBox.

## Architecture
| Server | Role | Tools |
|--------|------|-------|
| Client (Ubuntu 20) | Target Server | Node Exporter |
| NFS Server (Ubuntu 20) | Monitoring Server | Prometheus + Grafana |

## What's Monitored
- CPU usage
- Memory usage
- Disk usage

## Ports
| Service | Port |
|---------|------|
| Node Exporter | 9100 |
| Prometheus | 9090 |
| Grafana | 3000 |
