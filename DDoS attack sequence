# DDoS Attack Sequence

```mermaid
sequenceDiagram
    participant Attacker
    participant BotNet
    participant WebServer
    participant Firewall
Attacker->>BotNet: repeatedly request access to this WebServer
BotNet-->>WebServer: I need access
WebServer-->>Firewall: Is it ok to give access and resources to this client?
Firewall-->>WebServer: Here have some
WebServer-->>BotNet: Granted access 
BotNet-->>WebServer: I need more access
WebServer-->>Firewall: More please
Firewall-->>WebServer: Overloaded. All requests denied.
WebServer-->>BotNet: Request denied.
BotNet-->>Attacker: Attack Successful :D

```
