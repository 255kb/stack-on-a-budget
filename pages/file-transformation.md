# File transformation

<!-- TOC depthFrom:2 -->

- [Cloudinary](#cloudinary)
- [CurlShot](#curlshot)
- [Filestack](#filestack)
- [PDFSpark](#pdfspark)

<!-- /TOC -->

## Cloudinary

[Pricing page](https://cloudinary.com/pricing)

* *Free tier*: 25 monthly credits (on a rolling 30-day window). 1 credit equals 1 GB of storage, 1 GB of viewing bandwidth, or 1,000 transformations (mix and match across storage, bandwidth, and transformations as needed).
* *Pros*: Free tier includes image and video manipulations (resizing, AI effects, overlays, auto-format, quality optimization), backup and revisions, supports PDF, animated GIFs, video transcoding, and global CDN delivery. Provides SDKs in multiple languages.
* *Limitations*: Free tier does not offer custom domain (CNAME) and has concurrency limits on transformations.
* *Exceeding the free tier*: Account features are restricted/blocked when limits are reached until usage falls below the threshold or the plan is upgraded (no surprise overage charges on the free plan).
* *Credit card required*: No

## CurlShot

[Pricing page](https://curlshot.com/pricing)

* *Free tier*: 100 screenshots/month (URL, HTML or Markdown to PNG, JPEG, WebP, PDF or scrolling video), 10 requests/minute, 1 render at a time
* *Pros*: one GET request returns the file, so it also works from `curl`, an `<img>` tag or no-code tools; full-page and single-element capture, ad and cookie-banner blocking; failed renders and cache hits are not counted; OpenAPI spec and a hosted MCP server for AI agents
* *Limitations*: lower maximum height and pixel density for full-page captures on the free plan
* *Exceeding the free tier*: the API answers `402 quota_exceeded` until the next monthly period; nothing is charged
* *Credit card required*: No

## Filestack

[Pricing page](https://filestack.com/pricing)

* *Free tier*: 250 file uploads/month, 500 file transformations/month, 3GB bandwidth/month
* *Pros*: image and video transformations, document file conversions, audio/video transcoding, free CDN, HTML widget, iOS SDK, tons of cloud storage integrations
* *Limitations*: file upload size limited to 50 MB, free tier does not offer custom CNAME, S3 as file source is premium feature

## PDFSpark

[Home page](https://pdfspark.dev)

* *Free tier*: Free HTML and URL to PDF conversion API with no authentication required
* *Pros*: Convert any HTML content or URL to a high-quality PDF document via a simple API call; no API key or signup needed; supports custom page sizes and options
* *Limitations*: Rate limited on the free tier
* *Credit card required*: No
