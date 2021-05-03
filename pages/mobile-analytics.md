# Mobile analytics

<!-- TOC depthFrom:2 -->

- [Amazon Mobile Analytics](#amazon-mobile-analytics)
- [Countly Analytics](#countly-analytics)
- [Firebase Analytics](#firebase-analytics)
- [Flurry Analytics](#flurry-analytics)
- [Indicative Analytics](#indicative-analytics)
- [Mixpanel](#mixpanel)
- [Segment](#segment)
- [Visual Studio Mobile Center](#visual-studio-mobile-center)

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

## Flurry Analytics

[Product page](https://developer.yahoo.com/analytics)

* *Free tier*: Flurry analytics is free at any scale
* *Pros*: Extensive functionality and features including usage metrics, retention, real-time data, revenue metrics, crash reporting, custom user interaction and more. Flurry features an instant analysis tool (Flurry Explorer) that eliminates need for code and SQL for detailed look into user segmentation, interaction, funnels and retention. 
* *Limitations*: only available for native Android and iOS (no JavaScript version)

## Indicative Analytics

[Pricing page](https://www.indicative.com/pricing/)

* *Free Tier*: 1 Billion user events/actions per month, unlimited user seats, unlimited projects
* *Pros*: Full access to all customer analytics tools including unique multi-path funnel analysis, segmentation, cohorts, no need for code or SQL 
* *Limitations*: Data warehouse integrations are limited to paid tiers

## Mixpanel

[Pricing page](https://mixpanel.com/pricing/)

* *Free tier*: unlimited projects, data history, and seats, up to 100K monthly tracked users
* *Pros*: Ideal for mobile applications or "events" oriented websites, integrates well with other services like Segment, many types of reports that can be saved and used in dashboards for tracking metrics over time
* *Limitations*: some advanced reports feature gated, main limit is 5 saved reports per user, advanced data warehouse integrations are limited to paid tiers

## Segment

[Pricing page](https://segment.com/pricing)

* *Free tier*: Unlimited [integrations](https://segment.com/integrations), 1 [source](https://segment.com/sources), 1 [warehouse](https://segment.com/warehouses), 1,000 MTU (monthly tracked user)/month, 1 user, 
* *Pros*: Success engineering team is incredibly helpful around implementation and tool recommendation/consultation. Segment also supports web and mobile, as well as libraries in all of the popular languages. You have access to your raw data from day 1 to prevent vendor lock in.
* *Limitations*: data replay (replaying your data into a new tool)

## Visual Studio Mobile Center

[Pricing Page](https://docs.microsoft.com/en-us/mobile-center/general/pricing)

* *Free tier*: free during preview, unlimited reporting of up to 200 events with 5 properties max. per event, 90 days retention
* *Pros*: it provides a dashboard with metrics about active users, sessions, top devices, countries, languages and versions. It also allows to track the user’s interaction with the app by tracking events, as well as seeing the incoming logs in real-time.


