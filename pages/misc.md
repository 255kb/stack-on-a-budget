# Misc

<!-- TOC depthFrom:2 -->

- [APIVerve](#apiverve)
- [Argonaut](#argonaut)
- [Equibles](#equibles)
- [ExchangeRate-API](#exchangerate-api)
- [Fair Value Calculator](#fair-value-calculator)
- [FingerprintJS Pro](#fingerprintjs-pro)
- [Free LLM API Hub](#free-llm-api-hub)
- [FXMacroData](#fxmacrodata)
- [Geocodio](#geocodio)
- [Indexed](#indexed)
- [ipapi.is](#ipapiis)
- [Kite](#kite)
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

## Equibles

[Pricing page](https://equibles.com/pricing)

- _Free tier_: 100 requests a day, shared between the hosted MCP server and the REST API. Covers SEC filings with full-text search, XBRL financial statements, earnings call transcripts, insider and congressional trades, 13F institutional holdings, ETF and fund holdings, and end-of-day stock prices. ChatGPT and Claude can connect over OAuth without an API key
- _Pros_: Filing data comes from SEC filings and company releases, and answers link back to the source document. The same data is reachable over MCP for AI assistants and over plain JSON REST with an API key; CORS is enabled
- _Limitations_: End-of-day prices only; option chains and delayed or real-time quotes need a paid plan. The daily counter resets at 00:00 UTC
- _Exceeding the free tier_: The REST API returns `429` and the MCP server replies that the daily cap is reached until the counter resets; there are no overage charges
- _Credit card required_: No

## ExchangeRate-API

[Home page](https://www.exchangerate-api.com)

- _Free tier_: Free JSON currency conversion rate dataset
- _Pros_: No request limits, multiple data sources
- _Limitations_: Only updated every 24 hours

## Fair Value Calculator

[Developer page](https://fairvalue-calculator.com/developers)

- _Free tier_: No key, account or card for the data files: five daily-updated stock lists (undervalued stocks, overvalued stocks, value traps, largest companies, top 150 companies) as JSON and CSV under CC BY 4.0. The hosted MCP server for ChatGPT, Claude and other assistants works with a free account over OAuth, without an API key: 3 full fair-value verdicts and 30 quick snapshots a day, unlimited stock search, 5 comparisons or screens a day
- _Pros_: Covers 40,000+ listed stocks worldwide, recalculated daily from 26 valuation models; each verdict carries a fair-value range, a quality score and the 12-month trend. CORS is enabled on the JSON files, and the datasets are also archived on Zenodo with a DOI
- _Limitations_: Valuations, not market data: no price quotes or price history. The data files are fixed lists, not a per-ticker REST API; single-stock lookups go through the MCP server
- _Exceeding the free tier_: The MCP server answers with the status `free_daily_limit_reached` and no valuation until the counter resets at 00:00 UTC; a paid plan raises the limits. The data files have no daily quota, only a general rate limit
- _Credit card required_: No

## FingerprintJS Pro

[Pricing page](https://fingerprintjs.com/pricing/)

- _Free tier_: up to 1000 unique visitors per month
- _Pros_: identifies browser and hybrid mobile application users even when they purge data
- _Limitations_: the rate limit is reduced to 3 identifications per second
- _Exceeding the free tier_: the SDK returns an error

## Free LLM API Hub

[Website and API docs](https://freellmapihub.com)

- _Free tier_: the full dataset of free-tier and trial-credit LLM API offers from 60+ providers as a no-auth CORS JSON API, CSV, llms.txt and RSS feed (MIT-licensed data)
- _Pros_: every entry is dated and linked to the provider's own docs, compare pages per provider, changes published as RSS
- _Limitations_: it is a dataset, not an inference API; read-only
- _Exceeding the free tier_: no quota, the files are static
- _Credit card required_: No

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

## Kite

[Kite](https://kite.new/pricing)

- _Free Tier_: Unlimited editors and viewers, 1 workspace with 3 files and 3 design systems, 100 agent actions a day
- _Pros_: UI design canvas that coding agents (Claude, ChatGPT, Cursor, Codex) edit through a hosted MCP server; frames copy out as HTML, React or Tailwind; no AI credits, the agent runs on your own plan
- _Limitations_: 3 files on the free plan; no version history
- _Exceeding the free tier_: Pro plan needed for more files or unlimited agent actions

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
