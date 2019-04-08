# Serverless app hosting

<!-- TOC depthFrom:2 -->

- [AWS Lambda](#aws-lambda)
- [Google Cloud Functions](#google-cloud-functions)
- [Hook.io](#hook-io)

<!-- /TOC -->

## AWS Lambda

[Pricing page](https://aws.amazon.com/lambda/pricing/)

* *Free tier*: 1M requests/month, 400k GB-seconds of compute time/month (memory allocated to the function * execution time)
* *Pros*: automatic scaling, integrates well with oher AWS services (S3, SQS, API Gateway...), no idle time billing only calculate your actual request consumption, supports Node.js, C#, Python, Java deployments and Go using [Apex](https://github.com/apex/apex)

## Google Cloud Functions

[Pricing page](https://cloud.google.com/functions/)

* *Free tier*: 2M requests/month, 400k GB-seconds/month, 200k GHz-seconds/month, 5GB Outbound Date, Unlimited Inbound, Unlimited Outbound to Google APIs in same region
* *Pros*: automatic scaling, easy to integrate and manage from Firebase console, Node.js support, Webhooks, integration with Google APIs like Cloud Pub/Sub

## Hook io

[Pricing page](https://hook.io/pricing)
* *Free Tier*: 1k requests/month, 2 concurrent requests, 20 services, logs, cron jobs, 100 datastore documents, 100MB file-system storage
* *Pros*: Open-Source Hosting platform Optimized for deploying webhooks and microservices. Comes with a datastore or virtual file system out of the box. 
* *Cons*: They don't allow long running services by design.
* *Limitations*: 10s max service timeout, no custom domains, no role based access control, no support
