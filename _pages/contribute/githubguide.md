---
title: GitHub guide for CBS 
layout: single
permalink: /contribute/githubguide/
sidebar:
    nav: "contribute" 
---

 

## Read the contributor guide and code of conduct. 

Make sure you have the required development environment set up 

Understand the project structure: 

CBS has been divided into 5 bounded contexts (or projects/modules) as explained 

Each module has its own subfolder in the Source folder, containing a .sln file. Everything you need to build and run the module can be found within the specified folder for said module. 
For example: Everything you need to build and run the "Volunteer Reporting" module, can be found in the Volunteer Reporting folder under Source. 

In addition to this, each module has its own documentation and its own backlog. The documentation can be found in the Documentation/Projects folder while the backlog can be found on the GitHub project page. 
For example: The documentation for the "Volunteer Reporting" module can be found in the Volunteer Reporting folder. The backlog can be found on the "Volunteer Reporting" project page. 

Find an issue you want to work on. Issues labeled "good first issues" are issues that should be relatively easy to get started on without too much background information. Any issue labeled "good first issue" will be linked to a project/module so that you will be able to find the source code and documentation for the module. 

Create a fork. In order to contribute to this project, you will need to fork this repository. 

Make changes, test them and ensure the documentation is up to date. All commits SHOULD be related to an issue by adding a #{number of issue} to the comment. 

Synchronize your fork. Keep your fork synchronized with the CBS repository to avoid conflicts, as described here. 

Create a pull request. Once your changes are ready, create a pull request and reference the issues you have worked on. 