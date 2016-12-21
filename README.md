# Stack on a budget

This repository offers a collection of services with great free tiers for developers on a budget. Because not everyone has 20$ per month to spend on app or database hosting for every single side-project.

Nowadays, a lot of services are offering really good free tier more than enough for testing small apps and even put them in production. They are just waiting to be used by you.

The goal is to have enough details about each free tier so a developer can choose whether or not the service suits her needs just by reading the description.

# Contribution

Feel free to contribute to existing services or add new ones. Please follow the guidelines when submitting, you can find them in [CONTRIBUTING.md](CONTRIBUTING.md), and especially the rules about how to select a service and describe it (free tier, limitations...).

# Table of Contents
<!-- TOC depthFrom:2 -->

- [Static app hosting](#static-app-hosting)
    - [**Firebase hosting**](#firebase-hosting)
    - [**Github Pages**](#github-pages)
    - [**GitLab Pages**](#gitlab-pages)
    - [**netlify**](#netlify)
    - [**surge**](#surge)
- [App hosting](#app-hosting)
    - [**AWS EC2**](#aws-ec2)
    - [**Google App Engine**](#google-app-engine)
    - [**Heroku**](#heroku)
    - [**Gomix**](#gomix)
    - [**IBM Bluemix**](#ibm-bluemix)
    - [**OpenShift**](#openshift)
    - [**Zeit Now**](#zeit-now)
- [Database hosting](#database-hosting)
    - [**Firebase database**](#firebase-database)
    - [**GearHost Database**](#gearhost-database)
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
    - [**AppVeyor**](#appveyor)
    - [**CircleCI**](#circleci)
    - [**Codeship**](#codeship)
    - [**TeamCity**](#teamcity)
    - [**Travis CI (Org)**](#travis-ci-org)
- [User authentication](#user-authentication)
    - [**Auth0**](#auth0)
    - [**Firebase authentication**](#firebase-authentication)
    - [**Ionic Auth**](#ionic-auth)
    - [**Stormpath**](#stormpath)
- [Push notifications](#push-notifications)
    - [**Batch**](#batch)
    - [**Firebase Push**](#firebase-push)
    - [**Ionic Push**](#ionic-push)
    - [**onesignal**](#onesignal)
- [Emailing](#emailing)
    - [**Mailgun**](#mailgun)
- [Mobile analytics](#mobile-analytics)
    - [**Amazon Mobile Analytics**](#amazon-mobile-analytics)
    - [**Countly Analytics**](#countly-analytics)
    - [**Firebase Analytics**](#firebase-analytics)
    - [**Mixpanel**](#mixpanel)
- [Content Delivery Networks](#content-delivery-networks)
    - [**Cloudflare**](#cloudflare)
- [App Testing](#app-testing)
    - [**Sauce Labs**](#sauce-labs)
- [Realtime Infrastructure](#realtime-infrastructure)
    - [**Pusher**](#pusher)
- [Misc](#misc)
    - [**Cloudinary**](#cloudinary)
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

### **GitLab Pages**

[Product page](https://pages.gitlab.io/) / [More info](https://about.gitlab.com/2016/04/07/gitlab-pages-setup/)

* *Free tier*: Completely free for cloud hosted, self hosted version of Gitlab available
* *Pros*: Use any static website generator, Connect your custom domain(s) and TLS certificates, Shared / Self-hosted CI runners
* *Limitations*: Shared CI can be delayed some time

### **netlify**

[Pricing page](https://www.netlify.com/pricing/)

* *Free tier*: Unlimited sites, custom domain and SSL
* *Pros*: offers continuous deployment, custom redirect rules, git repositories integration, webhooks and notifications (for integration with third parties services)

### **surge**

[Pricing page](http://surge.sh/pricing)

* *Free tier*: unlimited deployments, custom domain and basic SSL
* *Pros*: deploy from CLI, custom 404 pages
* *Limitations*: no custom redirects or http->https redirection in free tier

## App hosting

### **AWS EC2**

[Product page](https://aws.amazon.com/free/)

* *Free tier*: 750 hours/month of t2.micro instances
* *Limitations*: expires 12 months after sign-up

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

### **Gomix**

[About page](https://gomix.com/about/)

* *Free tier*: instantly deployed Node.js app with collaboration tool
* *Pros*: based on Node.js, online editor with real time collaboration, live redeploy, great for prototyping and collaboration
* *Limitations*: no custom domain, memory limited to 64Mb

### **IBM Bluemix**

[Pricing page](https://console.ng.bluemix.net/pricing/)

* *Free tier*: 512Mb/month
* *Pros*: can deploy multiple smaller instance for free for a total of 512Mb (4x128Mb, 2x256Mb...), supports multiple languages (Java, JS, Go, Php, Python Ruby), supports containers

### **OpenShift**

[Pricing page](https://www.openshift.com/pricing/index.html)

* *Free tier*: 3 small gears (1 CPU, 512Mb memory and 1Gb storage)
* *Pros*: no time limitation, gears can be used to deploy apps in a lot of languages and/or databases, many deployment templates are provided
* *Limitations*: deployment requires installation of OpenShift app, 'idle' apps take longer to load (>30s)

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

### **GearHost Database**

[Pricing page](https://www.gearhost.com/pricing)

* *Free tier*: 5MB MySQL database or 10MB MS SQL database
* *Pros*: Recent versions (MySQL 5.6, MS SQL Server 2014)
* *Limitations*: simultaneous connections seems to be limited (according to [this page](http://talk.gearhost.com/t/restrictions-or-limitations-of-the-free-account/105), approx. 15)

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

### **AppVeyor**

[Pricing page](https://www.appveyor.com/pricing/)

* *Free tier*: unlimited projects for open source, 1 concurrent build
* *Pros*: build support for .NET, Xamarin, Node.js and Ruby, integrates with 10 different code hosting providers (GitHub, BitBucket, GitLab...), deploys to Azure, Amazon and other hosting providers

### **CircleCI**

[Pricing page](https://circleci.com/pricing/)

* *Free tier*: unlimited repos and users, 1 concurrent build, 1500 build minutes/month
* *Pros*: supports containers (Docker), integrates with many tools (GitHub, Bitbucket, Code Climate, Slack, Jira, etc)

### **Codeship**

[Pricing page](https://codeship.com/pricing)

* *Free tier*: 5 projects, 1 concurrent build, 1 parallel test pipeline, 100 builds/month
* *Pros*: easy to set up, supports many hosting providers (AWS, Heroku...)
* *Limitations*: no Docker support in free tier

### **TeamCity**

[Home page](https://www.jetbrains.com/teamcity/)

* *Free tier*: 20 builds configurations, 3 build agents, access to all features
* *Pros*: Integrates with cloud providers (AWS, Microsoft Azure and VMware vSphere) and VCS providers (GitHub, Bitbucket), supports Docker

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

### **Stormpath**

[Pricing Page](https://stormpath.com/pricing)

- *Free tier:* unlimited users, 10k API calls/mo
- *Pros:* complete user authentication, authorization and management through their API, client libraries for multiple languages

## Push notifications

### **Batch**

[Pricing page](https://batch.com/pricing)

* *Free tier*: unlimited notifications, up to 100,000 monthly active users
* *Pros*: supports iOS, Android, Cordova, Phonegap, Ionic, Adobe AIR, Unity mobile applications, basic users segmentation (country/language targeting), message scheduling, transactional API
* *Limitations*: no advanced user segmentation, campaigns API, data push and A/B testing on free tier

### **Firebase Push**

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: unlimited notifications
* *Pros*: supports Android and iOS native applications, users segmentation, message scheduling, integrates with Firebase analytics
* *Limitations*: no javascript library

### **Ionic Push**

[Pricing page](http://ionic.io/pricing)

* *Free tier*: 10K notifications/month
* *Pros*: provide dashboard to send push to segments, supports scheduling, designed to be sent from Ionic apps

### **onesignal**

[Pricing page](https://onesignal.com/#pricing)

* *Free tier*: unlimited devices, unlimited notifications
* *Pros*: support iOS, Android, web push, Windows Phone, Amazon Fire, Chrome extensions and native support for every development environment, localization, unlimited segments, delivery scheduling, realtime analytics, delivery automation, full API, A/B testing, import & export your data

## Emailing

### **Mailgun**

[Pricing page](http://www.mailgun.com/pricing)

* *Free tier*: 10000 emails/month
* *Pros*: great API, scheduling, SMTP or REST, logs and analytics

## Mobile analytics

### **Amazon Mobile Analytics**

[Pricing page](https://aws.amazon.com/mobileanalytics/pricing/)

* *Free tier*: 100 millions basic sessions and custom events per month
* *Pros*: provide dashboard with various metrics (sessions, active users, revenues per user, retention, etc), data can be exported in CSV format, events can be sent through SDKs or REST API, provide iOS, Android and javascript SDKs, events are send in batch and cached until the device is online
* *Limitations*: export to S3 or RedShift is subject to these services respective pricings

### **Countly Analytics**

[Product page](https://count.ly/product) 

* *Free tier*: Countly Community Edition (for mobile, web and desktop analytics) is free to download and use.
* *Pros*: Client and server side application are open source (AGPLv3). Installable on-premises, based on MongoDB and Nodejs. Data can be exported in CSV, XLS format or can be read through API. More than 10 SDKs including Android, iOS, Windows Phone, MacOS and Windows. Plugin based infrastructure. Countly Community Edition also includes crash reporting and push notifications.
* *Limitations*: Community Edition has less number of features than Countly Enterprise Edition (e.g Drill, User Profiles, etc).

### **Firebase Analytics**

[Product page](https://firebase.google.com/docs/analytics/)

* *Free tier*: unlimited reporting of 500 events each with max. 25 attributes
* *Pros*: provide dashboard with various metrics (sessions, active users, revenues per user, retention, etc), demographic segmentation linked to other services (Push notifications), can be exported to BigQuery
* *Limitations*: only available for native Android and iOS (no javascript version)

### **Mixpanel**

[Pricing page](https://mixpanel.com/pricing/)

* *Free tier*: unlimited projects, 20 millions data points/month/project, 1 custom event/project, 60 days data history
* *Pros*: Ideal for mobile applications or "events" oriented websites
* *Limitations*: limited to 3 team members, funnels and segmentation limited to 2 filters

### **Flurry Analytics**

[Product page](https://developer.yahoo.com/analytics)

* *Free tier*: Flurry analytics is free at any scale
* *Pros*: Extensive functionality and features including usage metrics, retention, real-time data, revenue metrics, crash reporting, custom user interaction and more.  Flurry features an instant analysis tool (Flurry Explorer) that eliminates need for code and SQL for detailed look into user segmentation, interaction, funnels and retention. 
* *Limitations*: only available for native Android and iOS (no javascript version)

## Content Delivery Networks

### **Cloudflare**

[Pricing page](https://www.cloudflare.com/plans/)

* *Free tier*: unlimited websites, free global CDN, free DNS management, shared SSL certificate, 3 page rules/website, basic DDoS protection
* *Pros*: very fast and reliable free CDN, fast DNS propagation, supports CNAME flattening, compatible with HTTP/2, SPDY, WebSockets and IPv6, offers shared SSL (between User and Cloudflare servers), a lot of services are provided (page rules, script injection, image optimization, statistics, etc)

## App Testing

### **Sauce Labs**

[Pricing page](https://saucelabs.com/beta/signup/OSS/None)

* *Free tier*: free for open source, unlimited automated testing, unlimited manual testing, 5 concurrent VMs, 2 subaccounts
* *Pros*: web tests on hundreds of platform/OS/browser combinations, integrates well with test runners like Karma and Selenium

## Realtime Infrastructure

### **Pusher**

[Pricing page](https://pusher.com/pricing)

* *Free tier*: Unlimited channels, 100 max connections, 200,000 messages a day, support
* *Pros*: Send messages from your server and subscribe to them in real-time from any client (Android, iOS, JavaScript, etc.) at massive scale (Pub/Sub). Great documentation, intuitive client libraries, and a powerful dashboard for testing, debugging, and analytics. Libraries available for various languages.


## Misc

### **Cloudinary**

[Pricing page](http://cloudinary.com/pricing)

* *Free tier*: 75000 total images or videos and 7500 monthly transformations, 2Gb storage, 5Gb bandwidth/month
* *Pros*: free tiers includes images and videos manipulations (resizing, effects, overlays, optimization), backup and revisions, supports PDF, sprites, animated GIFs, etc. Provide SDK in multiplae languages
* *Limitations*: free tier does not offer custom domain

### **Let's encrypt**

[Home page](https://letsencrypt.org/)

* *Free tier*: provide SSL certificates for free
* *Pros*: free?
* *Limitations*: certificates are valid for 90 days so automation is strongly recommended, no wildcard certificates
