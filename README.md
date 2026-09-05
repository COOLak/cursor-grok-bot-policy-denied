# SuperGrok Heavy / Cursor Grok Bot `policy_denied` incident

This repository is a privacy-sanitized public evidence hub for an unresolved paid-feature access failure involving xAI's SuperGrok Heavy subscription and Cursor's Grok Bot linking flow.

## Start here

- **[Open the public incident page](https://coolak.github.io/cursor-grok-bot-policy-denied/)**
- **[Read the public incident brief](https://coolak.github.io/cursor-grok-bot-policy-denied/incident-brief.html)**
- **[Open the reporter-ready brief](https://coolak.github.io/cursor-grok-bot-policy-denied/reporter-brief.html)**
- **[Give the technical owner this action packet](https://coolak.github.io/cursor-grok-bot-policy-denied/owner-action.html)**
- **[Inspect the system reconciliation matrix](https://coolak.github.io/cursor-grok-bot-policy-denied/reconciliation-matrix.html)**
- **[Audit the evidence chain and proof boundaries](https://coolak.github.io/cursor-grok-bot-policy-denied/evidence-chain.html)**
- **[Inspect the public-source matrix](https://coolak.github.io/cursor-grok-bot-policy-denied/public-source-matrix.html)**
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

**Unresolved as of 2026-09-05 00:14 UTC.**

- Grok Bot access has not been verified working.
- Cursor has not confirmed the precise backend reason for `policy_denied`.
- Cursor has not supplied a supported matching-`.ru` signup/linking path.
- No human technical owner or firm remediation ETA has been provided.
- Cursor's promised response window expired; a one-time follow-up at 2026-09-04 23:52 UTC demanded a named owner, exact rule, supported matching-`.ru` path, firm ETA, or billing remedy.
- Public posts are live. At the latest public check, Reddit showed 1.6K views and one substantive community reply; X showed 13 views and one external automated Grok routing reply. Neither reply is treated as a vendor resolution or technical finding.
- A staged press campaign has reached 48 distinct verified recipients without an immediate delivery failure.
- The live GitHub mirror, reporter brief, and timeline were individually included in outreach to all 48 current press recipients.
- Material snapshot `13eb557` was sent individually to all 48 current press recipients; no immediate delivery failure was found.
- Monitoring and evidence preservation continue every six hours.

## Media-outreach record

The Anthropic incident mirror did **not** publish a journalist roster or a numeric press-recipient total. Its public incident brief says only that privacy-sanitized tips went to “several relevant outlets.” It names Future Stack Reviews only after independent coverage appeared, not as a campaign roster. The full finding and private-mail cross-check are documented in the [`anthropic-approach-audit`](anthropic-approach-audit.md).

This mirror keeps individual names, addresses, and correspondence private while making the aggregate campaign materially more explicit.

As of 2026-09-04 18:08 UTC, **48 distinct verified recipients at 26 outlets** had received individualized tips and material snapshot `13eb557`. The 21 recipients in the first two batches had also received the earlier full parity-package update:

- 404 Media — 4 recipients
- ABC News — 1
- Ars Technica — 1
- Axios — 1
- Bloomberg — 1
- BleepingComputer — 4
- Business Insider — 1
- CNBC — 2
- Computerworld — 4
- CyberScoop — 1
- Engadget — 3
- Fast Company — 1
- Forbes — 2
- Gizmodo — 1
- Mother Jones — 1
- Rest of World — 1
- Reuters — 1
- Slate — 1
- TechCrunch — 1
- Tech Policy Press — 1
- TechRadar — 1
- The Atlantic — 1
- The Register — 5
- Tom's Hardware — 1
- VentureBeat — 1
- WIRED — 6

No immediate delivery failure was found at the recorded checkpoint. Exact recipient names and addresses remain private; the public-safe outlet ledger is [`press-outreach-summary.csv`](press-outreach-summary.csv).

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
- a regulator-ready PDF that is expressly not represented as filed.

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
