# Static app hosting

<!-- TOC depthfrom:2 -->

- [Static app hosting](#static-app-hosting)
  - [AWS S3](#aws-s3)
  - [Cloudflare Pages](#cloudflare-pages)
  - [Firebase hosting](#firebase-hosting)
  - [GitHub Pages](#github-pages)
  - [GitLab Pages](#gitlab-pages)
  - [Netlify](#netlify)
  - [Render](#render)
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

[Product page](https://www.netlify.com/features) / [Pricing page](https://www.netlify.com/pricing/)

* *Free tier*: Unlimited sites, Custom domain, Automatic HTTPS, Open source projects get [pro plan for free](https://www.netlify.com/blog/2016/07/28/netlifys-pro-plan-now-free-for-open-source-projects/)
* *Pros*: Deployment with git, Custom redirect rules, Webhooks and Notifications for integration with third party services, Form handling, User authentication handling, CMS

## Render

[Pricing page](https://render.com/pricing)

* *Free tier*: 100GB outbound bandwidth per month (unlimited inbound)
* *Pros*: Includes CDN, Deploy with git, Custom domains, Automatic HTTPS
* *Limitations*: Free tier does not allow GitHub actions to track deployments. You can use [this tool](https://github.com/marketplace/actions/render-github-action) instead.

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
