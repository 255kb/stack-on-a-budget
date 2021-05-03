# Static app hosting

<!-- TOC depthFrom:2 -->

- [AWS S3](#aws-s3)
- [DocEvent](#docevent)
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

## DocEvent

[pricing page](https://docevent.io/pricing/)

* *Free tier*: Lets you transfer 200MB of FTP or sftp data, and 5000 operations, 5 accounts/users max
* *Pros*: Free ftp and sftp server, 3 regions, us-east-1, eu-west-1, ap-southeast-2, don't need to host any servers
* *Limitations*: The backend is your own S3 (or Azure Blob/Files or GCP) bucket, but this can also be free
* *Exceeding the free tier*: You can no longer login to the FTP service if you go over your free tier allowance

## Firebase hosting

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1GB storage, 10GB/month transfer, custom domain and SSL
* *Pros*: includes CDN, auto provisioned SSL, deployment versioning, custom domain, URL rewriting (useful for HTML5 history API), possibility to define headers

## GitHub Pages

[Product page](https://pages.github.com/) / [More info](https://help.github.com/articles/what-is-github-pages/)

* *Free tier*: 1GB storage, 100GB bandwidth or 100K requests/month, 10 builds per hour
* *Pros*: deploy by pushing on a repository branch (`gh-pages`), provide automatic page generator, support HTTPS (on github.io), supports custom domains (with HTTPS)

## GitLab Pages

[Product page](https://pages.gitlab.io/) / [More info](https://about.gitlab.com/2016/04/07/gitlab-pages-setup/)

* *Free tier*: Completely free for cloud hosted, self hosted version of Gitlab available
* *Pros*: Use any static website generator, connect your custom domain(s) and TLS certificates

## netlify

[Product page](https://www.netlify.com/features) / [Pricing page](https://www.netlify.com/pricing/)

* *Free tier*: Unlimited sites, custom domain and SSL for private projects. Open source projects get [Pro plan for free](https://www.netlify.com/blog/2016/07/28/netlifys-pro-plan-now-free-for-open-source-projects/) (free plan features plus form handling, prerendering, subdomain builds from Git branches, custom TLS certificates, domain aliases)
* *Pros*: offers continuous deployment, custom redirect rules, git repositories integration, webhooks and notifications (for integration with third parties services)


## surge

[Pricing page](http://surge.sh/pricing)

* *Free tier*: unlimited deployments, custom domain and basic SSL
* *Pros*: deploy from CLI, custom 404 pages
* *Limitations*: no custom redirects or http->https redirection in free tier


## Vercel

[Pricing Page](https://vercel.com/pricing)

* *Free tier*: Unlimited websites, HTTPS-enabled custom domains, continuous deployment with git, Analytics for 1 project, [sponsorship](https://vercel.com/support/articles/can-vercel-sponsor-my-open-source-project) for open source projects
* *Pros*: Various starter templates, DNS management, Edge network and first-class support for Next.js
* *Limitations*: Free tier doesn't include commercial usage