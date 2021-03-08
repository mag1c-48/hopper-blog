---
title: "Setting Up The Server"
date: 2021-01-29T21:03:40Z
draft: false
---

Here we will be talking about the steps taken to choose where our server is located, and what is needed on our server.  

## The location  
We thought about this a lot, whether we wanted our server on a cloud provider such as AWS, Digital Ocean, Google Cloud or Azure or whether we wanted to host the server oursevles as one of us just happens to have a server machine at home. However we decided to go with Microsoft's Azure platform. Mainly for the reason that their student credits meant that we were able to get a rather strong, capable machine up and running free of cost for the duration of our project. That and for the fact that one of us had some prior experience with Azure as a platform. That extra aura of familiarity really helped with getting started.

## Dependencies  
Next came figuring out what dependencies were needed on our server for everything to function smoothly. We knew we definitely needed Wetty and we definitely needed Docker, well Docker was easy to install, wetty? not so much. Docker was simply allowing apt to link to remote repositories and installing through that. Wetty had a lot of dependencies of its own to install first before we installed wetty itself. Using the wetty docs to figure out what was needed we installed the likes of build-essential, nodejs, npm and we had to make sure our Python version was up to date. Once that was done we installed Yarn with the use of npm.

## Conclusion  
With all of our dependencies set up, after much thought figuring out what was needed and what was necessary, we were now ready to move onto working on the main aspects of our project.
