# Static app hosting

<!-- TOC depthfrom:2 -->

- [Static app hosting](#static-app-hosting)
  - [AWS S3](#aws-s3)
  - [Cloudflare Pages](#cloudflare-pages)
  - [deed.page](#deedpage)
  - [Firebase hosting](#firebase-hosting)
  - [GitHub Pages](#github-pages)
  - [GitLab Pages](#gitlab-pages)
  - [Netlify](#netlify)
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

## Cloudflare Pages

[pricing page](https://pages.cloudflare.com)

* *Free tier*: Unlimited sites, Unlimited requests, Unlimited bandwidth, 1 concurrent build, 500 builds per month

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
