---
title: I use CloudFlare for Performance and Security
layout: post
headerImage: true
tag:
- DNS
- Management
- CloudFlare
- Security
- jekyll
- gh-pages
- nepal
star: true
category: blog
author: alonshrestha
summary: "You can insert notes, tips, warnings, and important alerts in your content. These notes make use of Bootstrap styling and are available through data references such as site.data.alerts.note."
sidebar: mydoc_sidebar

---

{% include note.html content="This is my note. All the content I type here is treated as a single paragraph." %}

* TOC
{:toc}

{% include important.html content="This is my note. All the content I type here is treated as a single paragraph." %}

{% include warning.html content="This is my note. All the content I type here is treated as a single paragraph." %}

{% include tip.html content="This is my note. All the content I type here is treated as a single paragraph." %}

{% include callout.html heading="This is me" content="This is my note. All the content I type here is treated as a single paragraph." %}

{% include summaryCallout.html heading="This is me" content="This is my note. All the content I type here is treated as a single paragraph." %}

{% include summaryCallout.html heading="Table of content" content=" {:toc} " %}


## About alerts

Alerts are little warnings, info, or other messages that you have called out in special formatting. In order to use these alerts or callouts, reference the appropriate value stored in the alerts.yml file as described in the following sections.