# Stack on a budget

This repository offers a collection of services with free tiers for developers on a budget. Because not everyone has 20$ per month to spend on app or database hosting for every single side-project.

Nowadays, a lot of services are offering really good free tier more than enough for testing small apps and even put them in production. They are just waiting to be used by you.

# Table of Contents
<!-- TOC depthFrom:2 -->

- [Static app hosting](#static-app-hosting)
    - [**Firebase hosting**](#firebase-hosting)
    - [**Github Pages**](#github-pages)
- [App hosting](#app-hosting)
    - [**Google App Engine**](#google-app-engine)
    - [**Heroku**](#heroku)
    - [**Hyperdev**](#hyperdev)
    - [**IMB Bluemix**](#imb-bluemix)
    - [**Open Shift**](#open-shift)
    - [**Zeit Now**](#zeit-now)
- [Database hosting](#database-hosting)
    - [**Firebase database**](#firebase-database)
    - [**Google Cloud Datastore**](#google-cloud-datastore)
    - [**Heroku Postgres**](#heroku-postgres)
    - [**Heroku Redis**](#heroku-redis)
    - [**mLab**](#mlab)
    - [**Redis Cloud**](#redis-cloud)
- [Code collaboration tools](#code-collaboration-tools)
    - [**Bitbucket**](#bitbucket)
    - [**GitHub**](#github)
    - [**GitLab**](#gitlab)
- [Continuous integration/delivery](#continuous-integrationdelivery)
    - [**CircleCI**](#circleci)
    - [**Codeship**](#codeship)
    - [**Travis CI (Org)**](#travis-ci-org)
- [User authentication](#user-authentication)
    - [**Auth0**](#auth0)
    - [**Firebase authentication**](#firebase-authentication)
    - [**Ionic Auth**](#ionic-auth)
- [Push notifications](#push-notifications)
    - [**Ionic Push**](#ionic-push)
- [Emailing](#emailing)
    - [**Mailgun**](#mailgun)
- [Mobile analytics](#mobile-analytics)
    - [**Firebase Analytics**](#firebase-analytics)
    - [**Mixpanel**](#mixpanel)
- [Content Delivery Networks](#content-delivery-networks)
    - [**Clouflare**](#clouflare)
- [Misc](#misc)
    - [**Let's encrypt**](#lets-encrypt)

<!-- /TOC -->

## Static app hosting

### **Firebase hosting**

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1Gb storage, 10Gb/month transfer, custom domain and SSL
* *Pros*: includes CDN, auto provisioned SSL, deployment versioning, custom domain, URL rewriting (useful for HTML5 history API), possibility to define headers

### **Github Pages**

[Product page](https://pages.github.com/) / [More info](https://help.github.com/articles/what-is-github-pages/)

* *Free tier*: 1Gb storage, 100Gb bandwidth or 100K requests/month, 10 builds per hour
* *Pros*: deploy by pushing on a repository branch (`gh-pages`), provide automatic page generator, support HTTPS (on github.io), supports custom domains
* *Limitations*: no HTTPS for custom domains

## App hosting

### **Google App Engine**

[Product page](https://cloud.google.com/appengine)

* *Free tier*: 28 instance hours/day, 1Gb outgoing traffic/day, 1Gb incoming traffic/day
* *Pros*: managed, automatic scaling, plays well with other Google Cloud features (load balancing, datastores...), multiple languages supported
* *Limitations*: free tier only applies to standard environment which supports Python, Java, Php and Go. Flexible environment with Node.js and Ruby is not in the free tier.

### **Heroku**

[Pricing page](https://www.heroku.com/pricing)

* *Free tier*: one "dyno" (512Mb memory), custom domains
* *Pros*: supports multiple languages (Node.js, Ruby, Java, PHP, Python, Go, Scala or Clojure)
* *Limitations*: instance will sleep after 30 mins of inactivity

### **Hyperdev**

[About page](https://hyperdev.com/about/)

* *Free tier*: instantly deployed Node.js app with collaboration tool
* *Pros*: based on Node.js, online editor with real time collaboration, live redeploy, great for prototyping and collaboration
* *Limitations*: no custom domain, memory limited to 64Mb

### **IMB Bluemix**

[Pricing page](https://console.ng.bluemix.net/pricing/)

* *Free tier*: 512Mb/month
* *Pros*: can deploy multiple smaller instance for free for a total of 512Mb (4x128Mb, 2x256Mb...), supports multiple languages (Java, JS, Go, Php, Python Ruby), supports containers

### **Open Shift**

[Pricing page](https://www.openshift.com/pricing/index.html)

* *Free tier*: 3 small gears (1 CPU, 512Mb memory and 1Gb storage)
* *Pros*: no time limitation, gears can be used to deploy apps in a lot of languages and/or databases, many deployment templates are provided
* *Limitations*: deployment requires installation of Open Shift app

### **Zeit Now**

[Pricing page](https://zeit.co/now#pricing)

* *Free tier*: 1Gb storage, 1Gb bandwidth/month, 20 deploys/month, free backups
* *Pros*: auto scaling, multi cloud, free backups, served over HTTP/2, use Node.js last version, can also host static websites
* *Limitations*: maximum of 1Mb per file, no custom domain, source code is always public

## Database hosting

### **Firebase database**

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1Gb storage, 10Gb/month transfer, 100 simultaneous connections
* *Pros*: really fast can be used for real time pub/sub, libraries for multiple platforms, designed to be used directly from frontend (with security rules), integrates with Firebase Authentication
* *Limitations*: no backups, limited queries, complicated security rules (read the manual!)

### **Google Cloud Datastore**

[Product page](https://cloud.google.com/datastore/)

* *Free tier*: 1Gb storage/day, 50K reads/day, 20K writes/day, 20K deletes/day
* *Pros*: dashboard, clients available in multiple languages, fully managed (sharding and replication), ACID transactions
* *Limitations*: complex requests needs specific indexes (read the manual)

### **Heroku Postgres**

[Product page](https://www.heroku.com/postgres)

* *Free tier*: 10K rows/month
* *Pros*: dashboard, secured
* *Limitations*: SLA with maximum of 4 hours of downtime/month

### **Heroku Redis**

[Product page](https://www.heroku.com/redis)

* *Free tier*: 25Mb ram, 20 connections
* *Pros*: dashboard, secured, analytics, access via Heroku CLI
* *Limitations*: SLA with maximum of 4 hours of downtime/month

### **mLab**

[Pricing page](https://mlab.com/plans/pricing/)

* *Free tier*: 500Mb storage, daily backup, 
* *Pros*: managed on AWS, Azure or Google Cloud, data browser, monitoring

### **Redis Cloud**

[Pricing page](https://redislabs.com/pricing)

* *Free tier*: 30Mb, 30 connections
* *Pros*: managed, possibility to choose cloud provider (AWS, Azure, GCE, IBM Softlayer) and availability zones

## Code collaboration tools

### **Bitbucket**

[Pricing page](https://bitbucket.org/product/pricing/upcoming?tab=host-in-the-cloud)

* *Free tier*: unlimited public and private repositories for 5 users, 1Gb storage/repository, 1Gb file storage, 50 minutes build time/month
* *Pros*: provide pull requests, issue tracking, code snippets and wiki, has a desktop app

### **GitHub**

[Pricing page](https://github.com/pricing)

* *Free tier*: unlimited public repositories, collaborators and organizations
* *Pros*: provide issue tracking, code snippets (Gist), code reviews, wiki, organizations/team management, 3rd party integration and hooks, has a desktop app
* *Limitations*: no private repository in the free version

### **GitLab**

[Product page](https://about.gitlab.com/gitlab-com/)

* *Free tier*: unlimited public/private projects, unlimited private collaborators, unlimited global storage, 10Gb storage/project
* *Pros*: provide issue tracking, code snippets, wiki and webhooks, can be also self hosted by downloading GitLab Community Edition, provide also free continuous integration services for GitLab.com users

## Continuous integration/delivery

### **CircleCI**

[Pricing page](https://circleci.com/pricing/)

* *Free tier*: unlimited repos and users, 1 concurrent build, 1500 build minutes/month
* *Pros*: supports containers (Docker), integrates with many tools (GitHub, Bitbucket, Code Climate, Slack, Jira, etc)

### **Codeship**

[Pricing page](https://codeship.com/pricing)

* *Free tier*: 5 projects, 1 concurrent build, 1 parallel test pipeline, 100 builds/month
* *Pros*: easy to set up, supports many hosting providers (AWS, Heroku...)
* *Limitations*: no Docker support in free tier

### **Travis CI (Org)**

[Home page](https://travis-ci.org/)

* *Free tier*: unlimited projects and parallel testing for open source projects
* *Pros*: great language and hosting provider support, integrates with many tools (GitHub, Bitbucket, Code Climate, Slack, Jira, etc)
* *Limitations*: free tier is limited to open source projects

## User authentication

### **Auth0**

[Pricing page](https://auth0.com/pricing)

* *Free tier*: unlimited logins for 7000 active users/month, authentication with email/password and up to 2 social providers
* *Pros*: lots of providers, great documentation, support passwordless authentication, UI provided, compatible with iOS Touch ID, offers welcome emails and tasks triggers
* *Limitations*: active users are users who logged in the last 30 days

### **Firebase authentication**

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: always free, unlimited users
* *Pros*: offers multiple login providers for free (anonymous, email, Google, Facebook, Twitter, Github), provide welcome emails triggers, integrates well with Firebase database security rules, libraries for multiple platform
* *Limitations*: no UI provided

### **Ionic Auth**

[Pricing page](http://ionic.io/pricing)

* *Free tier*: always free, unlimited users
* *Pros*: offers multiple login providers (email, custom with in-app browser, Google, Facebook, Twitter, Github, Instagram, LinkedIn), provide forms

## Push notifications

### **Ionic Push**

[Pricing page](http://ionic.io/pricing)

* *Free tier*: 10K notifications/month
* *Pros*: provide dashboard to send push to segments, supports scheduling, designed to be sent from Ionic apps

## Emailing

### **Mailgun**

[Pricing page](http://www.mailgun.com/pricing)

* *Free tier*: 10000 emails/month
* *Pros*: great API, scheduling, SMTP or REST, logs and analytics

## Mobile analytics

### **Firebase Analytics**

[Product page](https://firebase.google.com/docs/analytics/)

* *Free tier*: unlimited reporting of 500 events each with max. 25 attributes
* *Pros*: provide dashboard, demographic segmentation linked to other services (Push notifications), can be exported to BigQuery
* *Limitations*: only available for native Android and iOS (no javascript version)

### **Mixpanel**

[Pricing page](https://mixpanel.com/pricing/)

* *Free tier*: unlimited projects, 20 millions data points/month/project, 1 custom event/project, 60 days data history
* *Pros*: Ideal for mobile applications or "events" oriented websites
* *Limitations*: limited to 3 team members, funnels and segmentation limited to 2 filters

## Content Delivery Networks

### **Clouflare**

[Pricing page](https://www.cloudflare.com/plans/)

* *Free tier*: unlimited websites, free global CDN, free DNS management, shared SSL certificate, 3 page rules/website, basic DDoS protection
* *Pros*: very fast and reliable free CDN, fast DNS propagation, supports CNAME flattening, compatible with HTTP/2, SPDY, WebSockets and IPv6, offers shared SSL (between User and Cloudflare servers), a lot of services are provided (page rules, script injection, image optimization, statistics, etc)

## Misc

### **Let's encrypt**

[Home page](https://letsencrypt.org/)

* *Free tier*: provide SSL certificates for free
* *Pros*: it's free, certificate provisioning can be automated
* *Limitations*: certificates are only valid for 90 days, no wildcard certificates
