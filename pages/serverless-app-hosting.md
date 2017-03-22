# Serverless app hosting

<!-- TOC depthFrom:2 -->

- [AWS Lambda](#aws-lambda)
- [Google Cloud Functions](#google-cloud-functions)
- [Webtask](#webtask)

<!-- /TOC -->

## AWS Lambda

[Pricing page](https://aws.amazon.com/lambda/pricing/)

* *Free tier*: 1,000,000 requests/month, 400,000 GB-seconds of compute time/month (memory allocated to the function * execution time)
* *Pros*: automatic scaling, integrates well with oher AWS services (S3, SQS, API Gateway...), no idle time billing only calculate your actual request consumption, supports Node.js, C#, Python, Java deployments and Go using [Apex](https://github.com/apex/apex)

## Google Cloud Functions

[Pricing page](https://cloud.google.com/functions/)

* *Free tier*: 2,000,000 requests/month, 400 000 GB-seconds/month, 200 000 GHz-seconds/month, 5GB Outbound Date, Unlimited Inbound, Unlimited Outbound to Google APIs in same region
* *Pros*: automatic scaling, easy to integrate and manage from Firebase console, Node.js support, Webhooks, integration with Google APIs like Cloud Pub/Sub

## Webtask

[Pricing page](https://webtask.io/pricing)

* *Free tier*: 2 containers, cron jobs (schedule tasks)
* *Pros*: amazingly easy deployment of serverless Node.js web handlers, 500 KB storage for each handler, supports authentication with [Auth0](user-authentication.md/#auth0)
* *Limitations*: 1 request/sec/container
