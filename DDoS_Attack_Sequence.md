```mermaid
sequenceDiagram
  participant Attacker
  participant BotNet
  participant WebServer
  participant Firewall
  participant Packet Analysis
  participant Packets Denied
  participant Packets Allowed
  actor Trusted User
  Attacker->>BotNet: Distribute Denial of Service Attack on SomeWebsite.com
  BotNet->>Firewall: BotNet commands army of computers to request connection to SomeWEbsite.com
  Firewall->>Packets Denied
  Firewall->>Packets Allowed

```
