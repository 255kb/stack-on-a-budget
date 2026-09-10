# Monitoring

<!-- TOC depthFrom:2 -->

- [Google Stackdriver](#google-stackdriver)
- [Healthchecks.io](#healthchecksio)
- [Honeybadger.io](#honeybadgerio)
- [Keptick](#keptick)
- [Librato](#librato)
- [MonitorMonk](#monitormonk)
- [New Relic](#new-relic)
- [OnlineOrNot](#onlineornot)
- [Sematext SPM](#sematext-spm)
- [Uptime Robot](#uptime-robot)
- [PingPong](#pingpong)

<!-- /TOC -->

## Google Stackdriver

[Pricing page](https://cloud.google.com/stackdriver/pricing)

* *Free tier*: 5 GB of logs with 7 day retention, read access API, basic email alerting
* *Pros*: Integrated monitoring, logging and diagnostics suite for applications running on Google Cloud Platform and Amazon Web Services.

## Healthchecks.io

[Product page](https://healthchecks.io)

* *Free tier*: monitor up to 20 jobs, invite two team members.
* *Pros*: Monitor cron jobs, background services, scheduled tasks. API access, many integrations, open-source (can be self-hosted).
* *Limitations*: no SMS notifications for the free tier, no SSO login options

## Honeybadger.io

[Pricing page](https://www.honeybadger.io/plans/)

* *Free tier* tier: 1000 errors per month, unlimited projects.
* *Pros*: Full stack Exception monitoring, Uptime monitoring, and Check-in/Cron Monitoring
* *Limitations*: 3 users, 15 day data retention, 5 uptime checks and 5 check-ins per month. Integrates with: GitHub, GitLab, SMS, Email, Slack, and more
* *Exceeding the free tier*: Honeybadger continues to process up to 125% of the limit before stop processing data until the end of the month. Also sends email alerts.

## Keptick

[Product and pricing](https://keptick.aifirm.app/?utm_source=github&utm_medium=directory&utm_campaign=e08_stack_budget#pricing) - [Usage guide](https://keptick.aifirm.app/guide?utm_source=github&utm_medium=directory&utm_campaign=e08_stack_budget)

* *Free tier*: One workflow monitor, 500 outcome receipts per day, seven-day detailed history and opt-in email alerts. The first monitor stays available after the 14-day workspace trial.
* *Pros*: Accepts JSON receipts over HTTP and checks reported failures, output counts below a chosen minimum, and missing runs. Includes n8n outcome and error-workflow templates.
* *Limitations*: 30 receipts per monitor per minute; the dashboard shows up to 100 recent outcomes per monitor. Missing-run checks start about every five minutes and may take additional cycles; email adds delivery delay. Depends on the workflow reporting completed work accurately.
* *Exceeding the free tier*: Ingestion returns HTTP 429 when a receipt limit is reached. Additional monitors require a paid subscription after the trial. There are no automatic overage charges or automatic paid conversion.
* *Credit card required*: No.

## Librato

[Pricing page](https://www.librato.com/pricing)

* *Free tier*: (Developer plan) 100 metric streams at 60s resolution 1 day retention, 10 alerts, 1 dashboard.
* *Pros*: allows for submission of metrics from multiple sources, metrics can be submitted via an agent or directly to the API.

## MonitorMonk

[Product page](https://monitormonk.com/) - [Pricing page](https://monitormonk.com/#pricing)
- *Free tier*: Up to 10 websites or APIs (urls), 2 public status pages ("dashboards"), 1-minute check intervals.
- *Pros*: HTTPS, keyword, page speed and SSL certificate monitoring. Minimalist approach. Nice status pages. Quick setup.
- *Limitations*: Single user (no team members), no history.
- *Exceeding the free tier*: Not possible to exceed limits. You can upgarde for higher quotas though.
- *Credit card required*: No. The free plan is forever free.

## New Relic

[Pricing page](https://newrelic.com/pricing)

* *Free tier*: 100 GB/month, 1 free full access user, unlimited free basic users.
* *Pros*: Collect all your telemetry data (including logs) in one place to deliver full-stack observability and power AI-driven insights so you can confidently improve service reliability and accelerate time to market. Supports most popular back-end, front-end, infrastructure, and cloud frameworks and services.
* *Exceeding the free tier*: After exceeding the 100 GB/month you will see a paywall asking you to add a credit card. Data collection will continue and access to key pages to lower data ingest will still be available.

## Sematext SPM

[Product page](https://sematext.com/spm) - [Pricing page](http://sematext.com/spm/#plans-and-pricing)

* *Free tier*: 30 minutes retention, 5 hosts, unlimited dashboards, unlimited users, 1 alert
* *Pros*: includes APM, infrastructure monitoring, and custom metrics, out of the box charts and filtering, REST API, correlation with logs, integration with Slack, HipChat, PagerDuty, OpsGenie, VictorOps, BigPanda, WebHooks, Nagios...

## Uptime Robot

[Product page](http://uptimerobot.com/)

* *Free tier*: 50 websites/servers, 5 minutes intervals
* *Pros*: multiple check supported (HTTP, ping, port...), dashboard with statistics, supports alerts via multiple canals (e-mail, Twitter, Slack, HipChat, push, SMS, web-hook notifications...)
* *Limitations*: Monitoring location cannot be customized


## OnlineOrNot

[Product page](http://onlineornot.com/) - [Pricing page](https://onlineornot.com/pricing)

- *Free tier*: Uptime Monitoring: 10 websites, 5 minute intervals, Page Speed Monitoring: 10 websites, 12 hour intervals
- *Pros*: Dashboard with uptime and page speed statistics, paid users are able to invite their whole team at no extra cost, supports alerts via multiple channels (e-mail, Slack)
- *Limitations*: Currently only supports HTTP/HTTPS monitoring, not possible to customise the monitoring location
- *Exceeding the free tier*: Not possible - users aren't able to add resources beyond the free limits.

## PingPong

[Product page](https://pingpong.one/) - [Pricing page](https://pingpong.one/pricing/)

* *Free tier*: Public, customizable status page with custom subdomain with SSL
* *Pros*: Includes unlimited components, incident reports and scheduled maintenance. With badges and integrations to showcase system status on users' website
* *Limitations*: No service monitoring, team members, subscribers, custom domain, only e-mail notifications, Slack manager, sync subscribers with customer service software like Intercom

## Phare

[Product page](https://phare.io) - [Pricing page](https://phare.io/pricing)

* *Free tier*: 100k monthly monitoring events, 30s intervals, unlimited users, unlimited projects, unlimited status pages
* *Pros*: Bootstrapped european company, 11 monitoring regions, no feature gating with affordable paid tier.
* *Limitations*: No IP filtering, TCP monitoring on ports 25, 465, 587 and 2525 is restricted.
* *Exceeding the free tier*: You will get alerted before consuming all your quota, an overage of 10% is allowed before locking your resources. 
