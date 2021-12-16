---
layout: project
type: project
image: images/kanak-attack.png
title: Kanak Attack Manoa
permalink: projects/kanak-attack-manoa
# All dates must be YYYY-MM-DD format!
date: 2021-12-16
labels:
- Web Development
- GitHub
summary: 
---

## Project Overview

Kanak Attack is an app designed for the UH Manoa campus. It gives vendors the ability to maintain an active menu, update items, and list the availability of items. The user have the ability to view menu items, vendors, and the menu for each vendor. On top of that, they are also able to read reviews from other users and leave their own. The overall purpose of this app is to display available items around campus so the user can make a decision on what to eat based on their personal taste and availability.

<img class="ui image" src="{{ site.baseurl }}/images/firmware.png">


## My Work

In this project, I was in charge of deployment of our application to Digital Ocean. I also kept our site up to date by redeploying each time. In addition to this, I established a domain name for our application. I also worked on both the admin and vendor home page for our site. This gave the administrator the ability to add a vendor role to a user and manage the system. To do this, I created the vendor role for our application and had to use Meteor methods so that a user can be assigned a role even after initialization of the database. For the vendor home page, vendors were able to add their current profile as well as edit it and change any information about their shop. I also included a page that would list the menu of all the vendors. In managing the different pages that the different roles can access, I worked with the publications and subscriptions to make sure that users could not access certain things and made sure that there were protected routes for all the roles. Since different pages weren't accessed by other roles, I also created different pages and components for multiple roles so that users didn't have edit access to anything and that vendors only had access to their own menu and profile.

## What I Learned 

This project taught me a lot about working as a group and having to come up with our own improvements and solutions in order to make the existing project and algorithm better. It also involved a lot of self-driven work and research, and at some points I did feel lost and stuck and felt like I needed to be given direction. I would say it felt a bit like a job as the professor doesn't set up everything for you or give you instructions on how to do it. Through this team, I was able to learn a lot about the process of creating something from the research to the design, as well as having to plan out a timeline for your team on how and when we would get the job done.

You can learn more at the [Kanak Attack Manoa wepage](https://kanak-attack-manoa.github.io/).
[Github Organization](https://github.com/kanak-attack-manoa)
