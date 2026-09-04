# Technical owner action packet

## Owner-routing request

Assign one human owner who can inspect Cursor's Grok Bot authentication, account eligibility, permanent-link registry, and xAI entitlement handoff. A support router or billing generalist cannot resolve the unexplained `policy_denied` decision.

## Current handoff state

- Cursor collected screenshots, plan context, account details, and proxy/VPN checks.
- Cursor reported a backend-settings refresh; the retry still failed.
- Cursor stated that the SuperGrok and Cursor emails must match and that a successful link cannot be moved.
- Cursor later forwarded the matter to the Grok Bot technical team without a named owner, finding, remedy, or ETA.
- xAI routed the issue back to Cursor.
- Cursor automation closed the transferred request as a duplicate of the original unresolved case.

## Observed good path

1. The customer opens **Get access with SuperGrok Heavy**.
2. X/xAI recognizes the paid identity.
3. The customer reaches and approves Cursor's OAuth consent request.

## Observed bad path

1. Cursor's callback receives the authorization result.
2. The flow returns `error=policy_denied`.
3. Grok Bot displays **“Access blocked, please contact support.”**
4. A new matching-`.ru` personal Cursor account cannot be completed and the paid entitlement is not activated.

## Inspect these systems

| System | Required inspection |
|---|---|
| OAuth callback and policy engine | Resolve the exact rule, rule version, decision code, and evaluated attributes behind `policy_denied`. |
| Cursor account eligibility | Determine whether personal accounts using the matching `.ru` address can be created and used for Grok Bot. |
| Permanent-link registry | Confirm whether the paid X/xAI identity is already linked, reserved, partially linked, or unlinked, without exposing another user's data. |
| Entitlement exchange | Trace SuperGrok Heavy verification from xAI identity through Cursor entitlement activation. |
| Risk/compliance controls | State whether domain, geography, sanctions controls, abuse scoring, or another policy intentionally blocks the path. |
| Error telemetry | Preserve the failed authorization decisions and correlate them with the customer's private support evidence. |
| Support tooling | Make the backend reason and supported remedy visible to the assigned human owner instead of creating a duplicate loop. |
| Billing remedy | If the benefit is unavailable by policy, identify the responsible vendor and the refund, service-credit, or equivalent remedy. |

## Minimum useful reply

A useful written reply must provide:

1. a named or clearly accountable human technical team;
2. the precise backend reason for `policy_denied`;
3. whether the matching `.ru` personal-account path is supported;
4. whether a permanent or partial link already exists;
5. exact safe retry or remediation steps;
6. an ETA; and
7. a billing remedy if the advertised benefit cannot be delivered.

## What does not resolve the incident

- “Forwarded to a teammate.”
- “Duplicate.”
- “Please wait.”
- “Settings refreshed” without a successful live retry.
- A suggestion to use a different email that would not match the paid X/xAI identity.
- A technically successful link to an unconfirmed target account.

## Resolution test

The owner should supply a supported path, then the customer should verify the target account before completing the irreversible link. Resolution requires a live Grok Bot session with the SuperGrok Heavy entitlement, or a documented restriction plus an appropriate billing remedy.

## Privacy boundary

The public packet omits exact email addresses, the support-ticket identifier, OAuth session values, Gmail identifiers, raw correspondence, payment data, and journalist contact details. The customer can supply private evidence through a safer authenticated channel.
