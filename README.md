# SuperGrok Heavy / Cursor Grok Bot `policy_denied` incident

This repository is a privacy-sanitized public evidence hub for an unresolved paid-feature access failure involving xAI's SuperGrok Heavy subscription and Cursor's Grok Bot linking flow.

## Start here

- **[Open the public incident page](https://coolak.github.io/cursor-grok-bot-policy-denied/)**
- **[Read the public incident brief](https://coolak.github.io/cursor-grok-bot-policy-denied/incident-brief.html)**
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

**Unresolved as of 2026-09-05 00:33 UTC.**

- Grok Bot access has not been verified working.
- Cursor has not confirmed the precise backend reason for `policy_denied`.
- Cursor has not supplied a supported matching-`.ru` signup/linking path.
- Cursor's public linking guide confirms individual SuperGrok Heavy eligibility, a grant without a paid Cursor-plan prerequisite, permanent linking, and support routing, but publishes no same-email requirement or `.ru`-domain exclusion.
- No human technical owner or firm remediation ETA has been provided.
- Cursor's promised response window expired; a one-time follow-up at 2026-09-04 23:52 UTC demanded a named owner, exact rule, supported matching-`.ru` path, firm ETA, or billing remedy.
- Public posts are live. At the latest public check, Reddit showed 1.6K views and one substantive community reply; X showed 13 views and one external automated Grok routing reply. Neither reply is treated as a vendor resolution or technical finding.
- Monitoring and evidence preservation continue every six hours.

## Anthropic-approach audit and functional parity

The earlier claim of full structural parity was too broad. The 2026-09-05 audit now maps every material Anthropic incident function to an implemented Cursor artifact, a fact-specific adaptation, or an explicitly open gap. See [`anthropic-approach-audit.md`](anthropic-approach-audit.md).

The implemented common layers include:

- a concise public incident brief;
- a concrete owner-action packet;
- a symptom-to-system reconciliation matrix;
- an evidence chain with explicit proof limitations;
- a source matrix that separates first-party, private authenticated, and public-discussion evidence;
- a public timeline;
- an affected-user checklist for comparable reports;
- machine-readable state and evidence custody records; and
- an indexable GitHub Pages site with canonical, Open Graph, Twitter-card, and structured metadata;
- a dedicated account-framing correction;
- an authentication-path audit;
- a support-routing cluster; and
- a regulator-ready PDF that is expressly not represented as filed; and
- neutral, time-stamped preservation of material first-party eligibility and linking terms.

No comparable-victim cluster or vendor-owned public issue burst is invented. Transaction-ledger artifacts from the billing incident are not copied into this access incident; their evidentiary function is served by the authentication-path and support-routing audits.

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
- the original authorization-consent screenshot because it visibly contains the private X-linked email address.

The public record preserves dates, roles, technical outcomes, corrections, vendor-routing events, public URLs, and cryptographic hashes sufficient to distinguish the retained source artifacts.

## Accuracy and update policy

- Confirmed observations are separated from inferences.
- The `.ru` domain being the policy trigger remains an inference until Cursor confirms it.
- Support correspondence is paraphrased and stripped of identifiers.
- Material corrections are preserved rather than silently rewritten.
- New evidence, vendor replies, public actions, and resolution tests will be appended with UTC timestamps.
