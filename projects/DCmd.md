---
layout: project
type: project
image: images/uh-logo.png
title: DCmd
permalink: projects/micromouse
date: 2016
labels:
  - Database
  - Groovy
  - Javascrit
  - Grails
summary: Data Center Meta Data is a Data Center Asset management system that maintains records for applications, servers, software clusters, as well as the individuals responsible for them..
---

#Data Center Meta Data

Data Center Meta Data is a Data Center Asset management system that maintains records for applications, servers, software clusters, as well as the individuals responsible for them.

DCmd is being developed on the Grails framework, and leverages the technologies of VMWare and LDAP for retrieving software and contact information; Jquery/Javascript, JQgrid, JSON/AJAX for querying and saving to the Database.

![Image of Home Page](https://raw.githubusercontent.com/uhawaii-system-its-ti-iam/DCmd/master/media/images/DCmdGUIScreenShot.PNG)

##API
For API usage, consult the [API page](https://github.com/UHMDCmd/DCmd/tree/master/api).


##JQGrid
Important information when pulling the repositiory.
Once you pull the DCmd source code, you have to follow these instructions to ensure that some of the functions for the jqgrid works.
  1. Navigate to directory DCmd[Sitar-inf] > .links_to_grails_plugins > jqgrid-3.8.0.1 > web-app > js > jqgrid 

  2. copy "ctrl-A, ctrl-C" contents of the file jquery.jqGrid.min.js 
  
  3. Navigate to directory Sitar-inf-graislPlugins>jqgrid-3.8.0.1 > web-app > js > jqgrid and replace contents of jquery.jqGrid.min.js with "ctr-A, delete, ctr-V". Then save.
