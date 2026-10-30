# CogniShield (showcase)

> The source code is private while the project is in active development. This repository describes the platform.

AI-powered insider-threat detection. Instead of alerting on every unusual event, CogniShield links related events into attack chains, so analysts see one meaningful alert instead of hundreds of small ones.

**Status:** active R&D.

## How it works
- Collects user-activity events (logins, file access, device use, downloads)
- **Threat-chain detection** across 7 attack patterns, e.g. off-hours login → bulk download → new USB device
- **Real-time alerts** pushed to the analyst dashboard over WebSocket

## Hardening
- Token blacklist for revoked sessions
- Input sanitisation on every endpoint
- Database indexes on hot queries
- Docker deployment

## Documentation
- 33-page SRS following IEEE 830
- Full UML: use case, class, sequence and activity diagrams

## Stack
React · TypeScript · WebSocket · Docker

---
Built by **Bashar Ahmed Abdullah** · [BashX](https://YOUR-DOMAIN) · [Case study](https://YOUR-DOMAIN/#case-studies)
