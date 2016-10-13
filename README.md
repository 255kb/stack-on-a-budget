# Stack on a budget

This repository offers a collection of services with free tiers for developers on a budget. Because not everyone has 20$ per month to spend on apps or database hosting for every single side-project.

Nowadays, a lot of services are offering really good free tier more than enough for testing and small apps in production. They are just waiting to be used by you.

# Table of Contents
<!-- TOC depthFrom:2 -->

- [Static app hosting](#static-app-hosting)
    - [**Firebase hosting**](#firebase-hosting)
- [App hosting](#app-hosting)
    - [**Zeit Now**](#zeit-now)
    - [**Hyperdev**](#hyperdev)
- [Database hosting](#database-hosting)
    - [**Firebase database**](#firebase-database)
- [Code versioning](#code-versioning)
- [Collaboration tools](#collaboration-tools)
- [Continuous integration](#continuous-integration)
- [APIs](#apis)
- [User authentication](#user-authentication)
    - [**Auth0**](#auth0)
    - [**Firebase authentication**](#firebase-authentication)
- [Push notifications](#push-notifications)
- [Emailing](#emailing)
- [Analytics](#analytics)
- [Misc](#misc)

<!-- /TOC -->

## Static app hosting

### **Firebase hosting**

[Pricing page](https://firebase.google.com/pricing/)

*Free tier*: 1Gb storage, 10Gb/month transfer, custom domain and SSL

*Pros*: includes CDN, auto provisioned SSL, deployment versioning, custom domain, URL rewriting (useful for HTML5 history API), possibility to define headers

## App hosting

### **Zeit Now**

[Pricing page](https://zeit.co/now#pricing)

*Free tier*: 1Gb storage, 1Gb bandwidth/month, 20 deploys/month, free backups

*Pros*: auto scaling, multi cloud, free backups, served over HTTP/2, use NodeJS last version, can also host static websites

*Limitations*: maximum of 1Mb per file, no custom domain, source code is always public


### **Hyperdev**

[About page](https://hyperdev.com/about/)

*Free tier*: instantly deployed NodeJS app with collaboration tool

*Pros*: based on NodeJS, online editor with real time collaboration, live redeploy, great for prototyping and collaboration

*Limitations*: no custom domain, memory limited to 64Mb

## Database hosting

### **Firebase database**

[Pricing page](https://firebase.google.com/pricing/)

*Free tier*: 1Gb storage, 10Gb/month transfer, 100 simultaneous connections

*Pros*: really fast can be used for real time pub/sub, libraries for multiple platforms, designed to be used directly from frontend (with security rules), integrates with Firebase Authentication

*Limitations*: no backups, limited queries, complicated security rules (read the manual!)

## Code versioning
## Collaboration tools
## Continuous integration
## APIs
## User authentication

### **Auth0**

[Pricing page](https://auth0.com/pricing)

*Free tier*: unlimitedlogins for 7000 active users/month, authentication with email/password and up to 2 social providers

*Pros*: lots of providers, great documentation, support passwordless authentication, UI provided, compatible with iOS Touch ID, offers welcome emails and tasks triggers

*Limitations*: active users are users who logged in the last 30 days

### **Firebase authentication**

[Pricing page](https://firebase.google.com/pricing/)

*Free tier*: always free, unlimited users

*Pros*: offers multiple login providers for free (anonymous, email, Google, Facebook, Twitter, Github), provide welcome emails triggers, integrates well with Firebase database security rules, libraries for multiple platform

*Limitations*: no UI provided

## Push notifications
## Emailing
## Analytics
## Misc
