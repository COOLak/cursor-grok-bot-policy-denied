# Affected-user evidence checklist

Use this checklist if the same Grok Bot / SuperGrok flow fails for you. Share aggregates and redacted screenshots publicly; keep account, session, and payment identifiers private.

## Record the plan and route

- Plan name and whether it is currently paid.
- Whether Grok is accessed through X, Google, Apple, GitHub, or email.
- Whether Cursor shows **Get access with SuperGrok Heavy**.
- Whether the identity-provider consent page appears.
- The exact visible error text and error code.
- UTC time of the attempt.

## Preserve private technical evidence

- Full callback URL, including state/session values, in a private record only.
- Original screenshots before redaction.
- Browser and operating-system version.
- Whether a VPN, proxy, corporate gateway, or travel context was present.
- Cursor account type and whether its email exactly matches the paid identity.
- Any prior or partial Grok Bot link.
- Support replies and their timestamps.

## Safe public report

It is usually safe to publish:

- plan name;
- email-domain suffix only, if relevant;
- error code and visible message;
- high-level route taken;
- dates and support outcomes; and
- redacted screenshots that contain no account, ticket, OAuth, payment, or network identifiers.

Do not publish complete email addresses, ticket IDs, callback/session values, cookies, access tokens, invoice details, IP addresses, identity documents, or unredacted message headers.

## Questions to answer

1. Did authorization fail before or after the identity provider consented?
2. Did a fresh session change the result?
3. Did Cursor confirm a same-email requirement?
4. Can a new matching personal account be created?
5. Is an irreversible link already present or only warned about?
6. Did support provide a backend reason or only routing language?
7. Was the paid benefit delivered, replaced, refunded, or credited?

## Comparable-report boundary

A similar public report is corroborating context, not proof of a common backend rule. Do not aggregate people or alleged losses without deduplicating sources and preserving each report's limitations.
