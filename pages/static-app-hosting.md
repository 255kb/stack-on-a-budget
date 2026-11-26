# Static app hosting

<!-- TOC depthfrom:2 -->

- [Static app hosting](#static-app-hosting)
  - [AWS S3](#aws-s3)
  - [Birta](#birta)
  - [BrewPage](#brewpage)
  - [Cloudflare Pages](#cloudflare-pages)
  - [Convika](#convika)
  - [deed.page](#deedpage)
  - [Firebase hosting](#firebase-hosting)
  - [GitHub Pages](#github-pages)
  - [GitLab Pages](#gitlab-pages)
  - [Netlify](#netlify)
  - [Pagehaus](#pagehaus)
  - [Reliant](#reliant)
  - [Render](#render)
  - [Catalyst Slate](#catalyst-slate)
  - [Shipvela](#shipvela)
  - [Surge](#surge)
  - [Vercel](#vercel)

<!-- /TOC -->

## AWS S3

[Pricing page](https://aws.amazon.com/s3/pricing/)

* *Free tier*: 5 GB of storage, 20000 GET requests, 2000 PUT requests, 15 GB data transfer per month
* *Pros*: ACL policies, Custom rules and MIME types, Supports expiration, Multiple regions world-wide
* *Limitations*: Free only for 12 months

## Birta

[HTML to website](https://birta.dev/tools/html-to-website) / [Pricing](https://birta.dev/#pricing)

* *Free tier*: 20 projects, 25 MB per published version, HTTPS address per project, custom domain, form submissions, version history with rollback, visitor stats, up to 3 collaborators
* *Pros*: Paste HTML or drop an .html file and get a link that opens for 24 hours with no account; keep it in an account and it becomes a site at a permanent address. Multi-file sites publish as a folder from an account or from an AI agent over MCP; reviewers leave remarks right on the page
* *Limitations*: Static files only (no server code); a small Birta mark on free sites; the no-account link expires after 24 hours and is closed to search engines
* *Exceeding the free tier*: A new project or a version over 25 MB is refused; live sites keep working; nothing is charged
* *Credit card required*: No

## BrewPage

[Product page](https://brewpage.app) / [API docs](https://brewpage.app/api)

* *Free tier*: HTML and Markdown pages up to 5 MB, multi-file static sites up to 20 MB (200 files, 5 MB per file), files up to 5 MB (video 20 MB), JSON documents and key-value values up to 1 MB, automatic HTTPS link for every publication
* *Pros*: Publish with one HTTP POST (no signup, no API key), the returned owner token updates the content at the same URL, optional password protection, unlisted links or a public gallery, MCP server (20 tools, remote or npm `brewpage-mcp`) for AI agents, GitHub Action, OpenAPI contract
* *Limitations*: Every publication expires (default 15 days, maximum 30 days, 90 days with a free account) and is then deleted; static files only (server code such as PHP is never executed); no custom domains; per-IP rate limits with no published figure
* *Exceeding the free tier*: The API returns an error (`400` naming the limit, `413` for a request over 25 MiB, `429` with `Retry-After`); nothing is charged
* *Credit card required*: No (no account needed either)

## Cloudflare Pages

[pricing page](https://pages.cloudflare.com)

* *Free tier*: Unlimited sites, Unlimited requests, Unlimited bandwidth, 1 concurrent build, 500 builds per month

## Convika

[Pricing page](https://convika.com/pricing/) / [Docs](https://convika.com/docs/)

* *Free tier*: 1 published page at a time (10 kept with drafts), 10,000 page views a month, 50 form entries shown a month, 1 custom subdomain with automatic HTTPS, visitor analytics for the last 90 days, HTML uploads up to 2 MB
* *Pros*: Upload an .html file, a folder or a .zip in the browser, or publish from an MCP client (Claude, Claude Code, Codex) at `https://mcp.convika.com`; forms that store entries (CSV/JSON export) and visitor analytics are built in; commercial use is allowed on the free plan
* *Limitations*: One published page at a time on the free plan; a small Convika bar at the bottom of each page on the free plan
* *Exceeding the free tier*: Past 10,000 page views in a month, editing and analytics pause, and pages stop 7 days later until the month ends (UTC) or a plan is bought; nothing is charged
* *Credit card required*: No

## deed.page

[Pricing page](https://deed.page/pricing) / [API docs](https://deed.page/docs)

* *Free tier*: 25 sites, 25 MB per site, 60 publishes per hour, last 10 versions kept per site, 1 custom domain, 1 webhook, automatic HTTPS on `<slug>.deed.page`
* *Pros*: Publish a single HTML file or a tarball of prebuilt files with one HTTP PUT (no CLI, no git, no build step), you choose the subdomain, the first publish returns a token that updates the same URL later, version history with rollback, remote MCP server for AI coding agents, cookieless per-site analytics
* *Limitations*: Static files only (no server-side code or databases), one request body is capped at 4 MB (larger sites use a manifest upload), no password protection on the free tier, no dashboard (API and MCP only), a lost token can only be recovered if a recovery email was attached
* *Exceeding the free tier*: The API returns an error (`403 quota_sites`, `413 quota_bytes` or `429 rate_limited`) and existing sites stay online; nothing is charged automatically
* *Credit card required*: No (no account or email needed either)

## Firebase hosting

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1GB storage, 10GB/month transfer, Custom domain and HTTPS
* *Pros*: Includes CDN, Automatic HTTPS, Deployment versioning, URL rewriting (useful for HTML5 history API), Possible to define headers, Free web.app domain

## GitHub Pages

[Product page](https://pages.github.com/) / [More info](https://help.github.com/articles/what-is-github-pages/)

* *Free tier*: 1GB storage, 100GB bandwidth or 100K requests/month, 10 builds per hour
* *Pros*: Deploy with git, Provide automatic page generator, Automatic HTTPS
* *Limitations*: Only with GitHub

## GitLab Pages

[Product page](https://pages.gitlab.io/) / [More info](https://about.gitlab.com/2016/04/07/gitlab-pages-setup/)

* *Free tier*: Completely free for cloud hosted, self hosted version of Gitlab available
* *Pros*: Use any static website generator, Custom domains
* *Limitations*: Only works with GitLab, No automatic HTTPS

## Netlify

[Pricing page](https://www.netlify.com/pricing/)

* *Free tier*: Unlimited sites, Custom domain, Automatic HTTPS
* *Pros*: Deployment with git, Custom redirect rules, Webhooks and Notifications for integration with third party services, Form handling, User authentication handling, CMS

## Pagehaus

[Product page](https://pagehaus.app) / [Pricing](https://pagehaus.app/pricing)

* *Free tier*: 1 site at yourname.pagehaus.site with HTTPS, 250 MB storage, 20 GB of traffic a month, 50 contact form messages a month, 7 days of version history, cookie-free visitor stats
* *Pros*: Upload files, folders or a zip in the browser, over SFTP, with a command-line tool or a GitHub Action, or from Claude and ChatGPT over MCP; Server Side Includes for shared headers and footers; contact forms with no code; a Markdown blog with RSS; `_redirects` rules
* *Limitations*: Static files only (no server code); custom domains on paid plans (from $4/month); 25 MB per file; links on free sites are nofollow
* *Exceeding the free tier*: Uploads are refused when storage is full; sites keep running past the traffic allowance, with emails at 80% and 100%, and are paused only at three times the limit; nothing is charged
* *Credit card required*: No

## Reliant

[Pricing page](https://reliantlabs.io/pricing) / [Hosting docs](https://docs.reliantlabs.io/hosting/overview)

* *Free tier*: Any number of static sites in one organization per person (each environment is its own site), 1 GiB storage per site and 10 GiB in total, 10 GiB traffic per month, served through a CDN with HTTPS
* *Pros*: Deployed with the open-source forge CLI (`npx @reliantlabs/forge env deploy prod`), which adopts an existing Vite app or Next.js static export in place; a site can also be deployed with no account (`--claimable`), which returns a URL and a claim link
* *Limitations*: Static exports only on the free tier (backends and managed Postgres need billing); sites in a person's other organizations are queued until billing is set up; a deploy made without an account goes offline after 72 hours unless it is claimed
* *Exceeding the free tier*: Past 10 GiB of traffic the site answers 429 until the month rolls over; a release too large for the storage cap is held with a message
* *Credit card required*: No

## Render

[Pricing page](https://render.com/pricing)

* *Free tier*: 100GB outbound bandwidth per month (unlimited inbound)
* *Pros*: Includes CDN, Deploy with git, Custom domains, Automatic HTTPS
* *Limitations*: Free tier does not allow GitHub actions to track deployments. You can use [this tool](https://github.com/marketplace/actions/render-github-action) instead.

## Catalyst Slate

[Product & Pricing page](https://catalyst.zoho.com/slate/index.html?src=header)

* *Free tier*: 500 MB CDN storage, 300,000 requests, 100,000 ISR reads, 50,000 ISR writes, 25,000 GB-seconds function invocations, 72,000 GB-seconds build compute free per month
* *Pros*: No Credit card required to get started, Pay-as-you-go after free tier limit, Supports all major JS frameworks(React, Next.JS, Vue, Angular, and more), Git-based auto deploys from GitHub, GitLab, and Bitbucket, Automatic SSL provisioning and managed CDN, Rollback to any previous deployment, Instant live previews with code change.
* *Limitations*: Three preview deployments per app.

## Shipvela

[Product and pricing page](https://shipvela.com/#pricing) / [Deployment documentation](https://shipvela.com/docs)

* *Free tier*: 3 projects and 20 publishes per month, custom domains and managed HTTPS
* *Pros*: GitHub repository imports, CLI publishing of prebuilt static files, deployment history and build logs
* *Limitations*: Hobby supports static websites and React/Vite output; server-rendered Next.js requires a paid plan. CLI uploads are limited to 50 MB and 5,000 files. General backend servers and databases are not provisioned.
* *Exceeding the free tier*: New publishing is blocked until the monthly allowance resets or the account upgrades; no automatic overage charges
* *Credit card required*: No

## Surge

[Pricing page](http://surge.sh/pricing)

* *Free tier*: Unlimited deployments, Unlimited bandwidth, Automatic HTTPS
* *Pros*: Deploy from CLI, Custom 404 pages
* *Limitations*: No custom redirects in free tier, No custom domain in free tier

## Vercel

[Pricing Page](https://vercel.com/pricing)

* *Free tier*: Unlimited websites, Automatic HTTPS, Deployment with git, Analytics for 1 project, [sponsorship](https://vercel.com/support/articles/can-vercel-sponsor-my-open-source-project) for open source projects
* *Pros*: Various starter templates, DNS management, Edge CDN, first-class support for Next.js
* *Limitations*: Free tier does not allow commercial usage
