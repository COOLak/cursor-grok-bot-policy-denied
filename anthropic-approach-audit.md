# Anthropic-mirror approach audit and Cursor adaptation

Audit date: **2026-09-05 UTC**  
Reference snapshot: [`COOLak/anthropic-claude-billing-incident` at `58006ec`](https://github.com/COOLak/anthropic-claude-billing-incident/commit/58006eca65f03295166fc2e1013f2a633d1a066c)

## Direct finding on journalist disclosure

The Anthropic mirror does **not** publish a roster of journalists who received the customer's tips, and it does **not** publish a numeric journalist or press-recipient total. Its public incident brief describes only privacy-sanitized media tips to “several relevant outlets.” The full public Git history contains no recipient roster or outreach total.

The mirror does identify Future Stack Reviews after the outlet published an independent document-first analysis. That is a coverage citation, not a disclosure of all recipients or of the individual correspondent.

A private Gmail cross-check found **82 distinct destinations** on Anthropic/Claude messages whose subject included `tip` during the audited July 17-August 22 campaign window. This is a conservative email-endpoint count, **not** a claim that 82 individual journalists received or read the material: the set includes named reporters, newsrooms, tips desks, and consumer-media endpoints. Three inspected threads contain replies from human media correspondents at the Financial Times, Computer Weekly, and Future Stack Reviews. Their addresses and private correspondence remain outside the public mirror.

## Functional parity map

| Anthropic incident function | Cursor adaptation | Status |
| --- | --- | --- |
| Public evidence hub and hosted index | GitHub repository plus GitHub Pages hub | Implemented |
| Concise incident brief | [`incident-brief.md`](incident-brief.md) | Implemented |
| Reporter-ready brief | [`reporter-brief.md`](reporter-brief.md) | Implemented |
| Concrete technical-owner packet | [`owner-action.md`](owner-action.md) | Implemented |
| Reconciliation matrix | [`reconciliation-matrix.md`](reconciliation-matrix.md) | Implemented |
| Evidence chain with proof limits | [`evidence-chain.md`](evidence-chain.md) | Implemented |
| Dated public timeline | [`timeline.md`](timeline.md) | Implemented |
| Public-source matrix | [`public-source-matrix.md`](public-source-matrix.md) | Implemented; no independent comparable-case cluster has been verified |
| Affected-user evidence worksheet | [`affected-user-checklist.md`](affected-user-checklist.md) | Implemented |
| Machine-readable incident and custody records | [`incident-state.json`](incident-state.json) and [`evidence-manifest.json`](evidence-manifest.json) | Implemented |
| Privacy-safe screenshot and share card | [`assets/access-blocked.png`](assets/access-blocked.png) and [`assets/share-card.svg`](assets/share-card.svg) | Implemented |
| Dedicated correction record | [`account-framing-correction.md`](account-framing-correction.md) | Implemented |
| Request-path audit adapted to this failure mode | [`authentication-path-audit.md`](authentication-path-audit.md) | Implemented |
| Cluster analysis adapted to the available vendor routes | [`support-routing-cluster.md`](support-routing-cluster.md) | Implemented |
| Regulator-ready attachment | [`regulator-attachment.pdf`](regulator-attachment.pdf) | Implemented; preparation is not evidence of regulatory submission |
| Public press-distribution record | [`press-outreach-summary.csv`](press-outreach-summary.csv) | Implemented with stronger aggregate disclosure: 48 recipients at 26 outlets |
| Independent document-first coverage | None yet | Open gap; no coverage is implied |
| Vendor-owned public issue tracker and issue burst | No comparable public Cursor Grok Bot tracker was identified | Adapted to private support-route cluster; no public issue burst is invented |
| Transaction ledger, receipt timeline, and payment-processor trace | Not applicable to an access-entitlement failure without disputed transactions | Replaced by authentication-path and support-routing audits |
| Neutral third-party web archives | Not yet captured | Open gap; live official links and repository snapshots are preserved |

## Accuracy rule

“Parity” means the same evidentiary function where the facts support it. It does not mean copying transaction-specific artifacts into an access incident, inventing comparable victims, implying that a draft was filed, or treating outreach as coverage. Open gaps stay labeled until independent evidence exists.

