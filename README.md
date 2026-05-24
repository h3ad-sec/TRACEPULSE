# TRACEPULSE

**Threat Query Packs — Part of [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/)**

TRACEPULSE delivers threat-specific query packs tied to active campaigns, threat actors, and CVEs. Queries are sourced from the [QUERYVAULT](https://github.com/h3ad-sec/QUERYVAULT) data repository.

## Features

- Query packs tied to specific threats, campaigns, and CVEs
- Supports KQL (Microsoft Sentinel / Defender), Sigma, and XQL (Cortex XDR)
- Filter by platform (KQL / Sigma / XQL)
- Search by title, description, threat actor, or CVE
- CVE badge displayed per relevant query
- Lazy-loaded query content — manifest loads on start, full query loads on view
- One-click copy to clipboard
- Fully responsive — works on mobile, tablet, and desktop

## Query Structure

Each pulse entry includes:
- Title
- Linked threat actor or campaign (optional)
- CVE reference (optional)
- Date
- Platform-specific query

## Data Source

Queries live in [QUERYVAULT](https://github.com/h3ad-sec/QUERYVAULT) under `pulse/2025/`. TRACEPULSE reads from the manifest at load time.

## Live Tool

[h3ad-sec.github.io/TRACEPULSE](https://h3ad-sec.github.io/TRACEPULSE/)

## Part of H3AD-SEC

TRACEPULSE is a sub-tool under [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/), the threat hunting hub of the [H3AD-SEC](https://h3ad-sec.github.io) platform.


## H3AD-SEC Platform Modules

| Module | Tools |
|--------|-------|
| [H3AD-X](https://h3ad-sec.github.io/H3AD-X/) | X-VERDIKT, PARSE-X, DNSCOPE |
| [H3AD-AI](https://h3ad-sec.github.io/H3AD-AI/) | INSIGHT-AI, QUERYCRAFT-AI, FPLENS-AI, ATTMAP-AI, CHRONO-AI, MALBRIEF-AI |
| [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/) | TRACERULES |
| [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/) | HYPOS, PIVEX, TRACEPULSE |
| [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/) | QUICKTRACE, SHIFTLOG, PHISHOPS |
| [H3AD-DF](https://h3ad-sec.github.io/H3AD-DF/) | REGSCOPE |
| [H3AD-IR](https://h3ad-sec.github.io/H3AD-IR/) | — |
