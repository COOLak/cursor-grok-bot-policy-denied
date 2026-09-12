# Grok Bot authentication-path audit

> **September 11 support correction:** Cursor now says different emails can link and attributes this case to a .ru domain restriction. On September 12, the customer clarified that the long-standing email and X-authenticated Grok identity must remain unchanged; changing the address is not an acceptable resolution. No supported remedy has been verified. [Read the correction and September 12 follow-up](support-correction-20260911.html). Earlier statements and downloadable packets are historical snapshots.

## Result

The observed failure occurs **after** the customer starts from Cursor's Grok Bot sign-in surface and successfully reaches the X/xAI authorization stage. The return to Cursor carries `policy_denied`, and the public Grok Bot page then displays **“Access blocked, please contact support.”**

## Public-safe path

| Step | Observed state | What it establishes | What it does not establish |
| --- | --- | --- | --- |
| 0. Published eligibility path | Cursor's public linking guide says individual SuperGrok Heavy qualifies and can grant usage to a Cursor account without a paid Cursor plan | The requested link class is publicly documented | Account-specific acceptance, a same-email rule, or `.ru` support |
| 1. Grok Bot sign-in | “Get access with SuperGrok Heavy” is visible | Cursor exposes the paid-plan linking route | Eligibility for this account |
| 2. X/xAI authorization | Cursor consent request appears for the already signed-in X identity | Identity-provider login and consent routing are reachable | Cursor acceptance of the identity |
| 3. Callback | Cursor receives a callback containing `policy_denied` | The denial is returned at the vendor integration boundary | The undisclosed backend rule that caused it |
| 4. Visible result | “Access blocked, please contact support” appears | Reproducible product-level failure | Whether `.ru` is the actual server-side trigger |
| 5. Fresh retries and network checks | VPN/proxy disabled; ordinary connectivity works; retries do not change the result | A simple transient browser or tunnel failure was not found | Every possible client, network, fraud, or policy signal |
| 6. Cursor settings refresh | Support reports a backend refresh; live retry remains blocked | The reported refresh did not restore access | What settings changed or whether the intended account was affected |

## Central boundary

The `.ru` email-domain trigger is a customer inference based on the repeated failure and support discussion. Cursor has not confirmed the precise backend policy. Its public linking guide does not publish the privately stated same-email requirement or a `.ru`-domain exclusion. That absence does not prove no internal restriction exists. OAuth state, authorization-session values, complete account addresses, cookies, tokens, IP data, and unredacted screenshots are withheld.

## Required vendor record

Cursor and xAI can resolve the remaining uncertainty by naming the technical owner and disclosing the evaluated account class, domain/region rule, entitlement result, prior-link state, and safe supported retry path. A generic support transfer does not answer those questions.


## September 9 signup evidence and route correction

The customer reports never having had a Cursor account under the matching .ru address. A new phone password-signup attempt displayed “Create a Grok Bot account” and “Access blocked, please contact support.” The supplied route redirects to the bot callback: this is not proof of a separate ordinary Cursor signup failure. The .ru trigger is still unconfirmed. [Read the new evidence, original checksum and limitations](mobile-signup-20260909.md).
