# Daniël van Ginneken

Backend and infrastructure engineer based in the Netherlands.  
I build distributed systems, backend APIs, and the infrastructure they run on.

---

Working part-time as a System Support Engineer at [Dentech](https://dentech.nl) while studying Computer Science at Avans University of Applied Sciences. My background spans both infrastructure (Linux, Proxmox, Cisco, VLANs) and backend engineering (ASP.NET Core, PostgreSQL, RabbitMQ) — I think about systems at every layer, from network topology to application design.

**Current engineering interests:** event-driven architectures · distributed systems · observability · backend API design · infrastructure automation · cloud-native systems

---

## Projects

### [PatientPingeling](https://github.com/DanielvG-IT/PatientPingeling)
*Multi-tenant notification platform — ASP.NET Core · RabbitMQ · PostgreSQL · OpenTelemetry*

Event-driven notification dispatch system that routes messages across multiple providers (email, SMS, push). Designed around clean architecture with per-tenant configuration, asynchronous message processing via RabbitMQ, full OpenTelemetry instrumentation for distributed tracing and metrics, and provider abstraction through the factory pattern. Deployed via Docker Compose.

### Homelab
*Self-hosted infrastructure — Proxmox · Linux · Docker · VLANs · Monitoring*

Personal infrastructure stack: Proxmox cluster, VLAN-segmented network with inter-VLAN routing, containerized self-hosted services, centralized monitoring, and automation scripts. Mirrors the production infrastructure patterns I work with daily.

---

## Stack

```
Backend        C# / .NET, ASP.NET Core, Entity Framework Core
Messaging      RabbitMQ
Databases      PostgreSQL, SQL Server
Frontend       React, TypeScript
Observability  OpenTelemetry, structured logging, distributed tracing
Infra          Linux, Proxmox, Docker, Cisco IOS
Networking     VLANs, routing, firewalls, DNS/DHCP
Automation     PowerShell, Bash
```

---

[LinkedIn](https://www.linkedin.com/in/daniel-vginneken) · [Website](https://danielvanginneken.nl) · [daniel@danielvanginneken.nl](mailto:daniel@danielvanginneken.nl)
