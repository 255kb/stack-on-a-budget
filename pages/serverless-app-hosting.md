# Serverless app hosting

<!-- TOC depthFrom:2 -->

- [AWS Lambda](#aws-lambda)
- [Webtask](#webtask)

<!-- /TOC -->

## AWS Lambda

[Pricing page](https://aws.amazon.com/lambda/pricing/)

* *Free tier*: 1,000,000 requests/month, 400,000 GB-seconds of compute time/month (memory allocated to the function * execution time)
* *Pros*: automatic scaling, integrates well with oher AWS services (S3, SQS, API Gateway...), no idle time billing only calculate your actual request consumption, supports Node.js, C#, Python, Java deployments and Go using [Apex](https://github.com/apex/apex)

## Webtask

[Pricing page](https://webtask.io/pricing)

* *Free tier*: 2 containers, cron jobs (schedule tasks)
* *Pros*: amazingly easy deployment of serverless Node.js web handlers, 500 KB storage for each handler, supports authentication with [Auth0](user-authentication.md/#auth0)
* *Limitations*: 1 request/sec/container
