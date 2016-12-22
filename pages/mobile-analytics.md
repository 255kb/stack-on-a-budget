# Mobile analytics

<!-- TOC depthFrom:2 -->

- [Amazon Mobile Analytics](#amazon-mobile-analytics)
- [Countly Analytics](#countly-analytics)
- [Firebase Analytics](#firebase-analytics)
- [Mixpanel](#mixpanel)

<!-- /TOC -->

## Amazon Mobile Analytics

[Pricing page](https://aws.amazon.com/mobileanalytics/pricing/)

* *Free tier*: 100 millions basic sessions and custom events per month
* *Pros*: provide dashboard with various metrics (sessions, active users, revenues per user, retention, etc), data can be exported in CSV format, events can be sent through SDKs or REST API, provide iOS, Android and JavaScript SDKs, events are send in batch and cached until the device is online
* *Limitations*: export to S3 or RedShift is subject to these services respective pricings

## Countly Analytics

[Product page](https://count.ly/product)

* *Free tier*: Countly Community Edition (for mobile, web and desktop analytics) is free to download and use.
* *Pros*: Client and server side application are open source (AGPLv3). Installable on-premises, based on MongoDB and Node.js. Data can be exported in CSV, XLS format or can be read through API. More than 10 SDKs including Android, iOS, Windows Phone, MacOS and Windows. Plugin based infrastructure. Countly Community Edition also includes crash reporting and push notifications.
* *Limitations*: Community Edition has less number of features than Countly Enterprise Edition (e.g Drill, User Profiles, etc).

## Firebase Analytics

[Product page](https://firebase.google.com/docs/analytics/)

* *Free tier*: unlimited reporting of 500 events each with max. 25 attributes
* *Pros*: provide dashboard with various metrics (sessions, active users, revenues per user, retention, etc), demographic segmentation linked to other services (Push notifications), can be exported to BigQuery
* *Limitations*: only available for native Android and iOS (no JavaScript version)

## Mixpanel

[Pricing page](https://mixpanel.com/pricing/)

* *Free tier*: unlimited projects, 20 millions data points/month/project, 1 custom event/project, 60 days data history
* *Pros*: Ideal for mobile applications or "events" oriented websites
* *Limitations*: limited to 3 team members, funnels and segmentation limited to 2 filters
