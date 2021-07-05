# Database hosting

<!-- TOC depthFrom:2 -->

- [AWS DynamoDB](#aws-dynamodb)
- [Cloudant CouchDB](#cloudant-couchdb)
- [DataStax Astra Cassandra](#datastax-astra-cassandra)
- [Dydra](#dydra)
- [ElephantSQL](#elephantsql)
- [Fauna](#fauna)
- [Firebase database](#firebase-database)
- [Google Cloud Datastore](#google-cloud-datastore)
- [Heroku Postgres](#heroku-postgres)
- [Heroku Redis](#heroku-redis)
- [InfluxDB Cloud](#influxdb-cloud)
- [MongoDB Atlas](#mongodb-atlas)
- [OpenShift MongoDB](#openshift-mongodb)
- [Oracle Cloud Free Tier](#oracle-cloud-free-tier)
- [Railway](#railway)
- [Redis Cloud](#redis-cloud)
- [Supabase Postgres](#supabase-postgres)

<!-- /TOC -->

## AWS DynamoDB

[Pricing page](https://aws.amazon.com/dynamodb/pricing/)

- *Free tier*: 25 GB of Storage, 25 Units of Write Capacity, 25 Units of Read Capacity
- *Pros*: A NoSQL database with both document and key-value store models, replicated with high availability.  The free tier is enough to handle up to 200M requests per month.
- *Limitations*: One unit of read/write capacity handles one request per second (or two requests per second in the case of eventually consistent reads). Has both strongly consistent and eventually consistent reads.

## Cloudant CouchDB

[Pricing page](https://www.ibm.com/cloud/cloudant/pricing)

* *Free tier*: 1$/GB per month, $0.015$/100 "heavy" requests, $0.015/500 "light" requests,  first $50 per month free
* *Pros*: Full CouchDB hosting. Can host also static sites and javascript applications
* *Limitations*: Account on shared multitenant instance
* *Exceeding the free tier*: Credit card needed after first 30 days to charge exceeding usage


## DataStax Astra Cassandra
[Product page](https://www.datastax.com/products/datastax-astra)

* *Free tier*: 25$ per month for free, serverless databases. Up to 30 million reads, 4.5 million writes, 40GB in total.
* *Pros*: Unlimited number of databases, Grafana-based health monitor, multiple providers (GCP, Azure, AWS)
* *Limitations*: Does not support VPC peering, multi-region databases, materialized views, or logged batches

## Dydra

[Product page](https://dydra.com)

* *Free tier*: Simple graph storage with unlimited repositories (public and private)
* *Pros*: Repositories support [SPARQL Query](http://www.w3.org/TR/sparql11-protocol/#query-operation), [SPARQL Update](http://www.w3.org/TR/sparql11-protocol/#update-operation) and [SPARQL Graph protocol](http://www.w3.org/TR/sparql11-http-rdf-update/) and [query federation](http://docs.dydra.com/federation). There is also a simple Web interface for querying datasets, a Web API and a Command-line interface
* *Limitations*: Invite Only.

## ElephantSQL

[Product page](https://www.elephantsql.com/)

* *Free tier*: 20MB storage, 5 simultaneous connections
* *Pros*: SQL web browser for simple database inspection, secure connection over SSL, full automatic backups
* *Limitations*: No SLA no in-memory cache, shared server

## Fauna

[Product page](https://fauna.com/)

* *Free tier*: 100k read ops, 100k write ops, 500k compute ops, 100MB storage
* *Pros*: Serverless with global replication and ACID transactions. Native GraphQL support, ABAC security model and support for relational, document, graph, and time-series patterns.
* *Limitations*: No team management or preview sandbox on free tier.
* *Exceeding the free tier*: Hard limits enforced on free tier. Subscription plans offer metered overages.

## Firebase database

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1GB storage, 10GB/month transfer, 100 simultaneous connections
* *Pros*: really fast can be used for real time pub/sub, libraries for multiple platforms, designed to be used directly from frontend (with security rules), integrates with Firebase Authentication
* *Limitations*: no backups, limited queries, complicated security rules (read the manual!)

## Google Cloud Datastore

[Product page](https://cloud.google.com/datastore/)

* *Free tier*: 1GB storage/day, 50K reads/day, 20K writes/day, 20K deletes/day
* *Pros*: dashboard, clients available in multiple languages, fully managed (sharding and replication), ACID transactions
* *Limitations*: complex requests needs specific indexes (read the manual)

## Heroku Postgres

[Product page](https://www.heroku.com/postgres)

* *Free tier*: 10K rows/month, 20 simultaneous connections
* *Pros*: dashboard, secured
* *Limitations*: SLA with maximum of 4 hours of downtime/month (99.5% uptime), no in-memory cache, no expensive queries support

## Heroku Redis

[Product page](https://www.heroku.com/redis)

* *Free tier*: 25MB ram, 20 connections
* *Pros*: dashboard, secured, analytics, access via Heroku CLI
* *Limitations*: SLA with maximum of 4 hours of downtime/month

## InfluxDB Cloud

[Product page](https://www.influxdata.com/products/influxdb-cloud/)

* *Free tier*: Writes: 5MB every 5 minutes, Tasks & Queries: 300MB every 5 minutes, Storage: 30 days of retention, Cardinality: Up to 10,000 series, Alerting: 2 alert checks and 2 notification rules, You can create up to: 5 dashboards, 5 tasks, 2 databases to store your time series data
* *Pros*: purpose-built time series database, pre-built UI and dashboarding tools, background processing and monitoring agent

## mLab

[Pricing page](https://mlab.com/plans/pricing)

* *Free tier*: 500MB storage, daily backup
* *Pros*: managed on AWS, Azure or Google Cloud, data browser, monitoring

## MongoDB Atlas

[Pricing page](https://www.mongodb.com/cloud/atlas/pricing)

* *Free tier*: Start with a free 3-node replica set and 512 MB of storage / Shared RAM.
* *Pros*: Fast, secure, and highly available MongoDB service for any scale.

## OpenShift MongoDB

[Product Page](https://developers.openshift.com/databases/mongodb.html)

* *Free tier*: 1Gb storage
* *Pros*: Easy to deploy
* *Limitations*: Only support mongodb 2.4

## Oracle Cloud

[Product Page](https://www.oracle.com/cloud/free/#always-free)

* *Free tier*: 2 Autonomous Database instances with 1 OCPU and 20GB storage each
* *Pros*: Flexible workload tuning
* *Limitations*: Maximum of 20 simultaneous database sessions

## Railway

[Pricing page](https://railway.app/pricing)

* *Free tier*: 1GB memory per container, shared CPU, 1GB disk usage (10GB hard limit), 100GB outbound traffic (unlimited inbound). [Read more](https://railway.app/legal/fair-use)
* *Pros*: Allows hosting multiple databases (PostgreSQL, MySQL, Redis, MongoDB) and you can have your app and database on the same platform and run both of them for free. [Also see](app-hosting.md#railway) for app hosting.
* *Limitations*: 3 projects, 2 plugins per project, 2 environments per project, 3 live deploys per environment.

## Redis Cloud

[Pricing page](https://redislabs.com/pricing)

* *Free tier*: 30MB, 30 connections
* *Pros*: managed, possibility to choose cloud provider (AWS, Azure, GCE, IBM Softlayer) and availability zones

## Supabase Postgres

[Pricing Page](https://supabase.io/pricing)

* *Free tier*: 500Mb storage, 100 simultaneous connections
* *Pros*: Open source, built in realtime capabilities and auth, 40+ extensions and pgbouncer preinstalled
* *Limitations*: Paused after 1 week of inactivity
* *Exceeding the free tier*: There are no overage charges. Team will reach out asking user to upgrade to a higher plan if limits are exceeded.
