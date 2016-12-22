# Database hosting

## Firebase database

[Pricing page](https://firebase.google.com/pricing/)

* *Free tier*: 1GB storage, 10GB/month transfer, 100 simultaneous connections
* *Pros*: really fast can be used for real time pub/sub, libraries for multiple platforms, designed to be used directly from frontend (with security rules), integrates with Firebase Authentication
* *Limitations*: no backups, limited queries, complicated security rules (read the manual!)

## GearHost Database

[Pricing page](https://www.gearhost.com/pricing)

* *Free tier*: 5MB MySQL database or 10MB MS SQL database
* *Pros*: Recent versions (MySQL 5.6, MS SQL Server 2014)
* *Limitations*: simultaneous connections seems to be limited (according to [this page](http://talk.gearhost.com/t/restrictions-or-limitations-of-the-free-account/105), approx. 15)
* *Exceeding the free tier*: The database becomes locked and a kind email is sent asking to upgrade to paid plan

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

## mLab

[Pricing page](https://mlab.com/plans/pricing/)

* *Free tier*: 500MB storage, daily backup
* *Pros*: managed on AWS, Azure or Google Cloud, data browser, monitoring

## Redis Cloud

[Pricing page](https://redislabs.com/pricing)

* *Free tier*: 30MB, 30 connections
* *Pros*: managed, possibility to choose cloud provider (AWS, Azure, GCE, IBM Softlayer) and availability zones
