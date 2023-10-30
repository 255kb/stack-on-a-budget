# Continuous integration/delivery

<!-- TOC depthFrom:2 -->

- [AppVeyor](#appveyor)
- [Bitbucket Pipelines](#bitbucket-pipelines)
- [Bitrise](#bitrise)
- [CircleCI](#circleci)
- [Codefresh](#codefresh)
- [Codemagic](#codemagic)
- [Codeship](#codeship)
- [Drone](#drone)
- [GitHub Actions](#github-actions)
- [GitLab CI](#gitlab-ci)
- [Semaphore](#semaphore)
- [TeamCity](#teamcity)
- [Travis CI (Org)](#travis-ci-org)
- [Visual Studio Team Services](#visual-studio-team-services)

<!-- /TOC -->

## AppVeyor

[Pricing page](https://www.appveyor.com/pricing/)

* *Free tier*: Unlimited projects for open source, 1 concurrent build
* *Pros*: Build support for .NET, Xamarin, Node.js and Ruby, Integrates with 10 different Git hosting providers including GitHub, GitLab and Bitbucket, Deploys to Azure, Amazon and other hosting providers

## Bitbucket Pipelines
[Product Page](https://bitbucket.org/product/features/pipelines)

* *Free tier*: 50 min / month included
* *Pros*: You can have your runner self-hosted, full integration with Bitbucket
* *Cons*: Only with Bitbucket

## Bitrise

[Pricing page](https://www.bitrise.io/pricing)

* *Free tier*: Run up to 90 builds in parallel, Build time limit of 90 minutes
* *Pros*: Runs are always finished even if you run out of credit in the middle
* *Limitations*: Unused free monthly credit is lost

## CircleCI

[Pricing page](https://circleci.com/pricing/)

* *Free tier*: Unlimited repos and users, 1 concurrent build, 1500 build minutes/month
* *Pros*: Supports Docker containers, Integrates with many tools (GitHub, Bitbucket, Code Climate, Slack, Jira)

## Codefresh

[Pricing page](https://codefresh.io/pricing/)

* *Free tier*: Unlimited repos and 3 users, 1 concurrent build, Unlimited builds
* *Pros*: Native Docker support, Built-in Docker registry, Built-in Helm repository, Distributed Docker cache, Kubernetes/Helm dashboard, Integrated Docker Swarm test environments

## Codemagic

[Pricing page](https://codemagic.io/pricing/)

* *Free tier*: 500 build minutes/month, MacOS standard VM
* *Pros*: Easy to setup Flutter, ReactNative, Cordova, Ionic, and iOS/Android native projects, Publish to App Store and Google Play Store directly

## Codeship

[Pricing page](https://codeship.com/pricing)

* *Free tier*: 5 projects, 1 concurrent build, 1 parallel test pipeline, 100 builds/month
* *Pros*: Easy to set up, Supports many hosting providers (AWS, Heroku)
* *Limitations*: No Docker support in free tier

## Drone

[Product page](https://drone.io)

* *Free tier*: Unlimited public projects, Unlimited builds
* *Pros*: Integrates with many providers and their services (AWS, Heroku, Google AppEngine), Supports GitHub and Bitbucket, Supports Docker, Supports many languages (JavaScript, Python, Go), Supports many environments including Chrome and Firefox for browser testing (Selenium, PhantomJS)
* *Limitations*: Free tier is limited to open source projects

## GitHub Actions

[Product page](https://github.com/features/actions)

* *Free tier*: Unlimited minutes/month for public repositories, 2000 minutes/month for private repositories
* *Pros*: Easy to use
* *Limitations*: Can only be used with GitHub

## GitLab CI

[Product page](https://about.gitlab.com/pricing/)

* *Free tier*: Shared runners (DigitalOcean 4GB instances with CoreOS and Docker) for public/private projects, tests can be run in parallel, 400 compute minutes per month
* *Pros*: Runners can also be installed on premise, fully integrated with GitLab
* *Limitations*: Shared runners builds can be delayed some time

## Semaphore

[Pricing page](https://semaphoreci.com/pricing)

* *Free tier*: Free for open source projects or 100 private builds/month
* *Pros*: Supports many languages (JavaScript, Python, PHP, Go, Java), Supports many databases (PostgreSQL, MySQL, MongoDB), Supports Docker, Integrates with GitHub and Bitbucket, Automatic configuration, Integrates with communication tools (Slack, Basecamp), Implements custom workflow through API, Deploys to many hosting providers (AWS S3, AWS Lambda, AWS Elastic Beanstalk, Cloud 66, Heroku, FTP)

## TeamCity

[Product page](https://www.jetbrains.com/teamcity/)

* *Free tier*: 20 builds configurations, 3 build agents
* *Pros*: Integrates with many cloud providers (AWS, Microsoft Azure and VMware vSphere), Supports GitHub and Bitbucket, Supports Docker

## Travis CI (Org)

[Product page](https://travis-ci.org/)

* *Free tier*: Unlimited projects and parallel testing for open source projects
* *Pros*: Supports many languages, Supports many hosting providers, Integrates with many tools (GitHub, Bitbucket, Code Climate, Slack, Jira)
* *Limitations*: Free tier is limited to open source projects

## Visual Studio Team Services

[Pricing Page](https://www.visualstudio.com/team-services/pricing/)

* *Free tier*: Unlimited projects, 4 hosted build hours/month, Unlimited build hours for a single instance of the [self-hosted build agent](https://github.com/Microsoft/vsts-agent)
* *Pros*: Provides Windows and Linux (preview) hosted build machines, Integrates with many tools/platforms (.NET, Node.js, iOS, Docker) and services (Azure, Google Play) via an [ecosystem](https://marketplace.visualstudio.com/vsts) of free extensions
* *Limitations*: Can only run a single build or release concurrently, with a maximum duration of 30 minutes/run
