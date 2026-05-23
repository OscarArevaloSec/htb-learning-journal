# Offense-to-Defense Tool Map

This document connects lab tools to defensive thinking. The goal is not to glorify offensive tooling; the goal is to understand what defenders can observe when these tools are used in authorized environments.

| Tool or Technique | Lab Use | Defensive Evidence |
|---|---|---|
| Nmap | Authorized host and service discovery. | Firewall logs, IDS alerts, unusual connection attempts, service banners requested. |
| Gobuster or directory enumeration | Authorized web content discovery. | Web server logs, repeated 404s, unusual user agent, high request volume. |
| Hydra or password testing | Authorized credential attack simulation. | Failed logins, account lockouts, source IP patterns, authentication alerts. |
| SMB enumeration | Authorized Windows or Samba share review. | SMB connection logs, authentication events, share access logs. |
| Burp Suite | Authorized web request inspection and testing. | Proxy logs, application logs, unusual request patterns. |
| PowerShell | Windows administration and lab testing. | Script block logs, process creation, command-line telemetry. |

## Analyst Note

Understanding attacker behavior helps defenders write better detections, investigate alerts with context, and explain risk clearly.
