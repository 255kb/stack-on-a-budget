# Static app hosting

<!-- TOC depthFrom:2 -->

- [AWS S3](#aws-s3)
- [Firebase hosting](#firebase-hosting)
- [GitHub Pages](#github-pages)
- [GitLab Pages](#gitlab-pages)
- [netlify](#netlify)
- [surge](#surge)

<!-- /TOC -->

## AWS S3

[Pricing page](https://aws.amazon.com/s3/pricing/)

* *Free tier*: 5 GB of storage, 20000 GET requests, 2000 PUT requests, 15 GB data transfer per month
* *Pros*: ACL policies, custom rules and MIME types, supports expiration, multiple regions world-wide
* *Limitations*: Free for only 1st year for new customers
* *Exceeding the free tier*: As cheap as USD 0.026 per GB per month

## Firebase hosting

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1GB storage, 10GB/month transfer, custom domain and SSL
* *Pros*: includes CDN, auto provisioned SSL, deployment versioning, custom domain, URL rewriting (useful for HTML5 history API), possibility to define headers

## GitHub Pages

[Product page](https://pages.github.com/) / [More info](https://help.github.com/articles/what-is-github-pages/)

* *Free tier*: 1GB storage, 100GB bandwidth or 100K requests/month, 10 builds per hour
* *Pros*: deploy by pushing on a repository branch (`gh-pages`), provide automatic page generator, support HTTPS (on github.io), supports custom domains
* *Limitations*: no HTTPS for custom domains (to solve this, use in combination with [Cloudflare](#cloudflare))

## GitLab Pages

[Product page](https://pages.gitlab.io/) / [More info](https://about.gitlab.com/2016/04/07/gitlab-pages-setup/)

* *Free tier*: Completely free for cloud hosted, self hosted version of Gitlab available
* *Pros*: Use any static website generator, connect your custom domain(s) and TLS certificates

## netlify

[Pricing page](https://www.netlify.com/pricing/)

* *Free tier*: Unlimited sites, custom domain and SSL
* *Pros*: offers continuous deployment, custom redirect rules, git repositories integration, webhooks and notifications (for integration with third parties services)

## surge

[Pricing page](http://surge.sh/pricing)

* *Free tier*: unlimited deployments, custom domain and basic SSL
* *Pros*: deploy from CLI, custom 404 pages
* *Limitations*: no custom redirects or http->https redirection in free tier
