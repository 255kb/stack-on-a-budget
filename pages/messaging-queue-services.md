# Messaging queue services

<!-- TOC depthFrom:2 -->

- [CloudAMQP](#cloudamqp)
- [Google Cloud Pub/Sub](#google-cloud-pubsub)

<!-- /TOC -->

## CloudAMQP

[Pricing page](https://www.cloudamqp.com/plans.html)

* *Free tier*: 1M messages/month, 100 queues, up to 20 concurrent connections, 10k queued messages
* *Pros*: offers replication, monitoring, administration interface; supports following hosting providers: AWS, Azure, Google, Digital Ocean
* *Limitations*: Allows maximum idle queue time of 28 days (can be removed by removing the default policy)

## Google Cloud Pub/Sub

[Pricing page](https://cloud.google.com/pubsub/pricing)

* *Free tier*: Free first 10GB
* *Pros*: Replication, 10k messages per second, by default, millions per second and beyond, upon request. Integration with Google Cloud Dataflow for analytics.

