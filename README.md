<div align="center">

# Ameen Ali

### Software Developer · Business Applications · SaaS Platforms

Designing and shipping business software for Arabic-speaking users: mobile field apps, ERP platforms, and the subscription, permission and integration layers that connect them.

[![Organization](https://img.shields.io/badge/Smart%20Choice%20IQ-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Smart-Choice-IQ)
[![Profile](https://img.shields.io/badge/GitHub-AMN--2-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AMN-2)

</div>

---

## About

I build systems that have to be correct in the field: apps used by representatives on the move, ERP sites that carry the accounting, and the access-control and subscription layers that decide who may do what, and when.

**Current project:** **Midan (ميدان)**, a Flutter field-sales application. It covers customers, point of sale, leads with an activity timeline, sample operations, goods exchange, and server-enforced permissions.

## What I deliver

| Area | Scope |
|---|---|
| **Mobile apps** | Arabic right-to-left interfaces, state management, offline-tolerant workflows |
| **ERP platforms** | Custom Frappe / ERPNext apps, versioned server APIs, multi-company configuration |
| **SaaS & entitlements** | Central Control Plane, subscription plans, grace periods, per-customer feature grants |
| **Servers** | SSH administration, Frappe bench deployments, environment setup and configuration |
| **Access control** | Server-enforced permissions with matching client-side checks and policy tests |

## System analysis

How I approach a system before writing code:

1. **Contract first.** I write the integration contract (requests, responses, error codes, idempotency rules) and agree it with the other side before building against it.
2. **Permission matrix.** Every action is mapped to the rule that allows it, including parent and child dependencies, so no path opens by accident.
3. **Failure modes.** I work through partial failures, retries, offline use and concurrent changes, and design so that a retry never duplicates a business document.
4. **Decisions on record.** Accounting, data and access decisions are written down, with the reasons and the people who approved them.
5. **Tested rules.** Each permission and business rule has a test; the full suite and static analysis run on every change.

## Technology stack

**Mobile & client**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![GetX](https://img.shields.io/badge/GetX-8A2BE2?style=flat-square&logoColor=white)
![Dio](https://img.shields.io/badge/Dio-0C6AB5?style=flat-square&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white)

**Backend & data**

![Frappe](https://img.shields.io/badge/Frappe-0089FF?style=flat-square&logoColor=white)
![ERPNext](https://img.shields.io/badge/ERPNext-0089FF?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

**Servers & delivery**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)

**AI-assisted engineering**

![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logoColor=white)

I use AI coding assistants in day-to-day development: to draft and review code, write tests, and check documentation against the implementation. Decisions and their verification stay with me.

## Engineering practices

- Conventional commits with one logical change per commit, and clean history on every feature branch.
- Clean Architecture separation between screens, controllers, services and domain rules.
- Idempotent write operations with request identifiers.
- Documentation-first integration: contracts are written before the client is built against them.

## Contact

Reach out through GitHub: [@AMN-2](https://github.com/AMN-2).
