<h1 align="center">Abdulfattox</h1>

<p align="center"><strong>Industrial systems engineer focused on software that runs real operations.</strong></p>

<p align="center"><code>ERPNext</code> <code>Mobile Bridge</code> <code>RFID</code> <code>Zebra</code> <code>Telegram Ops</code> <code>AI Assistants</code></p>

> I build operational software around ERPNext, industrial hardware, mobile workflows, and guided AI systems.

## System Topology

```text
ERPNext
  |
  +-- erpnext-mobile-bridge ------> erpnext-mobile-client
  |
  +-- erpnext-bridge-fields ------> external bridge actions
  |
  +-- zebra-scale-erpnext-core ---> Zebra / scale workflows
  |
  +-- rfid-zebra-scale-hybrid-core -> RFID / Zebra / scale orchestration
  |
  +-- erpnext-admin-ai-assistant --> guided operator support
```

## Operating Surface

| Track | Primary Systems | Purpose |
| --- | --- | --- |
| Mobile | [`erpnext-mobile-bridge`](https://github.com/WIKKIwk/erpnext-mobile-bridge), [`erpnext-mobile-client`](https://github.com/WIKKIwk/erpnext-mobile-client), [`erpnext-bridge-fields`](https://github.com/WIKKIwk/erpnext-bridge-fields) | Connect ERPNext to mobile execution and bridge-driven operations. |
| Hardware | [`zebra-scale-erpnext-core`](https://github.com/WIKKIwk/zebra-scale-erpnext-core), [`rfid-zebra-scale-hybrid-core`](https://github.com/WIKKIwk/rfid-zebra-scale-hybrid-core), [`zebra-rfid-bridge-core`](https://github.com/WIKKIwk/zebra-rfid-bridge-core) | Run printer, RFID, and scale devices inside ERP workflows. |
| ERPNext Modules | [`erpnext-ui-theme-suite`](https://github.com/WIKKIwk/erpnext-ui-theme-suite), [`erpnext-security-suite`](https://github.com/WIKKIwk/erpnext-security-suite), [`erpnext-admin-ai-assistant`](https://github.com/WIKKIwk/erpnext-admin-ai-assistant) | Extend ERPNext with UI, protection, and guided operations. |
| AI Systems | [`erpnext-guided-ai-assistant`](https://github.com/WIKKIwk/erpnext-guided-ai-assistant), [`expert-answer-ai-agent`](https://github.com/WIKKIwk/expert-answer-ai-agent), [`persona-companion-agent`](https://github.com/WIKKIwk/persona-companion-agent) | Build context-aware assistants for support, response, and workflow intelligence. |

## Selected Systems

| Repository | Brief |
| --- | --- |
| [`erpnext-mobile-bridge`](https://github.com/WIKKIwk/erpnext-mobile-bridge) | Bridge service connecting ERPNext with mobile clients and operational workflows. |
| [`erpnext-mobile-client`](https://github.com/WIKKIwk/erpnext-mobile-client) | Flutter client for warehouse, delivery, and admin execution. |
| [`erpnext-guided-ai-assistant`](https://github.com/WIKKIwk/erpnext-guided-ai-assistant) | Guided AI assistant for ERPNext training, troubleshooting, and contextual help. |
| [`zebra-scale-erpnext-core`](https://github.com/WIKKIwk/zebra-scale-erpnext-core) | Go-based Zebra printer and scale integration core for ERPNext operations. |
| [`rfid-zebra-scale-hybrid-core`](https://github.com/WIKKIwk/rfid-zebra-scale-hybrid-core) | Hybrid RFID, Zebra, and scale core for multi-device industrial workflows. |
| [`erpnext-admin-ai-assistant`](https://github.com/WIKKIwk/erpnext-admin-ai-assistant) | Admin-only AI assistant for ERPNext operations and guided troubleshooting. |

## Repository Index

<details>
<summary><strong>Mobile Stack</strong></summary>

- [`erpnext-mobile-bridge`](https://github.com/WIKKIwk/erpnext-mobile-bridge)
- [`erpnext-mobile-client`](https://github.com/WIKKIwk/erpnext-mobile-client)
- [`erpnext-bridge-fields`](https://github.com/WIKKIwk/erpnext-bridge-fields)
- [`erpnext-bot-bootstrap`](https://github.com/WIKKIwk/erpnext-bot-bootstrap)

</details>

<details>
<summary><strong>Hardware Operations</strong></summary>

- [`zebra-scale-erpnext-core`](https://github.com/WIKKIwk/zebra-scale-erpnext-core)
- [`rfid-zebra-scale-hybrid-core`](https://github.com/WIKKIwk/rfid-zebra-scale-hybrid-core)
- [`uhf-rfid-java-cli`](https://github.com/WIKKIwk/uhf-rfid-java-cli)
- [`zebra-rfid-bridge-core`](https://github.com/WIKKIwk/zebra-rfid-bridge-core)
- [`printer-scanner-telegram-core`](https://github.com/WIKKIwk/printer-scanner-telegram-core)
- [`industrial-scale-simulator`](https://github.com/WIKKIwk/industrial-scale-simulator)

</details>

<details>
<summary><strong>ERPNext Modules</strong></summary>

- [`erpnext-ui-theme-suite`](https://github.com/WIKKIwk/erpnext-ui-theme-suite)
- [`erpnext-security-suite`](https://github.com/WIKKIwk/erpnext-security-suite)
- [`erpnext-admin-ai-assistant`](https://github.com/WIKKIwk/erpnext-admin-ai-assistant)
- [`erpnext-guided-ai-assistant`](https://github.com/WIKKIwk/erpnext-guided-ai-assistant)

</details>

<details>
<summary><strong>Web And AI Products</strong></summary>

- [`abdulfattox-web`](https://github.com/WIKKIwk/abdulfattox-web)
- [`commerce-web-platform`](https://github.com/WIKKIwk/commerce-web-platform)
- [`ai-sheets-platform`](https://github.com/WIKKIwk/ai-sheets-platform)
- [`expert-answer-ai-agent`](https://github.com/WIKKIwk/expert-answer-ai-agent)
- [`persona-companion-agent`](https://github.com/WIKKIwk/persona-companion-agent)

</details>

## Current Direction

I am building a focused product ecosystem around ERPNext, industrial hardware, Telegram automation, and AI-driven operator workflows.
