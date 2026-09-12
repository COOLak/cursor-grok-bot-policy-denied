# Action log

> **September 11 support correction:** Cursor now says different emails can link and attributes this case to a .ru domain restriction. No fix or X-sign-in email-change procedure has been verified. [Read the correction and September 12 follow-up](support-correction-20260911.html). Earlier statements and downloadable packets are historical snapshots.

## Historical support response — September 10, 20:57 UTC (superseded September 11)

[Cursor has replied, but no working usage-grant path has been verified](support-response-20260910.html). The response rejects linking the different-email account and says the matching login cannot be created from this ticket. This does not confirm a blanket domain ban. One factual clarification was sent in the original case.

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
- After the promised response window expired, sent one non-duplicated technical follow-up at 2026-09-04 23:52 UTC demanding a named owner, exact evaluated rule, supported matching-`.ru` path, firm ETA, or billing remedy.

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
- Expanded the public hub toward the Anthropic mirror's layered incident-package model: incident brief, reporter brief, owner-action packet, reconciliation matrix, evidence chain, source matrix, public timeline, outreach record, affected-user checklist, machine-readable records, and social/indexing metadata. A later 2026-09-05 audit corrected the earlier overbroad parity claim and labeled remaining gaps explicitly.
- Sent the full parity package from material commit `8a549b2` individually to all 21 current press recipients; the update included the reporter brief, owner-action packet, reconciliation matrix, timeline, and privacy-sanitized outreach record.
- Sent the expanded material snapshot from commit `937d14a` individually to all 31 current press recipients after batch three and public-response metrics were added.
- Sent a fourth controlled batch to seven newly verified recipients at ABC News, CNBC, Mother Jones, Reuters, Slate, and The Atlantic after deduplicating every address against the private ledger and all Gmail Sent history.
- Recorded the public-attention checkpoint at 1.2K Reddit views and 12 X views; the existing replies remain a community analysis and an automated routing response, not human vendor engagement.
- Sent material snapshot `6b871ad` individually to all 38 current press recipients after the fourth batch and public-attention milestone were recorded.
- Sent a fifth controlled batch to 10 newly verified recipients at BleepingComputer, Business Insider, Computerworld, and CyberScoop after deduplicating every address against the private ledger and all Gmail Sent history.
- Recorded the public-attention checkpoint at 1.6K Reddit views and 13 X views; the same replies remain community analysis and automated routing, not human vendor engagement.
- Sent material snapshot `13eb557` individually to all 48 current press recipients after the fifth batch and audience checkpoint were published.
- Audited the Anthropic billing mirror at commit `58006ec`, corrected the false claim that it published recipient outlets, and documented that it contained neither a journalist roster nor a numeric press-recipient total.
- Added a functional-parity audit, account-framing correction, authentication-path audit, support-routing cluster, and regulator-ready public attachment. Open gaps remain labeled rather than implied complete.
- Sent material snapshot `630094e` individually to all 48 current press recipients. Marker verification found 48 messages to 48 distinct destinations and no immediate delivery-failure candidate.
- Verified Cursor's newly published SuperGrok linking guide and xAI's Grok Bot FAQ, then preserved both in successful time-stamped Wayback captures. The first-party guide confirms individual Heavy eligibility, a one-account usage grant without a paid Cursor-plan prerequisite, permanent linking, and support routing, but publishes no same-email or `.ru`-domain restriction.
- Sent the archived-guidance and public-reconciliation snapshot `38bfe8c` individually to all 48 current press recipients. Marker verification found 48 messages to 48 distinct destinations and no immediate delivery-failure candidate.
- Recorded the first substantive human journalist reply to this campaign. The correspondent supplied a public essay objecting to AI-written pitches; the reply is classified as an outreach-method objection, not coverage, readership, agreement, or incident corroboration. The identity, direct correspondence, signature details, and contact information remain private.
- Paused new AI-authored cold outreach and mass mirror-update replies pending an explicit transparent composition-method decision. The support watcher and public-thread monitoring remain active.
- Rechecked the public threads: Reddit reached 2.2K views with the same substantive community reply, while X reached 16 views with the same external automated Grok routing reply.

## Press escalation

- Built a private deduplicated outreach ledger containing source-verified work contacts.
- First five batches: 48 tips across 26 outlets. September 9 batch six adds six destinations (five named journalists and one tips desk); total 54 at 31 outlets.
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
- Verified 48 snapshot-update replies to 48 distinct recipients and found no immediate delivery failure.
- September 9 revised cadence: five to eight newly verified relevant destinations every six hours until at least 100, prioritizing new outlets and one destination per outlet per batch.
- Material incident changes may be shared once with eligible prior recipients, respecting objections and opt-outs. No pressure reminders, repeated initial tips or count-only broadcasts.

## Monitoring

- A six-hour watcher monitors the authoritative Cursor support thread, the xAI transfer, journalist replies, Reddit, X, and this public mirror.
- Routine no-change checks remain quiet.
- A vendor claim that the issue is fixed must be tested in the live signup/sign-in/linking flow before the incident can be marked resolved.


## September 9 evidence update

- Preserved the new phone screenshot privately and published its SHA-256, selected-text transcription and bot-callback route correction. Never uploaded the private email or OAuth session URL.
- Recorded the customer statement that the matching-email Cursor account has never existed.
- Prepared English and Japanese consumer complaint narratives and inspected official intake routes. At that initial preparation checkpoint nothing had been filed; verified submissions are recorded below.
- At the earlier preparation checkpoint, press distribution was on hold. The later batch-six distribution is recorded below; no coverage is implied.

- Recorded the later email-code verification failure as E-11 and the customer-reported working Gmail-account comparison. Original image and full account details remain private.

- Sent the September 9 evidence update to the original Cursor case and verified it in Sent. Submitted a factual FTC consumer report and verified the receipt; it is not a finding or individual-remedy promise.
- Preserved the subsequent refresh clarification: email-code signup returns the original access block; the human-verification message did not persist. Do not portray it as a second continuing barrier.

- Sent the refresh clarification to the original Cursor case and verified it in Sent.
- Submitted the refresh clarification as an FTC supplement explicitly referencing the initial report, as directed by its FAQ. Verified the browser receipt, displayed submitted narrative and email acknowledgement. This is one incident, not two claimed losses.
- Sent a private written-evidence routing inquiry and follow-up to the local consumer-affairs office in Japan. A formal complaint has not been confirmed accepted.
- Published and verified the [Reddit update](https://www.reddit.com/r/cursor/comments/1w6p3gi/comment/p8ocwis/) and [X update](https://x.com/Coolak777/status/2097524420579570096). Exact residency and other private details remain withheld.
- At that checkpoint, retained the six-hour monitoring cadence and press hold; the subsequent renewal below supersedes the hold.

## September 9: more considerate press outreach resumed

- Following the customer's renewed instruction, lifted the composition-method hold and sent six separate, tailored notes at 03:38–03:39 UTC: five named journalists and one tips desk, across six outlets (five new to the campaign).
- Verified work contacts on primary outlet pages, checked Sent and the private ledger, and excluded the correspondent who objected. No CC or BCC was used.
- Each note included explicit AI-assistance disclosure, a beat-relevant angle, the September 9 evidence-page link and a low-pressure question. The unconfirmed domain cause and limits of the phone test were not presented as established findings.
- Verified all six in Sent; no immediate bounce found. Total 54 distinct destinations at 31 outlets; neither receipt nor readership is established.
- The earlier 48 have not yet received the September 9 addendum by email. This bookkeeping update was not rebroadcast.
- Six-hour staged outreach continues in smaller batches of five to eight, with objections and opt-outs respected. Private recipient identities, addresses and exact pitches remain outside this repository.

## September 9: agency reply and next controlled press batch

- At 05:55 UTC on September 9, a local consumer-affairs office in Japan replied that it cannot negotiate with overseas sellers over directly purchased digital services. It referred the customer to the National Consumer Affairs Center's Cross-border Consumer Center Japan (CCJ) from September 14. This is a routing response, not complaint acceptance, a finding against either vendor, or a remedy.
- No new Cursor or xAI substantive reply, press response, opt-out or delivery failure was found during this check. Reddit and X showed no new substantive response or moderation change; no new social post was sent.
- At approximately 06:46 UTC, sent five new individual notes at five new outlets: three named journalists and two editorial desks. Verified recipient, subject, exact body and Sent label. Campaign total: 59 destinations at 36 outlets.
- At approximately 06:47 UTC, sent five individual material evidence updates to eligible earlier recipients after checking incoming mail and prior distribution. All were Sent-verified. The objector was not contacted.
- The September 9 signup evidence page has been sent to 16 destinations: 11 new contacts across batches six and seven, and five eligible earlier recipients. Of the original 48, 43 have not received this addendum; one is excluded following an objection, leaving 42 eligible recipients for staged distribution. Sent records establish dispatch, not inbox delivery or readership.
- No count-only broadcast. The six-hour cadence and privacy boundaries remain in force; the underlying access issue is unresolved.

## September 9, 17:08 UTC — considerate outreach batch eight

- Batch eight added five counted destinations at five new outlets: two named editors and three editorial desks. One published staff address returned a permanent delivery failure and was excluded; the outlet's published editorial desk was used once instead. All counted notes were verified in Sent, with explicit AI-assistance disclosure and the September 9 evidence link. Total: 64 counted destinations at 41 outlets, with one recorded failed address.
- The September 9 signup evidence page has been dispatched to 21 counted destinations: 16 new contacts across batches six through eight, plus five eligible earlier recipients. One additional attempted address bounced and is excluded. Of the original 48, one is excluded following an objection and 42 remain eligible for a staged addendum. Sent records establish dispatch, not inbox delivery or readership.
- New notes used plain language, documented outlet relevance, one evidence link and no demand for coverage. Prior unrelated correspondence was acknowledged where applicable.
- The six-hour cadence remains unchanged. No new support demand, agency filing or social post was sent. Public-thread inspection could not be refreshed because internal-browser control timed out; earlier view counts are historical, not a new observation.

## September 10, 15:15 UTC — five individual press notes

- Batch nine sent five separate, tailored notes on September 10 at 15:14 UTC: four named reporters and one tips desk, across five outlets including two new outlets. Exact recipients, subjects, bodies and Sent labels were verified; no immediate failure was found. Total: 69 counted destinations at 43 outlets; one earlier failed address remains excluded.
- The September 9 signup evidence page has been dispatched to 26 counted destinations: 21 new contacts across batches six through nine, plus five eligible earlier recipients. One earlier failed address is excluded. Of the original 48, one is excluded following an objection and 42 remain eligible for a staged addendum. Sent records establish dispatch, not inbox delivery or readership.
- Each note used the recipient’s actual beat, plain language, one evidence link and an unobtrusive AI-assistance disclosure. No demand for coverage, fake familiarity, CC/BCC, private residency detail or confirmed-domain-ban claim. Objections and known failures were excluded.
- Original support, press and agency mail checks found no new reply. Internal-browser Reddit and X checks found no new substantive response or moderation change; view counts were 3.2K and 42 respectively. No new support, agency or social message was sent.
- Keep exactly six-hour monitoring and one controlled future batch per run. This count-only record was not rebroadcast; access remains unresolved.

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

### Public discussion correction

[Reddit correction](https://www.reddit.com/r/cursor/comments/1w6p3gi/comment/p9a8l1g/) posted and freshly verified September 12. It states the new vendor attribution and withdrawn matching-email advice, while distinguishing a proposed email change from a fix. One X reply was attempted; publication was not confirmed and it was not resent. No regulator submission or account change occurred in this run.

## September 12, 09:30 UTC: batch thirteen

Batch thirteen sent three individually researched notes on September 12 at 09:27 UTC: two named independent technology/AI writers and one editorial tips desk, at three additional outlets. Each included one current evidence link, an optional question and explicit AI-assistance disclosure. Four eligible earlier recipients received a factual correction in their existing incident threads. All seven exact bodies, recipients, subjects and Sent labels were verified; no immediate failure was found. Dispatch is not inbox delivery, readership or coverage.

Current totals: 81 counted destinations at 53 outlets, 82 attempted addresses and one earlier permanent failure excluded. The September 11 support correction has 13 distinct dispatches: five new contacts and eight earlier recipients. Of 75 eligible earlier contacts, 67 remain for staged one-time correction. Older September 9/10-only update queues are superseded, not additional messages to send.

The full original Cursor thread and incoming support, press, agency and delivery-failure checks found no new reply or failure. In-app browser reads timed out, including the supported alternate visible-page reader, so no fresh Reddit/X content inspection or post is claimed. The earlier X submission remains unconfirmed and was not retried. No support demand, agency filing, account change or entitlement test was performed. Access remains unresolved.
