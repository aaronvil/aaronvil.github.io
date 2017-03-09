---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

#Meteor Gotchas

For a about a week I have been working with meteor, a framework that I have been learning in my ICS 314 class. In this meteor I have been working on an assignment known as digits, which is pretty much an app that creates a contacts list that displays them in a table. The app so far as it is written can add and edit contacts on the list. Working on the code for digits using a framework has brought up some issues that I constantly have. This isn’t just meteor either, I have had this problem with other frameworks like spring and angular.

One of the most common mistake I have made in making the digits app, as well as other apps I have worked on is the importing of files. Often when I am writing the code for a page or controller, I tend to often forget to import those files into the correct files they belong. In the meteor app, I often forget to put them in the index.html file so they can be access. In another app I wrote for spring-boot, I often forget to add them to the route, causing me not to be able to access the page. There is no easy way in trying to solve problems like these unless someone makes a plugin that say “Hey you forgot to import these files”, and really it is up to the programmer to remember these have to be imported to certain files so you can access them. While I haven’t really solved a way to not do this, it helps to add them at the start. In the meteor app, there is an add and edit page. When creating both of them, they both had a html and javascript file that was the basis for the page. What helped in trying to ensure I don’t make the mistake of not importing them correctly is once I have made both files, with no code, then I import them to the proper file. This helps in making sure you don’t forget to and it is best to get it out of the way so you can worry about debugging code. Though I still forget to do this from time to time, it is a good rule to follow, once you create the file, immediately import them or call them wherever they need to be.
