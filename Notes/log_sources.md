# 📜 Log Sources Reference

Understanding where to collect logs is crucial for SOC effectiveness.

## 🖥️ Host-based Logs

| Source         | Type                  | Description                            |
|----------------|-----------------------|----------------------------------------|
| Sysmon         | Event Logs            | Detailed process creation, network, registry |
| Windows Logs   | Security, System, App | Authentication, privilege use, crashes |
| AuditD         | Linux Audit Framework | System calls, file access, policy events |

## 🌐 Network Logs

| Source         | Type                  | Description                            |
|----------------|-----------------------|----------------------------------------|
| Suricata       | IDS/IPS Alerts        | Network threat detection & PCAP        |
| Firewall       | Allow/Deny Logs       | Perimeter monitoring and traffic flow  |
| Proxy Logs     | Web Access Logs       | User internet activity                 |

## 🔑 Authentication Logs

| Source         | Description                                |
|----------------|--------------------------------------------|
| AD Security    | User logons, password changes, Kerberos    |
| VPN            | Connection attempts, source IPs, durations|

