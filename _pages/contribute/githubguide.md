---
title: GitHub guide for CBS 
layout: single
permalink: /contribute/githubguide/
sidebar:
    nav: "contribute" 
---

 

1) Read the [contributor guide](https://github.com/IFRCGo/cbs/blob/master/Documentation/Contribution/contributing.md) and [code of conduct](https://cbsrc.org/contribute/codeofconduct/). 

2) Make sure you have the required [development environment](https://github.com/IFRCGo/cbs/blob/master/Documentation/Contribution/development_environment.md) set up 

3) Understand the project structure: 
- CBS has been divided into [5 bounded contexts](https://src.cbsrc.org/cbs/technology/) (or projects/modules). Each module has its own subfolder in the [source folder](https://github.com/IFRCGo/cbs/tree/master/Source), containing a .sln file. Everything you need to build and run the module can be found within the specified folder for said module. *For example: Everything you need to build and run the "Volunteer Reporting" module, can be found in the [Volunteer Reporting]* (https://github.com/IFRCGo/cbs/tree/master/Source/VolunteerReporting) folder under Source. 
- In addition to this, each module has its own documentation and its own backlog. The documentation can be found in the [Documentation/Projects folder](https://github.com/IFRCGo/cbs/tree/master/Documentation/Projects) while the backlog can be found on the [GitHub project page](https://github.com/IFRCGo/cbs/projects). *For example: The documentation for the "Volunteer Reporting" module can be found in the [Volunteer Reporting folder](https://github.com/IFRCGo/cbs/blob/master/Documentation/Projects/Volunteer%20Reporting/index.md). The backlog can be found on the ["Volunteer Reporting" project page](https://github.com/IFRCGo/cbs/projects/4)*. 
- Find an issue you want to work on. Issues labeled ["good first issues"](https://github.com/IFRCGo/cbs/labels/good%20first%20issue) are issues that should be relatively easy to get started on without too much background information. Any issue labeled "good first issue" will be linked to a project/module so that you will be able to find the source code and documentation for the module. 
- Create a fork. In order to contribute to this project, you will need to [fork this repository](https://help.github.com/articles/fork-a-repo/). 
- Make changes, test them and ensure the documentation is up to date. All commits SHOULD be related to an issue by adding a #{number of issue} to the comment. 
- Synchronize your fork. Keep your fork synchronized with the CBS repository to avoid conflicts, as described here. 
- Create a [pull request](https://help.github.com/articles/creating-a-pull-request/). Once your changes are ready, create a pull request and reference the issues you have worked on. 

Got questions? [Contact us](https://src.cbsrc.org/contactus/) for clarification or more information!
