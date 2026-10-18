# Security

<!-- TOC depthFrom:2 -->

- [IPASIS](#ipasis)
- [Snyk](#snyk)
- [Vetto](#vetto)

<!-- /TOC -->

## IPASIS

[Pricing page](https://ipasis.com/#pricing)

- *Free tier*: 1,000 API requests/day for real-time bot detection, IP reputation scoring, VPN/proxy/Tor detection, and email validation. Single REST endpoint returns an Interaction Trust Score (0-100).
- *Pros*: sub-20ms response time, combines IP intelligence and email risk in one call, simple JSON API with no SDK required, live scanner tool at ipasis.com/scan
- *Limitations*: free tier limited to 1,000 requests/day
- *Exceeding the free tier*: API returns a rate limit error; paid plans available for higher volumes
- *Credit card required*: No

## Snyk

[Pricing page](https://snyk.io/plans/)

- *Free tier:* 200 open source tests, 100 container tests, 300 IaC tests, 100 Snyk Code tests - all per month.
- *Pros:* GitHub Pull Requests integration, IDE extensions, a CLI
- *Limitations:* No license reports, JIRA integrations, API or rich reports

## Vetto

[Pricing page](https://usevetto.com/#pricing)

- *Free tier*: 1 site, 1,000 email checks per month on signup forms (re-checking the same address doesn't count). Disposable and dead-domain blocking, "did you mean" fixes for typo'd emails, bot honeypot. Privacy relays (Apple Hide My Email, Firefox Relay, DuckDuckGo) are allowed.
- *Pros*: one script tag, no backend changes needed on the free tier, checks fail open so signups never break.
- *Limitations*: a small "Protected by Vetto" link is shown under its messages; Gmail alias detection, signed verdict tokens and the server-side API are paid features.
- *Exceeding the free tier*: checks are skipped and signups go through unchecked until the next month.
- *Credit card required*: No
