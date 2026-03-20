# Serverless app hosting

<!-- TOC depthFrom:2 -->

- [AppSail](#appsail)
- [AWS Lambda](#aws-lambda)
- [Google Cloud Functions](#google-cloud-functions)

<!-- /TOC -->

## Catalyst AppSail

[Pricing page](https://catalyst.zoho.com/free-tier.html)

* *Free tier*: 15 GB-hours/month of app execution (shared across all AppSail services in your account, renews monthly)
* *Pros*: serverless PaaS with automatic scaling, supports any language/runtime via custom Docker containers or Catalyst-managed runtimes (Node.js, Java, Python), scales to zero when idle, free tier that is refreshed every month

## AWS Lambda

[Pricing page](https://aws.amazon.com/lambda/pricing/)

* *Free tier*: 1M requests/month, 400k GB-seconds of compute time/month (memory allocated to the function * execution time)
* *Pros*: automatic scaling, integrates well with oher AWS services (S3, SQS, API Gateway...), no idle time billing only calculate your actual request consumption, supports Node.js, C#, Python, Java deployments and Go using [Apex](https://github.com/apex/apex)

## Google Cloud Functions

[Pricing page](https://cloud.google.com/functions/)

* *Free tier*: 2M requests/month, 400k GB-seconds/month, 200k GHz-seconds/month, 5GB Outbound Date, Unlimited Inbound, Unlimited Outbound to Google APIs in same region
* *Pros*: automatic scaling, easy to integrate and manage from Firebase console, Node.js support, Webhooks, integration with Google APIs like Cloud Pub/Sub
