<h1 align="center">Abdulfattox</h1>

<p align="center"><strong>Industrial systems engineer focused on ERPNext, mobile execution, hardware workflows, and AI-assisted operations.</strong></p>

<p align="center">
  <code>ERPNext</code>
  <code>Rust</code>
  <code>Go</code>
  <code>Flutter</code>
  <code>MariaDB</code>
  <code>Industrial Hardware</code>
  <code>AI Guidance</code>
</p>

> I build operational software where ERPNext is not only a desk system, but the
> center of mobile work, device control, warehouse flow, messaging, and guided
> decision support.

## Engineering Thesis

I am interested in systems that connect business logic with real operators and
real constraints. ERPNext is the core. Mobile is the field interface. Hardware
is part of the workflow. Messaging gives operations a control surface. AI should
explain, guide, and reduce confusion instead of becoming another disconnected
tool.

The goal is not to build isolated apps. The goal is to make business movement
visible, controllable, and easier to execute.

## Current Production Work

My active production work now lives under
[`accord-erp-automation`](https://github.com/accord-erp-automation): a focused
ERPNext automation organization for warehouse, delivery, mobile, scale, Zebra,
and read-optimized ERP services.

| System | Stack | Purpose |
| --- | --- | --- |
| [`accord_mobile_server_rs`](https://github.com/accord-erp-automation/accord_mobile_server_rs) | Rust, Axum, Tokio, SQLx, LMDB | Production mobile backend for ERPNext workflows with direct MariaDB reads, ERPNext REST mutations, FCM push, Gemini Vision, and mobile API compatibility. |
| [`accord_mobile`](https://github.com/accord-erp-automation/accord_mobile) | Flutter, Dart | Mobile app for supplier, customer, Werka, warehouse, delivery, and admin workflows. |
| [`accord_erp_custom_field`](https://github.com/accord-erp-automation/accord_erp_custom_field) | Python, Frappe | ERPNext custom field module for structured bridge-service filtering and communication. |
| [`gscale-platform`](https://github.com/accord-erp-automation/gscale-platform) | Go | Scale, Zebra, Telegram, archive, mobile API, and ERPNext workflow orchestration. |
| [`gscale-erp-read-rs`](https://github.com/accord-erp-automation/gscale-erp-read-rs) | Rust | Read-only ERP catalog service for item and warehouse lookup over ERPNext/MariaDB. |

Current public release:

- [`accord_mobile_server_rs v1.1.0`](https://github.com/accord-erp-automation/accord_mobile_server_rs/releases/tag/v1.1.0)

## System Model

```text
ERPNext
  Documents | permissions | business rules | operational source of truth

Direct Read Models
  MariaDB projections | search | summaries | dashboards | low-latency lookup

Mobile Execution
  Supplier | customer | Werka | admin | delivery | warehouse workflows

Hardware Operations
  Scales | Zebra printers | RFID | scanners | shop-floor devices

Control Surfaces
  Telegram bots | admin tools | notifications | operational feedback loops

AI Assistance
  Image search | explanation | troubleshooting | operator guidance
```

## What I Care About

- ERPNext should remain the source of truth for business mutations.
- Direct database access should be read-only, measured, and contract-safe.
- Mobile workflows should work for real staff, not only technical users.
- Search and filtering should help less technical users, not punish them.
- Hardware integrations should be treated as production systems, not demos.
- Performance claims should come from benchmarks, not assumptions.
- The best interface is the one that needs the least explanation.

## Public Research Lineage

Before the current Accord production organization, I explored the same
operational direction through smaller public projects under this account.

| Domain | Repositories | Role |
| --- | --- | --- |
| ERPNext mobile bridge | [`erpnext-mobile-bridge`](https://github.com/WIKKIwk/erpnext-mobile-bridge), [`erpnext-mobile-client`](https://github.com/WIKKIwk/erpnext-mobile-client), [`erpnext-bridge-fields`](https://github.com/WIKKIwk/erpnext-bridge-fields) | Early mobile execution and bridge-service architecture around ERPNext. |
| Hardware operations | [`zebra-scale-erpnext-core`](https://github.com/WIKKIwk/zebra-scale-erpnext-core), [`rfid-zebra-scale-hybrid-core`](https://github.com/WIKKIwk/rfid-zebra-scale-hybrid-core), [`zebra-rfid-bridge-core`](https://github.com/WIKKIwk/zebra-rfid-bridge-core) | Experiments around Zebra, RFID, weighing, and device-controlled ERP workflows. |
| Messaging systems | [`erpnext-stock-telegram-core`](https://github.com/WIKKIwk/erpnext-stock-telegram-core), [`erpnext-stock-telegram-bot`](https://github.com/WIKKIwk/erpnext-stock-telegram-bot), [`erpnext-assignment-telegram-bot`](https://github.com/WIKKIwk/erpnext-assignment-telegram-bot) | Telegram as an operational interface for stock, assignment, and field feedback. |
| ERPNext modules | [`erpnext-ui-theme-suite`](https://github.com/WIKKIwk/erpnext-ui-theme-suite), [`erpnext-security-suite`](https://github.com/WIKKIwk/erpnext-security-suite), [`erpnext-backup-orchestrator`](https://github.com/WIKKIwk/erpnext-backup-orchestrator) | ERPNext UI, safety, backup, and operational hardening experiments. |
| AI guidance | [`erpnext-guided-ai-assistant`](https://github.com/WIKKIwk/erpnext-guided-ai-assistant), [`erpnext-admin-ai-assistant`](https://github.com/WIKKIwk/erpnext-admin-ai-assistant), [`expert-answer-ai-agent`](https://github.com/WIKKIwk/expert-answer-ai-agent) | AI assistance for explanation, troubleshooting, expert answers, and ERPNext support. |

## Operating Principles

### Keep the business system understandable

ERP software can become heavy quickly. I prefer architecture where each layer
has a clear job: ERPNext owns business truth, services expose faster workflows,
mobile keeps operators focused, and hardware joins the process through explicit
interfaces.

### Optimize only after preserving meaning

A faster system is not useful if it changes business behavior. Read paths can
be optimized aggressively, but only when the result shape and operational
meaning stay the same.

### Build for the least-trained operator in the loop

Industrial software should not assume perfect training. If the least technical
operator can use the flow without confusion, stronger users will move faster
through it naturally.

### Let the work carry the claim

I avoid overstating myself. I would rather show working systems, measured
results, and clear architecture. Criticism is useful when it makes the next
version stronger.

## Direction

| Direction | Intent |
| --- | --- |
| ERPNext-centered operations | Keep ERPNext as the operational core while making the surrounding execution layer faster and easier to use. |
| Mobile-first field work | Move warehouse, delivery, supplier, customer, and admin workflows out of desk-only usage. |
| Hardware-aware workflows | Treat scales, printers, RFID, and scanners as active workflow nodes. |
| AI-assisted operation | Use AI to guide, explain, search, and reduce operator confusion. |
| Productized platform boundaries | Turn prototypes into stable services with clear ownership, release notes, tests, and deployment rules. |

## More

- Organization: [`accord-erp-automation`](https://github.com/accord-erp-automation)
- Profile website: [`abdulfattox-web`](https://github.com/WIKKIwk/abdulfattox-web)
- Personal note: [`ABOUT_ME.md`](./ABOUT_ME.md)
