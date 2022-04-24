---
title: "Project Summary"
permalink: about/project-summary.html
layout: page
menus:
  about:
    identifier: project_summary
    is_child: True
    weight: 1
---

# Project Summary


## Motivations:
* Data is a key instrument for making Broadway the best it can be.
* Broadway data is not accessible for large scale analysis.
* Those using Broadway data for analysis or reporting
  do so with limited and private datasets – this hinders transparency,
  collboration, and scalability.

## Goals:
* Provide Broadway data for large scale analysis.
* Allow edits to existing data using a role based review process.
  * Use this interface to collect demographic data.
* Make demographic data available for reporting, using role based access control.


## Successes:
* We were able to get a POC up and running pretty quickly.
* We were able to deliver a meaningful experience by tailering the
platform to our early users.
* Our platform did its job in allowing collection of and secure access to
demographic data.

## Challenges:
* Getting the data itself is difficult without partnerships.
* Technical limitations:
  * Writing code for a secure platform is challenging – it's also
    hard to find volunteers who can do it.
  * Horizontally scalable systems: each layer in a [multi-tier architecture](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/n-tier)
    needs to scale horizontally to handle spikes in traffic (as well as
    control server costs). This is hard to architect and build.

-----
