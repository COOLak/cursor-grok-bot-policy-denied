# SuperGrok Heavy / Cursor Grok Bot `policy_denied` incident

> **September 11 support correction:** Cursor now says different emails can link and attributes this case to a .ru domain restriction. No fix or X-sign-in email-change procedure has been verified. [Read the correction and September 12 follow-up](support-correction-20260911.html). Earlier statements and downloadable packets are historical snapshots.

## Historical support response — September 10, 20:57 UTC (superseded September 11)

[Cursor has replied, but no working usage-grant path has been verified](support-response-20260910.html). The response rejects linking the different-email account and says the matching login cannot be created from this ticket. This does not confirm a blanket domain ban. One factual clarification was sent in the original case.

This repository is a privacy-sanitized public evidence hub for an unresolved paid-feature access failure involving xAI's SuperGrok Heavy subscription and Cursor's Grok Bot linking flow.

## Latest evidence — September 9

[Matching-email password signup also fails; bot-context limitation and original checksum](mobile-signup-20260909.html). The customer reports never having had a Cursor account under that matching address. No confirmed domain-policy finding or restored access.

## Start here

- **[Open the public incident page](https://coolak.github.io/cursor-grok-bot-policy-denied/)**
- **[Read the public incident brief](https://coolak.github.io/cursor-grok-bot-policy-denied/incident-brief.html)**
- **[Open the reporter-ready brief](https://coolak.github.io/cursor-grok-bot-policy-denied/reporter-brief.html)**
- **[Give the technical owner this action packet](https://coolak.github.io/cursor-grok-bot-policy-denied/owner-action.html)**
- **[Inspect the system reconciliation matrix](https://coolak.github.io/cursor-grok-bot-policy-denied/reconciliation-matrix.html)**
- **[Audit the evidence chain and proof boundaries](https://coolak.github.io/cursor-grok-bot-policy-denied/evidence-chain.html)**
- **[Inspect the public-source matrix](https://coolak.github.io/cursor-grok-bot-policy-denied/public-source-matrix.html)**
- **[Inspect neutral first-party archive preservation](https://coolak.github.io/cursor-grok-bot-policy-denied/archive-preservation.html)**
- **[Audit the authentication path](https://coolak.github.io/cursor-grok-bot-policy-denied/authentication-path-audit.html)**
- **[Inspect the Cursor/xAI support-routing cluster](https://coolak.github.io/cursor-grok-bot-policy-denied/support-routing-cluster.html)**
- **[Read the account-framing correction](https://coolak.github.io/cursor-grok-bot-policy-denied/account-framing-correction.html)**
- **[Review the Anthropic-approach parity audit](https://coolak.github.io/cursor-grok-bot-policy-denied/anthropic-approach-audit.html)**
- **[Download the regulator-ready attachment](https://coolak.github.io/cursor-grok-bot-policy-denied/regulator-attachment.pdf)**
- **[Inspect the dated public timeline](https://coolak.github.io/cursor-grok-bot-policy-denied/timeline.html)**
- **[Review the press-outreach record](https://coolak.github.io/cursor-grok-bot-policy-denied/press-outreach.html)**
- **[Use the affected-user evidence checklist](https://coolak.github.io/cursor-grok-bot-policy-denied/affected-user-checklist.html)**
- **[Inspect the machine-readable state](incident-state.json)**

## Short summary

The customer has a paid SuperGrok Heavy subscription attached to an X-authenticated identity whose valid email address ends in `.ru`. xAI publicly states that Grok Bot is included with SuperGrok Heavy.

The customer followed Cursor's **Get access with SuperGrok Heavy** path. X authorization succeeded, but Cursor's callback returned `policy_denied` and the Grok Bot sign-in page displayed **“Access blocked, please contact support.”**

Cursor support later stated that the SuperGrok and Cursor account email addresses must match and that a successful link is permanent and cannot be moved. The customer does **not** require the benefit on the pre-existing non-`.ru` Cursor account: creation of a new personal Cursor account using the matching `.ru` address is acceptable. That matching-address path is the path that remains blocked.

The evidence is therefore consistent with an unpublished domain-level eligibility rule or implementation block. Cursor has not confirmed that inference, identified the backend policy, supplied a working matching-address route, or provided a documented remedy.

## Reproducible failure

1. Start from Grok Bot's plan screen.
2. Choose **Get access with SuperGrok Heavy**.
3. Continue to xAI/X authorization.
4. Authorize Cursor to verify identity and read the account email.
5. The browser returns to Cursor's bot-auth callback with `error=policy_denied`.
6. Grok Bot shows **“Access blocked, please contact support.”**
7. The paid Grok Bot entitlement is not activated.

The failure was reproduced after creating fresh authorization sessions, disabling ordinary proxy/VPN variables, and after Cursor support said it had refreshed relevant backend settings.

![Grok Bot access-blocked page](assets/access-blocked.png)

## What the vendors have said

- Cursor's automated support said the pre-existing Cursor account was an individual account, not a team or enterprise account.
- Cursor asked for a retry without VPN/proxy interference, screenshots, subscription type, and the X/Grok account email. Those requests were satisfied.
- A Cursor billing-support representative said backend settings had been refreshed and requested another retry. The same error returned.
- Cursor then stated that the SuperGrok and Cursor emails must match and that successful links cannot be undone or moved.
- A later Cursor representative forwarded the case to the Grok Bot technical team, but supplied no owner, backend finding, remedy, or ETA.
- xAI support routed the issue back to Cursor, saying Cursor owns Grok Bot support.
- Cursor's automated support immediately closed that transferred request as a duplicate of the original still-unresolved case.

The private correspondence is summarized rather than reproduced because it contains personal account identifiers, authentication metadata, and private support-routing details.

## Public evidence

- xAI announcement: [Grok Bot is now included with more plans](https://x.ai/news/grok-bot-more-plans)
- Cursor linking guide: [Link SuperGrok for Grok Bot](https://cursor.com/help/grok-bot/supergrok)
- Neutral captures: [Cursor linking guide](https://web.archive.org/web/20260905003207/https://cursor.com/help/grok-bot/supergrok) and [xAI Grok Bot FAQ](https://web.archive.org/web/20260905003334/https://docs.x.ai/grok-bot/faq)
- Reddit evidence thread: [SuperGrok Heavy Grok Bot: matching `.ru` email gets `policy_denied`](https://www.reddit.com/r/cursor/comments/1w6p3gi/supergrok_heavy_grok_bot_matching_ru_email_gets/)
- X incident thread: [initial public report](https://x.com/Coolak777/status/2095666718429589769)
- X correction: [matching-account clarification](https://x.com/Coolak777/status/2095666806040236440)
- X Reddit amplifier: [public evidence link](https://x.com/Coolak777/status/2095671328988856616)
- Public error screenshot: [`assets/access-blocked.png`](assets/access-blocked.png)
- Evidence hashes and custody notes: [`evidence-manifest.json`](evidence-manifest.json)

## Why this matters

This is not merely a generic login failure. It combines:

- an advertised benefit of a paid AI subscription;
- a successful identity-provider authorization followed by a partner-side `policy_denied` response;
- an irreversible one-to-one linking rule;
- an apparent account-domain restriction that has not been publicly documented or confirmed;
- two vendors redirecting responsibility while the benefit remains unavailable; and
- no safe, supported workaround for a customer willing to create the required matching account.

The repository does not claim that a particular law, sanctions rule, or discriminatory policy has been violated. It documents an unresolved consumer-entitlement and platform-governance question and asks the vendors to identify the actual rule and remedy.

## Correction to the original account framing

Early support messages treated the pre-existing non-`.ru` Cursor account as the desired target. That is no longer the customer's requirement.

The corrected requirement is:

- a new personal Cursor account using the X/SuperGrok identity's matching `.ru` address is acceptable;
- the customer authorizes that route if Cursor supports it;
- no irreversible Grok link should be completed until the target account is visibly confirmed; and
- the unresolved problem is the inability to complete the matching-`.ru` account path.

This correction was sent to Cursor in writing on September 3, 2026.

## Current status

**Unresolved as of 2026-09-10 21:21 UTC.**

- Grok Bot access has not been verified working.
- Cursor has not confirmed the precise backend reason for `policy_denied`.
- Cursor has not supplied a supported matching-`.ru` signup/linking path.
- Cursor's public linking guide confirms individual SuperGrok Heavy eligibility, a grant without a paid Cursor-plan prerequisite, permanent linking, and support routing, but publishes no same-email requirement or `.ru`-domain exclusion.
- No human technical owner or firm remediation ETA has been provided.
- Cursor's promised response window expired; a one-time follow-up at 2026-09-04 23:52 UTC demanded a named owner, exact rule, supported matching-`.ru` path, firm ETA, or billing remedy.
- Public posts are live. At the September 11 public check, Reddit showed 3.3K views and one substantive community reply; X showed 43 views and one external automated Grok routing reply. Neither reply is treated as a vendor resolution or technical finding.
- A staged press campaign has 76 counted Sent-verified destinations at 49 outlets. One failed address is excluded from those totals.
- One human journalist replied with a public essay objecting to AI-written pitches. That is an outreach-method objection, not coverage or technical corroboration. On September 9, outreach resumed with individually researched notes explicitly disclosing AI assistance; the correspondent who objected was not contacted again.
- The earlier 48 received the historical hub, reporter brief and timeline. The September 9 signup evidence page has been dispatched to 26 counted destinations: 21 new contacts across batches six through nine, plus five eligible earlier recipients. One earlier failed address is excluded. Of the original 48, one is excluded following an objection and 42 remain eligible for a staged addendum. Sent records establish dispatch, not inbox delivery or readership.
- On September 5, material snapshot `38bfe8c` was sent individually to all 48 then-current press recipients; marker verification found 48 distinct destinations and no immediate delivery failure.
- At 05:55 UTC on September 9, a local consumer-affairs office in Japan replied that it cannot negotiate with overseas sellers over directly purchased digital services. It referred the customer to the National Consumer Affairs Center's Cross-border Consumer Center Japan (CCJ) from September 14. This is a routing response, not complaint acceptance, a finding against either vendor, or a remedy.
- Monitoring and evidence preservation continue every six hours.

## Media-outreach record

Current total: **76 counted Sent-verified destinations at 49 outlets**. The dated paragraphs below preserve earlier checkpoints. New outlets in batch ten: Fortune, The Guardian, Observer and Semafor.

The Anthropic incident mirror did **not** publish a journalist roster or a numeric press-recipient total. Its public incident brief says only that privacy-sanitized tips went to “several relevant outlets.” It names Future Stack Reviews only after independent coverage appeared, not as a campaign roster. The full finding and private-mail cross-check are documented in the [`anthropic-approach-audit`](anthropic-approach-audit.md).

This mirror keeps individual names, addresses, and correspondence private while making the aggregate campaign materially more explicit.

As of September 10, 2026, 15:15 UTC, **69 counted Sent-verified destinations at 43 outlets** have been contacted. Batch nine sent five separate, tailored notes on September 10 at 15:14 UTC: four named reporters and one tips desk, across five outlets including two new outlets. Exact recipients, subjects, bodies and Sent labels were verified; no immediate failure was found. Total: 69 counted destinations at 43 outlets; one earlier failed address remains excluded. The September 9 signup evidence page has been dispatched to 26 counted destinations: 21 new contacts across batches six through nine, plus five eligible earlier recipients. One earlier failed address is excluded. Of the original 48, one is excluded following an objection and 42 remain eligible for a staged addendum. Sent records establish dispatch, not inbox delivery or readership. The earlier 48 received historical snapshot `38bfe8c` on September 5. Counts include desks and individuals:

- 404 Media — 4
- ABC News — 1
- Ars Technica — 3
- Axios — 1
- BleepingComputer — 4
- Bloomberg — 1
- Business Insider — 1
- CNBC — 2
- Computerworld — 4
- CyberScoop — 1
- Engadget — 3
- Fast Company — 1
- Forbes — 2
- Futurism — 1
- Gizmodo — 1
- Mother Jones — 1
- Platformer — 1
- Rest of World — 1
- Reuters — 1
- Slate — 1
- Tech Policy Press — 1
- TechCrunch — 2
- TechRadar — 1
- TechSpot — 1
- The Atlantic — 1
- The Register — 5
- The Verge — 2
- The Washington Post — 1
- Tom's Hardware — 1
- VentureBeat — 1
- How-To Geek — 1
- The Decoder — 1
- The Deep View — 1
- Windows Central — 1
- Windows Latest — 1
- WIRED — 6
- Android Authority — 1
- Digital Trends — 1
- Laptop Mag — 1
- PCWorld — 1
- PiunikaWeb — 1
- The Information — 1
- Tom's Guide — 1

One permanent delivery failure was recorded and excluded from the totals. The published editorial desk for that outlet was contacted once as a replacement; no second counted destination was added for the failed address. Exact recipient names and addresses remain private; the public-safe outlet ledger is [`press-outreach-summary.csv`](press-outreach-summary.csv).

## Anthropic-approach audit and functional parity

The earlier claim of full structural parity was too broad. The 2026-09-05 audit now maps every material Anthropic incident function to an implemented Cursor artifact, a fact-specific adaptation, or an explicitly open gap. See [`anthropic-approach-audit.md`](anthropic-approach-audit.md).

The implemented common layers include:

- a concise public incident brief;
- a dedicated reporter brief;
- a concrete owner-action packet;
- a symptom-to-system reconciliation matrix;
- an evidence chain with explicit proof limitations;
- a source matrix that separates first-party, private authenticated, and public-discussion evidence;
- a public timeline and outreach record;
- an affected-user checklist for comparable reports;
- machine-readable state and evidence custody records; and
- an indexable GitHub Pages site with canonical, Open Graph, Twitter-card, and structured metadata;
- a dedicated account-framing correction;
- an authentication-path audit;
- a support-routing cluster; and
- a regulator-ready PDF that is expressly not represented as filed; and
- neutral, time-stamped preservation of material first-party eligibility and linking terms.

No independent coverage, comparable-victim cluster, or vendor-owned public issue burst is invented. Transaction-ledger artifacts from the billing incident are not copied into this access incident; their evidentiary function is served by the authentication-path and support-routing audits.

## What would count as resolution

At least one of the following, verified in the live product:

1. Cursor permits creation/use of a new personal account with the matching `.ru` address and the SuperGrok Heavy entitlement links successfully.
2. Cursor or xAI supplies another supported linking method that preserves the paid entitlement and avoids an irreversible link to the wrong account.
3. If access is intentionally unavailable, the responsible vendor publishes the restriction and provides an appropriate refund, service credit, or other billing remedy.

A generic “forwarded,” “duplicate,” “please wait,” or “settings refreshed” response is not resolution.

## Privacy boundary

This repository intentionally omits:

- complete customer email addresses;
- the private support-ticket identifier;
- Gmail message, thread, and mailbox identifiers;
- OAuth nonce, state, authorization-session, and callback identifiers;
- raw email headers and private support transcripts;
- IP address, ISP, exact location, and raw browser/network logs;
- subscription receipts or payment identifiers;
- the original authorization-consent screenshot because it visibly contains the private X-linked email address; and
- journalist email addresses and other outreach contact details.

The public record preserves dates, roles, technical outcomes, corrections, vendor-routing events, public URLs, and cryptographic hashes sufficient to distinguish the retained source artifacts.

## Accuracy and update policy

- Confirmed observations are separated from inferences.
- The `.ru` domain being the policy trigger remains an inference until Cursor confirms it.
- Support correspondence is paraphrased and stripped of identifiers.
- Material corrections are preserved rather than silently rewritten.
- New evidence, vendor replies, public actions, and resolution tests will be appended with UTC timestamps.

## Outreach checkpoint — September 10, 21:21 UTC

Batch ten sent four separate notes at 21:19 UTC on September 10: three named journalists and one technology desk, all at new outlets. Exact recipients, subjects, bodies and Sent labels were verified. Total: 73 counted destinations at 47 outlets; one earlier failed address remains excluded. Each note was about 160 words, offered a specific editorial reason and one current evidence link, and disclosed AI assistance without pressure.

The September 10 support-response page was dispatched to four new destinations. There are 68 eligible earlier destinations for a staged, one-time material update; the prior objector and failed address remain excluded. The September 9-only distribution checkpoint remains 26 destinations, with 42 earlier eligible recipients then pending. Future combined updates should use the current page, which links that earlier evidence. Dispatch is not inbox delivery, readership or coverage.

## Outreach checkpoint — September 11, 03:20 UTC

Batch eleven sent three separate notes to named technology writers at 03:18 UTC on September 11, including two new independent outlets. The roughly 170-word notes used verified editorial relevance, one current evidence link and explicit AI-assistance disclosure. Exact recipients, subjects, bodies and Sent labels were verified. Total: 76 counted destinations at 49 outlets; one earlier failed address remains excluded.

Five eligible earlier contacts also received one brief, individual update containing the September 10 support response. The current material has now been dispatched to 12 destinations: seven new contacts and five earlier recipients. There are 63 eligible earlier recipients still awaiting this staged update. The previous objector and failed address remain excluded. These follow-ups do not increase the unique-contact total, and dispatch is not proof of readership or coverage.

September 11 checks found no newer support, press or agency reply and no new delivery failure. In-app Reddit and X inspections found no new substantive response or moderation change; the displayed view counts were 3.3K and 43 respectively. No new support, agency or social message was sent. Access remains unresolved; checks continue every six hours.

## September 12 outreach checkpoint

Two new, separately researched notes were sent to named technology journalists on September 12 at 03:10 UTC, including one new outlet. Each was 166 words, included one current evidence link and disclosed AI assistance. The freelance recipient was identified privately as a contributor, not a staff reporter. Four earlier recipients received a concise correction in their existing threads. Every exact recipient, subject, body and Sent label was verified. No immediate delivery failure was found. Sent is dispatch, not readership or coverage.

As of September 12, 03:17 UTC: 78 counted destinations at 50 outlets, 79 attempted addresses and one earlier permanent failure excluded. The September 11 support correction has six distinct dispatches: two new contacts and four earlier recipients. Of 75 eligible earlier contacts, 71 remain for staged one-time correction. The old September 10-only queue is superseded; do not stack stale updates or rebroadcast count-only changes.

## September 12, 09:30 UTC: batch thirteen

Batch thirteen sent three individually researched notes on September 12 at 09:27 UTC: two named independent technology/AI writers and one editorial tips desk, at three additional outlets. Each included one current evidence link, an optional question and explicit AI-assistance disclosure. Four eligible earlier recipients received a factual correction in their existing incident threads. All seven exact bodies, recipients, subjects and Sent labels were verified; no immediate failure was found. Dispatch is not inbox delivery, readership or coverage.

Current totals: 81 counted destinations at 53 outlets, 82 attempted addresses and one earlier permanent failure excluded. The September 11 support correction has 13 distinct dispatches: five new contacts and eight earlier recipients. Of 75 eligible earlier contacts, 67 remain for staged one-time correction. Older September 9/10-only update queues are superseded, not additional messages to send.

The full original Cursor thread and incoming support, press, agency and delivery-failure checks found no new reply or failure. In-app browser reads timed out, including the supported alternate visible-page reader, so no fresh Reddit/X content inspection or post is claimed. The earlier X submission remains unconfirmed and was not retried. No support demand, agency filing, account change or entitlement test was performed. Access remains unresolved.
