# Stack on a budget

This repository offers a collection of services with free tiers for developers on a budget. Because not everyone has 20$ per month to spend on apps or database hosting for every single side-project.

Nowadays, a lot of services are offering really good free tier more than enough for testing and small apps in production. They are just waiting to be used by you.

# Table of Contents
<!-- TOC depthFrom:2 -->

- [Static app hosting](#static-app-hosting)
    - [**Firebase hosting**](#firebase-hosting)
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
    - [**Redis Cloud**](#redis-cloud)
- [Code versioning](#code-versioning)
- [Collaboration tools](#collaboration-tools)
- [Continuous integration/delivery](#continuous-integrationdelivery)
    - [**Codeship**](#codeship)
- [APIs](#apis)
- [User authentication](#user-authentication)
    - [**Auth0**](#auth0)
    - [**Firebase authentication**](#firebase-authentication)
- [Push notifications](#push-notifications)
- [Emailing](#emailing)
    - [**Mailgun**](#mailgun)
- [Analytics](#analytics)
- [Misc](#misc)
    - [**Let's encrypt**](#lets-encrypt)

<!-- /TOC -->

## Static app hosting

### **Firebase hosting**

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1Gb storage, 10Gb/month transfer, custom domain and SSL
* *Pros*: includes CDN, auto provisioned SSL, deployment versioning, custom domain, URL rewriting (useful for HTML5 history API), possibility to define headers

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

### **Redis Cloud**

[Pricing page](https://redislabs.com/pricing)

* *Free tier*: 30Mb, 30 connections
* *Pros*: managed, possibility to choose cloud provider (AWS, Azure, GCE, IBM Softlayer) and availability zones

## Code versioning
## Collaboration tools
## Continuous integration/delivery

### **Codeship**

[Pricing page](https://codeship.com/pricing)

* *Free tier*: 5 projects, 1 concurrent build, 1 parallel test pipeline, 100 builds/month
* *Pros*: easy to set up, supports many hosting providers (AWS, Heroku...)
* *Limitations*: no Docker support in free tier

## APIs
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

## Push notifications
## Emailing

### **Mailgun**

[Pricing page](http://www.mailgun.com/pricing)

* *Free tier*: 10000 emails/month
* *Pros*: great API, scheduling, SMTP or REST, logs and analytics

## Analytics
## Misc

### **Let's encrypt**

[Home page](https://letsencrypt.org/)

* *Free tier*: provide SSL certificates for free
* *Pros*: it's free, certificate provisioning can be automated
* *Limitations*: certificates are only valid for 90 days, no wildcard certificates
