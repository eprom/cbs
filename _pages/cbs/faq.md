---
title: FAQ
author_profile: false
layout: single
permalink: /cbs/faq/
sidebar:
  nav: "cbs"
---

## What is Community Based Surveillance?

Community based surveillance (CBS) is the use of input from communities themselves to collect, analyse and interpret information on local health risks to prevent, identify and respond to disease outbreaks. As early warning of health risks leads to early action and lives saved, community based surveillance can stop disease outbreaks from turning into large scale epidemics and pandemics.

## Why is CBS needed?

Many outbreaks begin with a cluster of unwell people or sudden deaths in a community which are not detected early enough by traditional surveillance systems. Often the community members are aware of the health threat, but the people who can mobilize response resources receive this information too late to limit the spread of a disease. By allowing for volunteers from the communities to report on health situations we can ensure that help is provided in the right place at the right time. This is CBS!

Community based surveillance (CBS) is the use of feedback from community volunteers to collect, analyse and interpret information on local health risks to prevent, identify and respond to disease outbreaks. As early warning of health risks leads to early action and lives saved, community based surveillance can stop disease outbreaks from turning into large scale epidemics and pandemics.

## Why is it needed?

Public health crises, such as disease outbreaks and famine, most often occur in settings where health systems and public health surveillance are weak. This gap in national and global surveillance poses a risk to communities, as disease outbreaks can develop undetected. In an emergency, people’s vulnerabilities to health risks also increase, often simultaneously to health services being overwhelmed or put out of function.

The information needed during an emergency is often complex and is required in real-time. Information is needed for a variety of reasons: to monitor and understand health risks, to allocate resources and ensure early and effectively action in dynamic contexts. This requires reliable data from a number of sources. The Red Cross and Red Crescent Movement consists of a network of 17 million active volunteers worldwide. They can and will report what is going on in their communities – if they are given the tools to do so! By allowing for communities themselves to report on disease risk, potential outbreaks can be detected earlier, and responses can happen quicker.

## Why does the Red Cross need to build their own software?

Since starting this work in 2013, the assumption has been that technologies and tools are already out there, we just need to access and use them. But, after three implementation phases and extensive research, we have come to the conclusion that we need a custom-built application for the Red Cross Red Crescent CBS.

## Isn't there an app for this?

There are many great apps, but to reach communities with limited infrastructure we depend on using SMS as the main form of communication. Mobile internet access is often affected during an emergency, leaving many apps unaccessesible. SMS therefore becomes the most reliable reporting tool.

## Why open source?

We wouldn’t want to build something as awesome as this without making it available to anyone who might need it and benefit from it. Furthermore, we’ve benefited a lot from using open source code in components of the software and we hope that others will benefit from what we are building. The CBS platform is built by a team of amazing contributors, who contribute with their time, their skills, their dedication and great questions, for a greater good. How could we not make this open source?

## What is the technology behind CBS?

CBS is a web application built with an Angular2 frontend, a dotnet core backend and a MongoDB database. It is based on an event-driven, microservices architecture, meaning it is developed as several separate applications (or bounded contexts), but appear as one application to the end user. The bounded contexts communicate with each other by publishing and subscribing to events. In production, CBS will run in Docker containers on a managed Kubernetes cluster in Azure Container Service (AKS).

## Why are you asking us to contribute?

The Red Cross Red Crescent is a volunteer movement, with more than 17 million volunteers across the globe. CBS is built for volunteers who use the application to manage health risks in their local communities. It is built by volunteers, because it gives technologists, designers, engineers and many others the opportunity to contribute with their skills and expertise for the direct benefit of other volunteers and communities.
