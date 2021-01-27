---
title: "What Is Hopper"
date: 2021-01-27T00:07:23Z
draft: false
---

# What is it?
To put simply? Hopper is a tool to access easily discardable containers running linux on the web!

# The longer story
Our idea is to provide users with discardable containers in which they have full access to the system in which their actions have no consequences on the system at large as each container can easily be discarded. Administrators can set exercises that can be found on an /exercises endpoint on the website, the users can then complete the exercises in the container and then their solution could be evaluated by a script mounted on a Docker volume. The users can request to have their logs sent to them via email after each container discard. Users would connect to the service by logging into a website in which they can request a container after which they will be taken to an endpoint with a container running WeTTY in their browser.

