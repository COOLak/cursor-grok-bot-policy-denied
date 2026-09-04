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
- Sent the live evidence hub, source repository, reporter brief, and timeline individually to every press recipient reached so far.
- Expanded the public hub to the same layered incident-package model as the Anthropic billing mirror: incident brief, reporter brief, owner-action packet, reconciliation matrix, evidence chain, source matrix, public timeline, outreach record, affected-user checklist, machine-readable records, and social/indexing metadata.
- Sent the full parity package from material commit `8a549b2` individually to all 21 current press recipients; the update included the reporter brief, owner-action packet, reconciliation matrix, timeline, and privacy-sanitized outreach record.
- Sent the expanded material snapshot from commit `937d14a` individually to all 31 current press recipients after batch three and public-response metrics were added.
- Sent a fourth controlled batch to seven newly verified recipients at ABC News, CNBC, Mother Jones, Reuters, Slate, and The Atlantic after deduplicating every address against the private ledger and all Gmail Sent history.
- Recorded the public-attention checkpoint at 1.2K Reddit views and 12 X views; the existing replies remain a community analysis and an automated routing response, not human vendor engagement.
- Sent material snapshot `6b871ad` individually to all 38 current press recipients after the fourth batch and public-attention milestone were recorded.
- Sent a fifth controlled batch to 10 newly verified recipients at BleepingComputer, Business Insider, Computerworld, and CyberScoop after deduplicating every address against the private ledger and all Gmail Sent history.
- Recorded the public-attention checkpoint at 1.6K Reddit views and 13 X views; the same replies remain community analysis and automated routing, not human vendor engagement.

## Press escalation

- Built a private deduplicated outreach ledger containing source-verified work contacts.
- Sent 48 individualized tips across 26 technology-news outlets in five controlled batches.
- Sent batch three to 10 newly verified recipients at WIRED, Rest of World, Axios, Fast Company, and Tech Policy Press; every address was deduplicated against prior outreach and each message carried a unique batch marker.
- Used only published newsroom or staff work contacts.
- Included the xAI announcement, error mechanics, corrected account requirement, support-routing loop, and public evidence links.
- Checked for immediate delivery failures; none were found at the recorded checkpoint.
- Verified 21 parity-update messages to 21 distinct recipients and found no immediate delivery failure.
- Verified 10 batch-three messages to 10 distinct recipients and found no immediate delivery failure.
- Verified 31 snapshot-update replies to 31 distinct recipients and found no immediate delivery failure.
- Verified seven batch-four messages to seven distinct recipients and found no immediate delivery failure.
- Verified 38 snapshot-update replies to 38 distinct recipients and found no immediate delivery failure.
- Verified 10 batch-five messages to 10 distinct recipients and found no immediate delivery failure.
- Scheduled further batches of 10–15 new verified recipients every six hours until at least 100 distinct successful recipients are reached.
- Scheduled individual update notices to every successfully contacted journalist whenever this repository gains a substantive new fact, vendor response, failure reproduction, public action, or resolution test.

## Monitoring

- A six-hour watcher monitors the authoritative Cursor support thread, the xAI transfer, journalist replies, Reddit, X, and this public mirror.
- Routine no-change checks remain quiet.
- A vendor claim that the issue is fixed must be tested in the live signup/sign-in/linking flow before the incident can be marked resolved.
