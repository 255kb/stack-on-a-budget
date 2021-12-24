# App hosting

<!-- TOC depthFrom:2 -->

- [App hosting](#app-hosting)
  - [AWS EC2](#aws-ec2)
  - [Azure App Service](#azure-app-service)
  - [Google App Engine](#google-app-engine)
  - [Google Compute Engine](#google-compute-engine)
  - [Oracle](#oracle)
  - [IBM Cloud](#ibm-cloud)
  - [OpenShift](#openshift)
  - [Heroku](#heroku)
  - [Koyeb](#koyeb)
  - [Railway](#railway)
  - [Vercel](#vercel)
  - [Netlify](#netlify)
  - [Glitch](#glitch)
  - [AppHarbor](#appharbor)
  - [GearHost](#gearhost)
  - [OpeNode](#openode)

<!-- /TOC -->

## AWS EC2

[Product page](https://aws.amazon.com/free/)

* *Free tier*: 750 hours/month of t2.micro instances
* *Limitations*: Expires 12 months after sign-up

## Azure App Service

[Pricing page](https://azure.microsoft.com/en-us/pricing/details/app-service/)

* *Free tier*: 10 applications, 1 shared core, 1GB RAM and 1GB storage per application
* *Pros*: Supports .NET, easy publishing directly from Git/GitHub/Bitbucket
* *Limitations*: Cumulative limit for CPU (60 minutes allowed every 24 hours), No uptime SLA, No custom domain, No SSL

## Google App Engine

[Product page](https://cloud.google.com/appengine)

* *Free tier*: 28 instance hours/day, 1GB outbound bandwidth/day, 1GB inbound bandwidth/day, 5GB Cloud storage, Shared memcache, 1000 search operations per day, 10MB search indexing, 100 emails per day
* *Pros*: Managed, Autoscaling, Works well with other Google Cloud features (load balancing, datastores, etc.), Multiple languages supported
* *Limitations*: Free tier only applies to a standard environment which supports Python, Java, PHP and Go

## Google Compute Engine

[Product page](https://cloud.google.com/compute/)

* *Free tier*: 1 f1-micro instance per month (US regions only), 30GB-months HDD, 5GB-months snapshot, 1GB network egress from North America to all region destinations per month (excluding China and Australia)
* *Pros*: Works well with other Google Cloud features (load balancing, datastores, etc.)
* *Limitations*: Limited to US region only for now

## Oracle

[Pricing page](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier.htm)

* *Free tier*: 2 Compute(AMD) Micro instances (1/8th OCPU, 1GB memory each), Ampere A1 Compute(Arm) instances (4 OCPUs and 24GB of memory that you can allocate flexibly), 20TB outbound bandwidth (unlimited inbound) [Read more](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm)
* *Pros*: Free forever virtual machines
* *Limitations*: OS selection restricted to Oracle Enterprise Linux, CentOS and Ubuntu

## IBM Cloud

[Pricing page](https://cloud.ibm.com/pricing/)

* *Free tier*: 512MB/month
* *Pros*: Can deploy multiple smaller instance for free for a total of 512MB (4x128MB, 2x256MB...), Supports multiple languages (Java, JS, Go, PHP, Python Ruby), Supports containers

## OpenShift

[Pricing page](https://www.openshift.com/pricing/index.html)

* *Free tier*: 1 project, 2GB memory, 2GB storage, no custom domain
* *Pros*: Gears can be used to deploy apps in a lot of languages and/or databases, Many deployment templates are provided
* *Limitations*: Deployment requires installation of OpenShift app, Idle apps take longer to load (>30s)

## Heroku

[Pricing page](https://www.heroku.com/pricing)

* *Free tier*: One dyno (512MB memory), Custom domains
* *Pros*: Supports multiple languages (Node.js, Ruby, Java, PHP, Python, Go, Scala or Clojure)
* *Limitations*: Instance will sleep after 30 mins of inactivity

## Koyeb

[Pricing page](https://www.koyeb.com/pricing)

* *Free tier*: 2 nano services, 1vCPU per service, 256MB of RAM per service, 2.5GB SSD per service, 100GB outbound bandwidth (unlimited inbound)
* *Pros*:  Native autoscaling, Intuitive web interface and CLI, Deploy with Git, Edge CDN, Cron background tasks, Good observability, Supports containers
* *Limitations*: No uptime SLA on free tier

## Fly

[Pricing page](https://fly.io/docs/about/pricing/)

* *Free tier*: 2340 shared CPU hours per month, 160GB outbound bandwidth per month (unlimited inbound), Unlimited IPv6 and 1 IPv4 Anycast IPs per active app, 10 active certificates per app
* *Limitations*: No uptime SLA, No web app (access through CLI only)

## Railway

[Pricing page](https://railway.app/pricing)

* *Free tier*: 1GB memory per container, Shared CPU, 1GB disk usage (10GB hard limit), 100GB outbound bandwidth (unlimited inbound). [Read more](https://railway.app/legal/fair-use)
* *Pros*: You can have your app and database on the same platform and run both of them for free, [see](database-hosting.md#railway) for database hosting
* *Limitations*: Only 99% uptime SLA, 3 projects, 2 plugins per project, 2 environments per project, 3 live deploys per environment

## Vercel

[Pricing page](https://vercel.com/pricing)

* *Free tier*: 100GB bandwidth per month, 100GB-Hours serverless function execution, 1000 image optimizations, Unlimited serverless function invocations, 100000 edge function invocations, 6000 build minutes/month, 1 concurrent build, 50 domains per project, 3 projects per git repository, 100 deployments per day, 12 serverless functions written in Node.js, Go, Python and Ruby
* *Pros*:  Deploy with git, Edge CDN, Preview deployments, Next.js API endpoints are converted to serverless functions automatically. [Also see](static-app-hosting.md#vercel) for static hosting
* *Limitations*: No uptime SLA on free tier, Free tier does not allow commercial usage, observability is limited, Free tier has limited analytics

## Netlify

[Pricing page](https://www.netlify.com/pricing/)

* *Free tier*: 100GB bandwidth per month, 1 concurrent build, 300 build minutes/month, 125000 serverless function invocations per month, 100 form submissions per month, 1000 active Identity users per month, 2500 large media transformations per month
* *Pros*: Deploy with Git, Edge CDN
* *Limitations*: No site analytics on free tier

## Glitch

[Pricing page](https://glitch.com/pricing)

* *Free tier*: Instantly deployed Node.js app with collaboration tool, 1000 project hours, 4000 requests/hour, 512MB ram, 200MB disk excluding node_modules, Custom domain
* *Pros*: Based on Node.js, Online editor with real time collaboration, Live redeploy, Great for prototyping and collaboration
* *Limitations*: Free tier instances will sleep after 5 mins of inactivity but will turn on when someone accesses the website

## AppHarbor

[Pricing page](https://appharbor.com/pricing)

* *Free tier*: 1 worker unit, apphb.com hostname
* *Pros*: Auto scaling, Deploy with git, One of few PaaS for .NET apps
* *Limitations*: No custom domain on free tier

## GearHost

[Pricing page](https://www.gearhost.com/pricing)

* *Free tier*: 1 shared node and 1 worker at max, 100MB storage, 1GB bandwidth/month, Custom domains
* *Pros*: Supports .NET (4.6), PHP (5.3-5.5) and Node.js apps, MSSQL and MySQL databases, Easy publishing over FTP, WebDeploy or directly from Git/GitHub/Bitbucket
* *Limitations*: Cumulative limits for CPU (60 minutes allowed every 24 hours) and RAM (256MB allocated every hour), 1GB bandwidth allowd every 24 hours, [250 concurrent connections](https://www.gearhost.com/documentation/difference-free-standard-reserved-plans), No SSL support, only 32bits processes
* *Exceeding the free tier*: If CPU usage, RAM usage or bandwidth consumed reaches the limit within its timefame, the application goes offline until the counter resets

## OpeNode

[Pricing page](https://www.openode.io/pricing)
* *Free tier*: 100MB RAM, 1GB Storage, 100GB Bandwidth / Month
* *Limitations*: Your code will be open-sourced unless you declare your project is educational (for students)
