# September 9: the matching-email signup attempt also fails

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
