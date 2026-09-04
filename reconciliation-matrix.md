# Grok Bot access reconciliation matrix

| Observed state | System or owner to inspect | Evidence available | Required answer | Resolution test |
|---|---|---|---|---|
| SuperGrok Heavy is paid and publicly listed as including Grok Bot | xAI plan and entitlement service | Public announcement; private subscription proof | Is this identity entitled, and what restrictions apply? | Entitlement is accepted by Cursor or a documented billing remedy is provided. |
| X/xAI consent page is reached and approved | xAI OAuth and Cursor OAuth client | Private authorization screenshot and digest | Did xAI issue a valid authorization result to Cursor? | Fresh authorization completes without partner rejection. |
| Cursor callback returns `policy_denied` | Cursor callback policy engine | Visible error, private callback record, support history | Which exact rule and attributes produced the denial? | The rule is corrected or a supported alternative is documented. |
| Cursor says emails must match | Cursor identity/account model | Private support correspondence | What exact normalized identifier must match, and can the `.ru` address be used? | Matching account is visibly confirmed before link completion. |
| New matching personal account cannot be completed | Cursor signup/eligibility/risk systems | Reproduced failure sequence | Is the address, domain, geography, or another attribute blocked? | Matching personal account can be created and used. |
| Successful links are permanent | Cursor/xAI link registry | Cursor support statement | Is there an existing, reserved, partial, or failed link record? | Link state is confirmed safe before irreversible completion. |
| Backend-settings refresh changed nothing | Cursor configuration and cache layers | Before/after retry result | What was refreshed, and why did the same denial persist? | New configuration produces a successful verified result. |
| xAI sends the case to Cursor and Cursor automation closes the transfer as duplicate | Cross-company support routing | Authenticated private correspondence | Who owns the technical and billing decision? | One human owner accepts and resolves the case. |
| Advertised paid feature remains unavailable | Cursor/xAI billing and consumer-remedy owners | Public plan claim and unresolved entitlement | What refund, credit, or alternative is offered if access is intentionally unavailable? | Benefit delivered or written remedy completed. |

## Central contradiction

The customer can authenticate the paid identity and approve Cursor's request, yet the partner callback denies the entitlement and no supported matching-account path is provided.

## Evidence boundary

The matrix maps observations to systems that can answer them. It does not prove that `.ru` is the policy trigger, identify a legal basis, establish sanctions treatment, or assign fault between Cursor and xAI.
