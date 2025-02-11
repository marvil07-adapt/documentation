---
title: "Measuring with hosted service"
description: "User our hosted service to measure applications on Github."
date: 2022-06-21T08:49:15+00:00
weight: 806
toc: true
---

In order to use our hosted service your application must already be on Github, be [containerized →]({{< relref "containerizing-applications" >}}) and contain a [usage_scenario.yml →]({{< relref "usage-scenario" >}}) file.

If you do not have that, please check out the relevant links given.

## Trying out the hosted service with an example application

You can supply the Github link to our provided [easy example application](https://github.com/green-coding-berlin/simple-example-application) and wait for an email to arrive to view a report.

This example highlights that in order to measure an application you really need to only have a repository with a
 [usage_scenario.yml →]({{< relref "usage-scenario" >}}) file.

<img src="/img/add-new-project.webp">

## Measuring your applications

The hosted service can really helpful when you want to measure your application a 
reference machine and see if the values you are getting are in the same order of magnitude.

The hosted service is free to use and makes your measurement data visible and reproducible for other people.

### Benefits of hosted service
- No need to setup local linux environment
- Reproducible measurements from machines maintained by our team
- DC / AC Metrics Providers are calibrated on our machines
- Visibility of measurements on central platform
- Applied [best practices →]({{< relref "best-practices" >}}) for measurement configuration
