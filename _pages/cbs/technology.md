---
title: Technology
layout: single
permalink: /cbs/technology/
sidebar:
  nav: "cbs"
---

Since starting this work in 2013, the assumption has been that technologies and tools are already out there, we just need to access and use them. But, after three implementation phases and extensive research, we have come to the conclusion that we need a custom-built application for the Red Cross Red Crescent CBS.

In simple terms, the Red Cross CBS platform allows for community volunteers to send SMS reports when they witness health risks. The health risks are fed into a dashboard, where we are able to track cases and take action when caseloads increase. The ability to send and receive text messages, parse and analyses the results, as well as visualize data has been previously demonstrated through existing technological solutions.  What truly makes the CBS platform special is that it completes these existing functions, but it further aims to identify clusters of diseases, directly notify health responders for verification, and provide educational messages to the hands of volunteers so they can continuously improve their knowledge to respond to health needs in their communities. 

CBS is a web application built with an Angular2 frontend and a dotnet core backend. It is based on an event-driven, microservices architecture, meaning it is developed as several separate applications (or bounded contexts), but appear as one application to the end user. The bounded contexts communicate with each other by publishing and subscribing to events. In production, CBS will run in Docker containers on a managed Kubernetes cluster in Azure Container Service (AKS). It is all open-source and all the techy-information behind the software can be found on our [GitHub page](https://github.com/IFRCGo/cbs).

An MVP is currently operational in Somalia and we are constantly looking for people to help us improve the software. [Click here to see how you can contribute](https://cbsrc.org/contribute/)!

| Name | Description | Issues |
|---|---|---|
| [Volunteer Reporting](https://github.com/IFRCGo/cbs/blob/master/Documentation/Projects/Volunteer%20Reporting/index.md) | Processing all incoming case reports from data collectors in the field and allowing for communication with the data collectors through ad-hoc and regular text messages. | [link](https://github.com/IFRCGo/cbs/projects/4) |
| [Reporting](https://github.com/IFRCGo/cbs/blob/master/Documentation/Projects/Reporting/index.md) | Web-based visualization of all incoming case reports. The level of detail within a report is dependent on the "role" of the user. | [link](https://github.com/IFRCGo/cbs/projects/5) |
| [Admin](https://github.com/IFRCGo/cbs/blob/master/Documentation/Projects/Admin/index.md) | Web-based interface for system admins where they define the global configuration within CBS, such as alert thresholds, health events, SMS gateway to use etc. They also have the ability to create new CBS projects. | [link](https://github.com/IFRCGo/cbs/projects/1) |
| [User Management](https://github.com/IFRCGo/cbs/blob/master/Documentation/Projects/User%20Management/index.md) | Web-based user management, where data collectors, data managers, data coordinators etc are associated with one or several CBS projects. | [link](https://github.com/IFRCGo/cbs/projects/2) |
| [Alerts](https://github.com/IFRCGo/cbs/blob/master/Documentation/Projects/Alerts/index.md) | Case report escalation when an alert threshold is reached. Escalation in this case can mean notifying nearby data collectors of health events, notifying data managers and notifying local authorities such as the Ministry of Health. | [link](https://github.com/IFRCGo/cbs/projects/6) |
| [Portal & Infrastructure](https://github.com/IFRCGo/cbs/blob/master/Documentation/Projects/Portal/index.md) | "Glue" for navigating between bounded context. | [link](https://github.com/IFRCGo/cbs/projects/15) |
