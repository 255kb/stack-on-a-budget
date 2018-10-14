# App hosting

<!-- TOC depthFrom:2 -->

- [AppHarbor](#appharbor)
- [AWS EC2](#aws-ec2)
- [Azure App Service](#azure-app-service)
- [GearHost](#gearhost)
- [Glitch](#glitch)
- [Google App Engine](#google-app-engine)
- [Google Compute Engine](#google-compute-engine)
- [Heroku](#heroku)
- [IBM Bluemix](#ibm-bluemix)
- [OpenShift](#openshift)
- [Zeit Now](#zeit-now)

<!-- /TOC -->

## AppHarbor

[Pricing page](https://appharbor.com/pricing)

* *Free tier*: 1 worker unit
* *Pros*: auto scaling, deploy with git, one of few PaaS for .NET apps
* *Limitations*: no custom domain

## AWS EC2

[Product page](https://aws.amazon.com/free/)

* *Free tier*: 750 hours/month of t2.micro instances
* *Limitations*: expires 12 months after sign-up

## Azure App Service

[Pricing page](https://azure.microsoft.com/en-us/pricing/details/app-service/)

* *Free tier*: 10 applications, 1 shared core, 1GB RAM and 1GB storage per application
* *Pros*: supports .NET, easy publishing directly from Git/GitHub/Bitbucket
* *Limitations*: cumulative limit for CPU (60 minutes allowed every 24 hours), no SLA, no custom domain, no SSL

## GearHost

[Pricing page](https://www.gearhost.com/pricing)

* *Free tier*: 1 shared node and 1 worker at max, 100MB storage, 1GB bandwidth/month, custom domains
* *Pros*: supports .NET (4.6), PHP (5.3-5.5) and Node.js apps, MSSQL and MySQL databases, easy publishing over FTP, WebDeploy or directly from Git/GitHub/Bitbucket
* *Limitation*: cumulative limits for CPU (60 minutes allowed every 24 hours) and RAM (256 MB allocated every hour), 1 GB bandwidth allowd every 24 hours, [250 concurrent connections](https://www.gearhost.com/documentation/difference-free-standard-reserved-plans), no SSL support, only 32bits processes
* *Exceeding the free tier*: whenever the CPU usage, RAM usage or consumed bandwidth reaches the limit within its timefame, the application goes offline until the counter resets

## Glitch

[About page](https://glitch.com/about/)

* *Free tier*: instantly deployed Node.js app with collaboration tool
* *Pros*: based on Node.js, online editor with real time collaboration, live redeploy, great for prototyping and collaboration
* *Limitations*: no custom domain, memory limited to 64MB

## Google App Engine

Platform for building scalable web applications and mobile backends

[Product page](https://cloud.google.com/appengine)

* *Free tier*: 28 instance hours/day, 1GB outgoing traffic/day, 1GB incoming traffic/day, 5GB Cloud storage, Shared memcache, 1000 search operations per day, 10 MB search indexing, 100 emails per day
* *Pros*: managed, automatic scaling, plays well with other Google Cloud features (load balancing, datastores...), multiple languages supported
* *Limitations*: free tier only applies to standard environment which supports Python, Java, PHP and Go. Flexible environment with Node.js and Ruby is not in the free tier.

## Google Compute Engine

Scalable, high-performance virtual machines

[Product page](https://cloud.google.com/compute/)

* *Free tier*: 1 f1-micro instance per month (US regions only), 30 GB-months HDD, 5 GB-months snapshot, 1 GB network egress from North America to all region destinations per month (excluding China and Australia)
* *Pros*: plays well with other Google Cloud features (load balancing, datastores...)
* *Limitations*: for now limited to US region only

## Heroku

[Pricing page](https://www.heroku.com/pricing)

* *Free tier*: one "dyno" (512MB memory), custom domains
* *Pros*: supports multiple languages (Node.js, Ruby, Java, PHP, Python, Go, Scala or Clojure)
* *Limitations*: instance will sleep after 30 mins of inactivity

## IBM Bluemix

[Pricing page](https://console.ng.bluemix.net/pricing/)

* *Free tier*: 512MB/month
* *Pros*: can deploy multiple smaller instance for free for a total of 512MB (4x128MB, 2x256MB...), supports multiple languages (Java, JS, Go, PHP, Python Ruby), supports containers

## OpenShift

[Pricing page](https://www.openshift.com/pricing/index.html)

* *OpenShift is launching a new v3 with 30 days limited developer preview. Sign up are closed since August 1st 2016 for the previous version with 3 free small gears. It is not clear yet if the v3 will come with a free tier or not. Information below are related to the v2.*
* *Free tier*: 3 small gears (1 CPU, 512MB memory and 1GB storage)
* *Pros*: no time limitation, gears can be used to deploy apps in a lot of languages and/or databases, many deployment templates are provided
* *Limitations*: deployment requires installation of OpenShift app, 'idle' apps take longer to load (>30s)

## Zeit Now

[Pricing page](https://zeit.co/now#pricing)

* *Free tier*: 1GB storage, 1GB bandwidth/month, 100MB logs/month, unlimited deploys/month, 3 concurrent instances
* *Pros*: multi cloud, served over HTTP/2, use Node.js last version, can also host static websites
* *Limitations*: maximum of 5MB per file, no custom domain, source code is always public
