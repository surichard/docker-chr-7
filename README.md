# Mikrotik RouterOS (Cloud Hosted Router only) in Docker

Blank deployment, no software license provided

## docker-chr-7
Only native virtualization, Cloud Hosted Router, is a new approach specifically made for Virtual Machines both locally and in the cloud

[![Badge](https://img.shields.io/badge/CHR-7.2.3-green)](https://mikrotik.com/download#chr)

```dockerfile
ADD ["your-scripts.sh", "/"]
RUN /your-scripts.sh
```


## List of exposed ports

| Description | Ports |
|-------------|-------|
| Defaults    | 21, 22, 23, 80, 8291, 8728, 8729 |
| IPSec       | 50, 51, 500/udp, 4500/udp |
| OpenVPN     | 1194/tcp, 1194/udp |
| L2TP        | 1701 |
| PPTP        | 1723 |
| SNMP        | 161 161/udp |
| SpeedTest   | 2000 2000/udp |
| Radius      | 1812/udp 1813/udp |
