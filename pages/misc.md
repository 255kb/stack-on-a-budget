# Misc

<!-- TOC depthFrom:2 -->

- [APIVerve](#apiverve)
- [Argonaut](#argonaut)
- [Datacircle](#datacircle)
- [ExchangeRate-API](#exchangerate-api)
- [FingerprintJS Pro](#fingerprintjs-pro)
- [FXMacroData](#fxmacrodata)
- [Geocodio](#geocodio)
- [Indexed](#indexed)
- [ipapi.is](#ipapiis)
- [Let's Encrypt](#lets-encrypt)
- [ostr.io](#ostrio)
- [QRMint](#qrmint)
- [Svix](#svix)
- [Taskade](#taskade)

<!-- /TOC -->

## APIVerve

[APIVerve](https://apiverve.com/?utm_source=stack-on-a-budget)

- _Free Tier_: 1,000 free tokens per month, a free mock endpoint, and a free JSON bin
- _Pros_: High quality curated APIs to help build your next project, 1 API Key gives you access to all APIs
- _Limitations_: Free tier has rate limits, and some API features are locked down on the free tier
- _Exceeding the free tier_: API calls return an error

## Argonaut

[Argonaut](https://argonaut.dev/?utm_source=stack-on-a-budget&utm_medium=rsrc)

- _Free Tier_: Unlimited apps and deployments for 5 environments and 2 users
- _Pros_: App deployment and infrastructure management in one place, bring your own cloud
- _Limitations_: Currently support only AWS
- _Exceeding the free tier_: Can continue using; our team will reach out

## Datacircle

[Datacircle pricing](https://docs.datacircle.dev/pricing)

- _Free Tier_: Sign up at datacircle.dev with your work email: a $5 credit, that's 2,105 LinkedIn profiles at $2.375 per 1,000. Free: 10M+ U.S. B2B leads, as a flat file. Download it at datacircle.dev.
- _Pros_: Query your favorite B2B data APIs through us. Same request, same price, no markup. You send the provider's own request to api.datacircle.dev, with your Datacircle key. That's the only change.
- _Limitations_: The $5 credit is given once per workspace and never expires. Right now we have 3 live LinkedIn profile APIs that we trust: Up2Data, HarvestAPI and Fetchin.
- _Exceeding the free tier_: A call your balance can't cover answers 402. Add funds, from $5, on your dashboard.
- _Credit card required_: No

## ExchangeRate-API

[Home page](https://www.exchangerate-api.com)

- _Free tier_: Free JSON currency conversion rate dataset
- _Pros_: No request limits, multiple data sources
- _Limitations_: Only updated every 24 hours

## FingerprintJS Pro

[Pricing page](https://fingerprintjs.com/pricing/)

- _Free tier_: up to 1000 unique visitors per month
- _Pros_: identifies browser and hybrid mobile application users even when they purge data
- _Limitations_: the rate limit is reduced to 3 identifications per second
- _Exceeding the free tier_: the SDK returns an error

## FXMacroData

[Free access docs](https://fxmacrodata.com/documentation/rate-limits?utm_source=github&utm_medium=referral&utm_campaign=stack-on-a-budget&utm_content=readme)

- _Free tier_: No key, account or card. USD macroeconomic releases (CPI, payrolls, GDP, policy rate and others) for the most recent 90 days, the USD release calendar, USD COT positioning, USD central bank press releases, and the indicator catalogue for all 22 covered currencies. Fair use of 100 requests a day
- _Pros_: Data comes straight from the official publishers (central banks and statistics agencies) and every release row carries its publication timestamp, which helps with point-in-time checks. Plain JSON over REST. A hosted MCP server is also available, and its USD release, calendar and catalogue tools work without a key too
- _Limitations_: Keyless releases become readable 15 minutes after publication. Other currencies, FX rates, commodities and history older than 90 days need a key. CORS is not enabled, so call it from a server
- _Exceeding the free tier_: Routes outside the free set return `401 api_key_required` with a subscribe link; a trial or paid key unlocks them
- _Credit card required_: No

## Geocodio

[Home page](https://www.geocod.io)

- _Free tier_: 2,500 lookups per day
- _Pros_: Forward and reverse geocoding, supports data appends such as Census data, congressional districts and timezones
- _Limitations_: Only covers US and Canada

## Indexed

[API docs](https://indexed.vc/docs/api)

- _Free tier_: An API key with no card required, 25 searches a day (company and investor search by name or website domain) and 25 credits a month for full company records with funding rounds and investors (3 credits each). `GET /api/v1/industries` needs no key
- _Pros_: Look up a company by website domain, one at a time or up to 100 per batch. Domains that are not in the database return a coverage status and cost nothing. OpenAPI 3.1 spec
- _Limitations_: Free keys cannot use bulk enrichment, webhooks or sorted listing. CORS is not enabled, so call it from a server
- _Exceeding the free tier_: Past 25 searches a day the API returns `429 SEARCH_QUOTA_EXCEEDED` until 00:00 UTC. When the monthly credits run out it returns `402 CREDIT_LIMIT_REACHED` with upgrade links, and paid plans raise both limits
- _Credit card required_: No

## ipapi.is

[Home page](https://ipapi.is/)

- _Free tier_: 1,000 API lookups per day
- _Pros_: The free tier includes full API output with all data types. The API is replicated on mutiple servers worldwide which results in a fast performance.
- _Limitations_: No limits
- _Exceeding the free tier_: need to pay if 1,000 free daily API lookups are exceeded

## Let's Encrypt

[Home page](https://letsencrypt.org/)

- _Free tier_: provide SSL certificates for free
- _Pros_: free, support for wildcard certificates
- _Limitations_: certificates are valid for 90 days so automation is strongly recommended

## ostr.io

[Pricing page](https://ostr.io/info/pricing)

- _Free tier_: up to 240 prerenders, 400 monitoring checks, 800 web-analytics requests, 400 web-CRON requests
- _Pros_: simple and easy to use, "one click" setup for Monitoring and Domains Protection, Prerendering supports ES6 (ECMAScript 2015)
- _Limitations_: No limits
- _Exceeding the free tier_: need to pay, Domain Names Protections continues to work as it's free for all accounts on all plans

## QRMint

[Home page](https://qrmint.dev)

- _Free tier_: Free QR code generation API with no authentication required
- _Pros_: Generate QR codes for any content via a simple API call; supports multiple output formats; no API key or signup needed
- _Limitations_: Rate limited on the free tier
- _Credit card required_: No

## Svix

[Pricing page](https://www.svix.com/pricing/)

- _Free tier_: 50,000 webhook messages/month, 7 day data retention, unlimited environments
- _Pros_: super easy to ship a reliable, scalable webhook service with automatic retries, HMAC signatures, etc.
- _Limitations_: rate limited to 10 messages/second
- _Exceeding the free tier_: need to pay but service will continue working and a sales rep will reach out

## Taskade

[Home page](https://taskade.com)

- _Free tier_: 1 workspace, unlimited tasks, lists, and collaborators
- _Pros_: Simple and real-time task management
- _Limitations_: No limits
- _Exceeding the free tier_: need to pay, will included unlimited workspaces, file uploads, and more advanced features
