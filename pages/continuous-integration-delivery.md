# Continuous integration/delivery

<!-- TOC depthFrom:2 -->

- [AppVeyor](#appveyor)
- [Bitrise](#bitrise)
- [CircleCI](#circleci)
- [Codefresh](#codefresh)
- [Codemagic](#codemagic)
- [Codeship](#codeship)
- [ContinuousPHP](#continuousphp)
- [Drone](#drone)
- [GitLab CI](#gitlab-ci)
- [Semaphore](#semaphore)
- [Shippable](#shippable)
- [TeamCity](#teamcity)
- [Travis CI (Org)](#travis-ci-org)
- [Visual Studio Team Services](#visual-studio-team-services)

<!-- /TOC -->

## AppVeyor

[Pricing page](https://www.appveyor.com/pricing/)

* *Free tier*: unlimited projects for open source, 1 concurrent build
* *Pros*: build support for .NET, Xamarin, Node.js and Ruby, integrates with 10 different code hosting providers (GitHub, Bitbucket, GitLab...), deploys to Azure, Amazon and other hosting providers

## Bitrise

[Pricing page](https://www.bitrise.io/pricing)

* *Free tier*: On a credit-based plan, you can run up to 90 builds in parallel, with a build time limit of 90 minutes, until you use up your free credit bundle.
* *Pros*: runs are always finished even if you run out of credit in the middle.
* *Limitations*: unused free monthly credit is lost

## CircleCI

[Pricing page](https://circleci.com/pricing/)

* *Free tier*: unlimited repos and users, 1 concurrent build, 1,500 build minutes/month
* *Pros*: supports containers (Docker), integrates with many tools (GitHub, Bitbucket, Code Climate, Slack, Jira, etc)

## Codefresh

[Pricing page](https://codefresh.io/pricing/)

* *Free tier*: unlimited repos and 3 users, 1 concurrent build. Unlimited builds per month.
* *Pros*: Native Docker support, built-in Docker registry, built-in Helm repository. Distributed Docker cache. Kubernetes/Helm dashboard, integrated Docker swarm test environments

## Codemagic

[Pricing page](https://codemagic.io/pricing/)

* *Free tier*: 500 build minutes every month. macOS standard VM.
* *Pros*: easy to setup Flutter, ReactNative, Cordova, Ionic, and iOS/Android native projects. Publish to App Store and Google Play directly.

## Codeship

[Pricing page](https://codeship.com/pricing)

* *Free tier*: 5 projects, 1 concurrent build, 1 parallel test pipeline, 100 builds/month
* *Pros*: easy to set up, supports many hosting providers (AWS, Heroku...)
* *Limitations*: no Docker support in free tier

## ContinuousPHP

[Pricing page](https://continuousphp.com/plans)

* *Free tier*: unlimited projects for open source projects
* *Pros*: supports many hosting providers (AWS, Zend Server...) and several Git Repository Hosting Services (GitHub, Bitbucket, GitLab)
* *Limitations*: dedicated to PHP

## Drone

[Home page](https://drone.io)
* *Free tier*: unlimited public projects and unlimited builds
* *Pros*: Integrates with multiple providers and their services (AWS, Heroku, Google AppEngine, etc.), supports VCS (GitHub, Bitbucket), uses Docker, supports multiple languages (Go, Python, JavaScript...) and environments including Chrome and Firefox for browser testing (Selenium, PhantomJS...)
* *Limitations*: free tier is limited to open source projects

## GitLab CI

[Product page](https://about.gitlab.com/gitlab-ci/) / [Shared runners details](https://about.gitlab.com/gitlab-com/settings/#shared-runners)

* *Free tier*: shared runners (Digital Ocean 4GB instances with CoreOS and Docker) for public/private projects, tests can be run in parallel
* *Pros*: runners can also be installed on premise, fully integrated with GitLab
* *Limitations*: Shared runners builds can be delayed some time

## Semaphore

[Pricing page](https://semaphoreci.com/pricing)

* *Free tier*: free for open source projects or 100 private builds per month
* *Pros*: supports various languages (JavaScript, Go, Java, PHP, Python...), databases (MongoDB, PostgreSQL, MySQL...) and Docker, integrates seamlessly with GitHub and Bitbucket, automatic configurations for a wide range of projects, integrates with communication tools (Campfire, Slack...), implements custom workflow through API, deploys to many hosting providers (AWS S3, Lambda and Elastic Beanstalk, Cloud 66, Heroku, FTP)

## Shippable

[Home page](https://app.shippable.com/)

* *Free tier*: unlimited projects from either public or private repos, unlimited builds for open source repositories, 150 builds/month for private repositories, one concurrent job
* *Pros*: integrates with GitHub or Bitbucket, uses Docker buildpacks, custom images, YAML file config, build badges, integrates with a lot of services, including various AWS services, Slack, GitLab, IRC, Jenkins and JFrog Artifactory

## TeamCity

[Home page](https://www.jetbrains.com/teamcity/)

* *Free tier*: 20 builds configurations, 3 build agents, access to all features
* *Pros*: Integrates with cloud providers (AWS, Microsoft Azure and VMware vSphere) and VCS providers (GitHub, Bitbucket), supports Docker

## Travis CI (Org)

[Home page](https://travis-ci.org/)

* *Free tier*: unlimited projects and parallel testing for open source projects
* *Pros*: great language and hosting provider support, integrates with many tools (GitHub, Bitbucket, Code Climate, Slack, Jira, etc)
* *Limitations*: free tier is limited to open source projects

## Visual Studio Team Services

[Pricing Page](https://www.visualstudio.com/team-services/pricing/)

* *Free tier*: Unlimited projects, with 4 hosted build hours/month, and unlimited build hours for a single instance of the [self-hosted build agent](https://github.com/Microsoft/vsts-agent)
* *Pros*: Provides Windows and Linux (preview) hosted build machines, and integrates with many tools/platforms (e.g. .NET, Node.js, iOS, Docker) and services (e.g. Azure, Google Play) via an [ecosystem](https://marketplace.visualstudio.com/vsts) of free extensions
* *Limitations*: Can only run a single build or release concurrently, with a maximum duration of 30 minutes per run
