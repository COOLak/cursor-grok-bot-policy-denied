# Grok Bot authentication-path audit

## Result

The observed failure occurs **after** the customer starts from Cursor's Grok Bot sign-in surface and successfully reaches the X/xAI authorization stage. The return to Cursor carries `policy_denied`, and the public Grok Bot page then displays **“Access blocked, please contact support.”**

## Public-safe path

| Step | Observed state | What it establishes | What it does not establish |
| --- | --- | --- | --- |
| 1. Grok Bot sign-in | “Get access with SuperGrok Heavy” is visible | Cursor exposes the paid-plan linking route | Eligibility for this account |
| 2. X/xAI authorization | Cursor consent request appears for the already signed-in X identity | Identity-provider login and consent routing are reachable | Cursor acceptance of the identity |
| 3. Callback | Cursor receives a callback containing `policy_denied` | The denial is returned at the vendor integration boundary | The undisclosed backend rule that caused it |
| 4. Visible result | “Access blocked, please contact support” appears | Reproducible product-level failure | Whether `.ru` is the actual server-side trigger |
| 5. Fresh retries and network checks | VPN/proxy disabled; ordinary connectivity works; retries do not change the result | A simple transient browser or tunnel failure was not found | Every possible client, network, fraud, or policy signal |
| 6. Cursor settings refresh | Support reports a backend refresh; live retry remains blocked | The reported refresh did not restore access | What settings changed or whether the intended account was affected |

## Central boundary

The `.ru` email-domain trigger is a customer inference based on the repeated failure and support discussion. Cursor has not confirmed the precise backend policy. OAuth state, authorization-session values, complete account addresses, cookies, tokens, IP data, and unredacted screenshots are withheld.

## Required vendor record

Cursor and xAI can resolve the remaining uncertainty by naming the technical owner and disclosing the evaluated account class, domain/region rule, entitlement result, prior-link state, and safe supported retry path. A generic support transfer does not answer those questions.

