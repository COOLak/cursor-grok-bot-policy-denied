# September 9: the matching-email signup attempt also fails

> **September 11 support correction:** Cursor now says different emails can link and attributes this case to a .ru domain restriction. On September 12, the customer clarified that the long-standing email and X-authenticated Grok identity must remain unchanged; changing the address is not an acceptable resolution. No supported remedy has been verified. [Read the correction and September 12 follow-up](support-correction-20260911.html). Earlier statements and downloadable packets are historical snapshots.

## Latest support response — September 10, 20:57 UTC

[Cursor has replied, but no working usage-grant path has been verified](support-response-20260910.html). The response rejects linking the different-email account and says the matching login cannot be created from this ticket. This does not confirm a blanket domain ban. One factual clarification was sent in the original case.

Published 2026-09-09 UTC. The incident remains unresolved.

The customer reports never having had a Cursor account under the `.ru` address used by the paid X/xAI identity. Creating a new personal account with that matching address is acceptable; keeping the earlier non-matching Cursor account is not a requirement.

## New evidence

On September 9 the customer supplied a phone screenshot of a password-signup attempt. The customer reports attempting account creation without the SuperGrok authorization button. The screenshot visibly contains:

- Heading: “Create a Grok Bot account”
- An email field containing the matching `.ru` address (withheld here)
- “Continue with email code”
- Error: “Access blocked, please contact support.”
- A masked password field and a “Continue” button

This is a transcription of selected visible text, not a replacement or altered screenshot. The original is retained privately because it contains the full account address and other private interface details.

**Original SHA-256:** `b1f117e920c40d62ef9b298235c6d3b07526b8169cb50804e770265a1bc01bf9`  
**Original size:** 246,537 bytes. Evidence reference: E-10.

## Important route correction

The supplied URL has host `authenticator.cursor.sh`, path `/sign-up/password`, and a `redirect_uri` pointing to `https://cursor.com/api/auth/bot/callback`. Its nonce, state and authorization-session values are withheld.

That bot callback agrees with the screenshot's Grok Bot heading. This evidence supports a blocked password-signup attempt in the Grok Bot authentication context. It does **not** establish that ordinary Cursor signup, independent of the bot flow, was tested and blocked. The screenshot does not show a `policy_denied` code; that code belongs to the previously recorded authorization/callback failure.

The customer's account-creation history and use of the phone are customer reports. The visible heading/error and supplied URL's route are directly inspectable evidence. This is not a controlled email-domain comparison or proof of the internal rule. No claim is made that this phone attempt was VPN-free.

## What Cursor needs to answer

1. At which account-creation step is this identity denied, and which rule caused it?
2. Is the exact email domain or the `.ru` suffix a factor, or is another account, network or eligibility signal responsible?
3. What supported route creates the intended matching personal account and grants the advertised benefit without consuming a permanent link on an unintended identity?

The `.ru` trigger remains a hypothesis, not a vendor-confirmed policy or a finding of unlawful discrimination. A working access path is still the requested outcome. If it cannot be supplied, the customer seeks a written explanation and an appropriate remedy for the unavailable advertised benefit—not an unsupported claim that the entire subscription was unusable.

[Evidence hub](https://coolak.github.io/cursor-grok-bot-policy-denied/) · [Timeline](timeline.md) · [Account-framing correction](account-framing-correction.md)


## Later September 9: transient email-code verification error (E-11)

After selecting “Continue with email code,” the customer supplied a second phone screenshot showing **“Unable to verify the user is human.”** The customer reports that no CAPTCHA challenge was displayed, that they were in Japan, and that their Cursor account created with a Gmail address works. These are additional customer-reported comparison facts, not a controlled same-session test with only the email domain varied.

The new error records a failed human-verification step, not proof that the customer was classified as a bot. A page may perform background verification or fail before displaying a challenge; this screenshot does not identify the provider, cause, or relationship to the access denial. The working account makes a universal Cursor outage less plausible, but does not establish the precise account/email restriction. The .ru trigger is still unconfirmed.

Private original: 246,364 bytes. SHA-256: `b2cdd763aa38a08e74128c07dfa80c9ecd2e2c255788aaf14f8baf623431fa5d`. Cursor is asked to compare the working account with the failed matching-email signup and investigate both errors. No challenge bypass was attempted.


## Latest September 9 correction: refresh returns to the original access block

After refreshing the page and requesting an email code again, the customer reports that “Unable to verify the user is human” disappeared and **“Access blocked, please contact support” returned**. The customer attributes the temporary verification error to a timeout. The refresh result is consistent with a transient or stale verification state, but the server-side cause has not been verified. E-11 remains historical evidence; it must not be presented as a second continuing barrier. The unresolved issue is the persistent access block on the matching-email signup path.

## Escalation status

A factual update was sent to the original Cursor support case on September 9. An FTC consumer report was submitted and its on-screen receipt verified. The private report number and contact details are withheld. FTC intake is not a finding against either vendor, a confirmed investigation, or a promise of individual redress. The later refresh clarification was sent to Cursor and submitted to the FTC as a linked supplement referencing the original report, following the FTC FAQ. Its receipt was also verified. This is one incident with a clarification, not two separate losses.

A private inquiry was sent to a local consumer-affairs office in Japan asking how to submit written evidence. At 05:55 UTC on September 9, a local consumer-affairs office in Japan replied that it cannot negotiate with overseas sellers over directly purchased digital services. It referred the customer to the National Consumer Affairs Center's Cross-border Consumer Center Japan (CCJ) from September 14. This is a routing response, not complaint acceptance, a finding against either vendor, or a remedy.

The [Reddit update](https://www.reddit.com/r/cursor/comments/1w6p3gi/comment/p8ocwis/) and [X update](https://x.com/Coolak777/status/2097524420579570096) were published and verified. No new press distribution is claimed; the existing outreach-method hold remains.

## Evidence distribution checkpoint — 06:49 UTC

The September 9 signup evidence page has been sent to 16 destinations: 11 new contacts across batches six and seven, and five eligible earlier recipients. Of the original 48, 43 have not received this addendum; one is excluded following an objection, leaving 42 eligible recipients for staged distribution. Sent records establish dispatch, not inbox delivery or readership. See the [outreach record](press-outreach.html). No count-only broadcast was sent.

## Evidence distribution checkpoint — September 10, 15:15 UTC

The September 9 signup evidence page has been dispatched to 26 counted destinations: 21 new contacts across batches six through nine, plus five eligible earlier recipients. One earlier failed address is excluded. Of the original 48, one is excluded following an objection and 42 remain eligible for a staged addendum. Sent records establish dispatch, not inbox delivery or readership. See the [outreach record](press-outreach.html). One failed address was not counted; this bookkeeping was not rebroadcast.
