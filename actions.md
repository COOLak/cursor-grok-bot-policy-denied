# Action log

This log records actions taken to diagnose, resolve, document, and escalate the incident. Private identifiers are omitted.

## Product and network diagnostics

- Repeated the Grok Bot authorization flow with fresh authorization sessions.
- Confirmed that the X/xAI authorization page recognized the paid identity.
- Confirmed that the callback returned `policy_denied` and the entitlement was not applied.
- Checked ordinary Windows network state for common VPN processes and system proxy configuration.
- Retried after Cursor said it refreshed backend settings.
- Preserved two source screenshots and their SHA-256 digests.
- Withheld the consent screenshot from the public repository because it displays the complete private account address.

## Cursor support escalation

- Opened the original case on August 16.
- Supplied the requested error screenshot, subscription context, X-authentication explanation, and network checks.
- Asked whether an existing permanent link, account classification, or entitlement association caused the failure.
- Followed up after the settings refresh did not change the result.
- Requested specialist review of the linking state and a safe non-destructive path.
- Corrected the record to state that a new matching-`.ru` Cursor account is acceptable.
- Requested a human technical owner, exact backend reason, supported remedy, and ETA.
- Rejected duplicate closure or generic forwarding language as sufficient resolution.

## xAI escalation

- Forwarded the evidence and Cursor correspondence to xAI support.
- Requested intervention because the advertised benefit belongs to a paid SuperGrok plan.
- xAI support redirected ownership to Cursor; the transferred Cursor request was then closed as a duplicate.

## Public escalation

- Published a detailed Reddit report in the Cursor community.
- Published an X incident thread.
- Published a separate X clarification correcting the target-account misunderstanding.
- Published an X link amplifying the Reddit evidence.
- Created this GitHub evidence hub and GitHub Pages mirror.

## Monitoring

- A six-hour watcher monitors the authoritative Cursor support thread, the xAI transfer, Reddit, X, and this public mirror.
- Routine no-change checks remain quiet.
- A vendor claim that the issue is fixed must be tested in the live signup/sign-in/linking flow before the incident can be marked resolved.

