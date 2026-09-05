# Evidence and limitations register

## E-01 — xAI plan announcement

**Public source:** https://x.ai/news/grok-bot-more-plans

xAI's August 26, 2026 announcement says Grok Bot is included with SuperGrok Heavy. The announcement establishes the general advertised plan benefit; it does not disclose a `.ru` email-domain exclusion or prove this customer's account-level eligibility.

## E-02 — Public-safe access-blocked screenshot

**Public artifact:** [`assets/access-blocked.png`](assets/access-blocked.png)

The screenshot shows the Grok Bot sign-in page displaying “Access blocked, please contact support” immediately above the **Get access with SuperGrok Heavy** path. It contains no complete customer address, ticket identifier, or authorization-session value.

The screenshot proves the visible failure state. By itself, it does not prove subscription ownership, payment status, the server-side policy reason, or the identity-provider state.

## E-03 — X authorization screenshot

**Custody:** retained privately; not uploaded.

The screenshot shows the xAI/X consent page authorizing Cursor and visibly displays the X-linked account address. It supports the sequence in which X authorization is reached before Cursor's callback rejects the flow.

It is withheld because redacting only the address while preserving every other pixel would create an additional derivative artifact; the original digest is preserved in `evidence-manifest.json`.

## E-04 — Cursor support correspondence

**Custody:** authenticated private Gmail thread retained by the customer.

The correspondence establishes the requests for diagnostics, Cursor's settings refresh, the same-email requirement, permanent-link warning, technical-team routing, corrected target-account requirement, and the absence of a working remedy as of the last update.

Public files paraphrase the relevant statements. Raw headers, message IDs, addresses, tracking pixels, and full message bodies are excluded.

## E-05 — xAI and duplicate-routing correspondence

**Custody:** authenticated private Gmail records retained by the customer.

xAI support routed the matter to Cursor on the ground that Cursor supports Grok Bot. Cursor's automated support closed the transferred request as a duplicate of the original case. These records support the documented ownership loop; they do not establish what either company did internally.

## E-06 — Network and retry checks

**Custody:** private support messages and contemporaneous local checks.

Ordinary Windows proxy settings were disabled and no common VPN process was active when the failure was reproduced. The public record does not disclose an IP address, ISP, or exact location.

These checks reduce the plausibility of a local VPN/proxy explanation. They do not exclude every possible network, geolocation, risk-scoring, or account-policy factor.

## E-07 — Public discussion

- Reddit: https://www.reddit.com/r/cursor/comments/1w6p3gi/supergrok_heavy_grok_bot_matching_ru_email_gets/
- X: https://x.com/Coolak777/status/2095666718429589769
- X correction: https://x.com/Coolak777/status/2095666806040236440
- X amplifier: https://x.com/Coolak777/status/2095671328988856616

These URLs prove publication and preserve the public framing. At the 2026-09-04 17:59 UTC checkpoint, Reddit showed 1.6K views and one substantive community reply; X showed 13 views and one external automated Grok routing reply. The community reply's analysis and Grok's routing response are not treated as technical proof, human vendor engagement, or resolution.

## E-08 — Press outreach records

**Public artifacts:** [`press-outreach.html`](press-outreach.html) and [`press-outreach-summary.csv`](press-outreach-summary.csv)

The private ledger records exact work addresses, verification sources, send results, and deduplication state. The public summary names 26 outlets and reports only aggregate counts. A Gmail sent-mail audit found 48 distinct successful recipients, including 10 marker-verified messages in batch five, plus 48 individually marker-verified replies distributing material snapshot `38bfe8c`. No duplicate address or immediate delivery failure was found at the recorded checkpoint. One human journalist later replied with a public essay objecting to AI-written pitches. The identity, direct correspondence, signature, and contact details remain private; the response is classified only as an outreach-method objection, not coverage or technical corroboration.

## E-09 — Anthropic-approach audit and adapted artifacts

**Public artifacts:** [`anthropic-approach-audit.html`](anthropic-approach-audit.html), [`authentication-path-audit.html`](authentication-path-audit.html), [`support-routing-cluster.html`](support-routing-cluster.html), [`account-framing-correction.html`](account-framing-correction.html), and [`regulator-attachment.pdf`](regulator-attachment.pdf)

The audit compares this package with the public Anthropic billing mirror at commit `58006ec`. It confirms that the Anthropic mirror published neither a journalist roster nor a numeric press-recipient total. A private Gmail cross-check found 82 distinct `tip`-subject destinations, but that set includes named reporters, newsrooms, tips desks, and consumer-media endpoints and is not represented as 82 individual journalists. The adapted path, routing, correction, and regulator artifacts fill applicable evidentiary functions without inventing independent coverage, a public vendor issue burst, or transaction evidence.

## E-10 — First-party linking terms and neutral preservation

**Public artifacts:** [Cursor's SuperGrok linking guide](https://cursor.com/help/grok-bot/supergrok) and [`archive-preservation.html`](archive-preservation.html)

Cursor's guide publicly confirms that individual SuperGrok Heavy qualifies, linking grants usage to one Cursor account even without a paid Cursor plan, the link is permanent, and unresolved access/email problems should be taken to support. Successful Wayback captures preserve that guide and xAI's eligibility FAQ as displayed on 2026-09-05 UTC.

The guide does not publish a same-email requirement or a `.ru`-domain exclusion. That absence is not proof that no internal rule exists and does not establish why this account was denied.

## Central inference boundary

The matching `.ru` address being the actual trigger for `policy_denied` is an evidence-based inference, not a confirmed vendor finding. Cursor is being asked to confirm or refute it and identify the real backend rule.
