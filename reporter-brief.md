# Reporter brief: paid SuperGrok Heavy benefit blocked in Cursor

## The story in one paragraph

A paying SuperGrok Heavy subscriber can reach and approve Cursor's authorization request through the X/xAI identity provider, but Cursor's callback returns `policy_denied` and Grok Bot displays “Access blocked, please contact support.” Cursor says the SuperGrok and Cursor emails must match and that links are permanent. The subscriber is willing to create the required new personal Cursor account using the matching `.ru` address, but that path remains blocked. xAI routes support responsibility to Cursor; Cursor closed the transferred request as a duplicate of the original unresolved case. No vendor has identified the precise backend rule, supplied a working path, or documented a billing remedy.

## Confirmed facts

- xAI publicly lists SuperGrok Heavy among plans that include Grok Bot.
- The paid identity is authenticated through X and has a valid `.ru` email address.
- The xAI/X authorization step was reached and approved.
- Cursor's callback returned `policy_denied`.
- The visible Grok Bot page displayed “Access blocked, please contact support.”
- The failure persisted after fresh sessions, ordinary VPN/proxy checks, and a Cursor-side settings refresh.
- Cursor said the SuperGrok and Cursor emails must match and that successful links cannot be moved.
- A new matching-`.ru` personal Cursor account is acceptable to the subscriber.
- xAI told the subscriber that Cursor owns Grok Bot support.
- Cursor's automated assistant closed the transferred request as a duplicate of the still-unresolved original case.
- The incident remains unresolved.

## Not yet confirmed

- Whether `.ru` is the actual backend policy trigger.
- Whether the paid identity has any pre-existing permanent Cursor link.
- Whether the block originates in Cursor, xAI, or a shared risk/eligibility service.
- Whether the block is intentional policy, a sanctions-control implementation, risk scoring, or an unintended account-system defect.
- Whether any published eligibility rule covers the observed behavior.

## Why this is newsworthy

- A premium subscription publicly advertises a partner benefit that cannot be activated.
- The identity-provider flow succeeds far enough for the partner to evaluate and deny the request.
- The same-email and permanent-link constraints make unsupported workarounds risky.
- Cross-company routing has not produced one accountable technical owner.
- The apparent domain-sensitive behavior is not explained in the public plan material.

## Questions for Cursor and xAI

1. What exact backend rule produced `policy_denied`?
2. Does Cursor prohibit personal signup or entitlement linking for otherwise valid `.ru` addresses?
3. If so, where is that restriction published and what supported remedy exists for current paying subscribers?
4. If not, why can the customer not create/use the required matching personal account?
5. Can the vendors confirm whether the paid identity is already permanently linked without exposing another account's identity?
6. Which company owns entitlement delivery, account eligibility, and billing remediation?
7. What is the ETA for a working path or written remedy?

## Public sources

- Evidence hub: https://coolak.github.io/cursor-grok-bot-policy-denied/
- Source repository: https://github.com/COOLak/cursor-grok-bot-policy-denied
- xAI plan announcement: https://x.ai/news/grok-bot-more-plans
- Reddit report: https://www.reddit.com/r/cursor/comments/1w6p3gi/supergrok_heavy_grok_bot_matching_ru_email_gets/
- X report: https://x.com/Coolak777/status/2095666718429589769

Private subscription proof, the original authorization screenshot, and sanitized support excerpts can be supplied directly to a journalist when genuinely needed.

## Public outreach checkpoint

As of 2026-09-04 01:10 UTC, individualized privacy-sanitized tips and the live evidence-hub update had reached **21 distinct verified recipients at 11 outlets**. Outlet names and counts are public in [`press-outreach-summary.csv`](press-outreach-summary.csv); individual names, addresses, and private correspondence are withheld.
