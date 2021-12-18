---
layout: project
type: project
image: images/food.png
title: Kanak Attack Manoa
permalink: projects/kanak-attack-manoa
# All dates must be YYYY-MM-DD format!
date: 2021-12-16
labels:
- Web Development
- GitHub
summary: Kanak Attack Manoa is an application that gives users the chance to view vendors available on campus and make a choice that best fits their budget and taste.
---

## Project Overview

Kanak Attack is an app designed for the UH Manoa campus. It gives vendors the ability to maintain an active menu, update items, and list the availability of items. The user have the ability to view menu items, vendors, and the menu for each vendor. On top of that, they are also able to read reviews from other users and leave their own. The overall purpose of this app is to display available items around campus so the user can make a decision on what to eat based on their personal taste and availability.

<img class="ui image" src="{{ site.baseurl }}/images/kanak-attack.png">

## My Work

In this project, I was in charge of deployment of our application to Digital Ocean. I also kept our site up to date by redeploying each time. In addition to this, I established a domain name for our application. I also worked on both the admin and vendor home page for our site. This gave the administrator the ability to add a vendor role to a user and manage the system. To do this, I created the vendor role for our application and had to use Meteor methods so that a user can be assigned a role even after initialization of the database. For the vendor home page, vendors were able to add their current profile as well as edit it and change any information about their shop. I also included a page that would list the menu of all the vendors. In managing the different pages that the different roles can access, I worked with the publications and subscriptions to make sure that users could not access certain things and made sure that there were protected routes for all the roles. Since different pages weren't accessed by other roles, I also created different pages and components for multiple roles so that users didn't have edit access to anything and that vendors only had access to their own menu and profile.

Here are a couple pages mentioned that I implemented:
<img class="ui image" src="{{ site.baseurl }}/images/admin-home.png">
<img class="ui image" src="{{ site.baseurl }}/images/vendor-home.png">

## What I Learned 

This project taught me a lot about working as a group and having to come up with our own design choices and utilizing what we learned about web application development. I also learned a lot about working in a team, trusting your teammates, and communicating with them to get the work done. Through this team, I was able to learn a lot about the process of creating something from your own ideas and through what was learned during the course of the semester, as well as having to plan out a timeline for your team on how and when we would get the job done.

You can learn more at the [Kanak Attack Manoa page](https://kanak-attack-manoa.github.io/).

[Github Organization](https://github.com/kanak-attack-manoa)
