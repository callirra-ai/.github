# Security policy

## Reporting a vulnerability

Please report security issues **privately** — do not open a public issue, and do
not paste live credentials, tokens or customer data.

1. **Preferred:** open a private advisory — repository → **Security** tab → *Report a vulnerability*
2. **Email:** support@callirra.com with `[SECURITY]` in the subject

Please include: the surface you tested (web app, `api.callirra.com`, CLI/MCP, a
specific repository), reproduction steps, the impact you believe it has, and any
proof of concept. If secrets or personal data are needed to demonstrate the
issue, send the smallest possible redacted sample.

We aim to acknowledge within 3 business days and to keep you updated until the
issue is resolved. We do not run a paid bounty programme, but we are glad to
credit you in the fix notes if you would like that.

## In scope

- Accounts, sessions, 2FA and API keys (`sk-cal-…`)
- Credits, orders, refunds, subscriptions and payment-provider webhooks
- `api.callirra.com` — authentication, rate limiting, spend limits, model gating
- Prompt and reference-media handling, media storage access, watermark or entitlement bypass
- Code in this organization's repositories (CLI, MCP server, agent skill)

## Out of scope

- Vulnerabilities in third-party model providers, or in content those models generate
- Volumetric denial of service, spam and social engineering
- Automated-scanner output with no demonstrated impact
- Missing best-practice headers or configuration with no exploit path

## Safe harbour

Good-faith research is welcome. Keep it to accounts you own, do not access or
modify other people's data, do not degrade the service, and give us a reasonable
window to fix the issue before publishing. We will not pursue legal action for
research that follows this policy.
