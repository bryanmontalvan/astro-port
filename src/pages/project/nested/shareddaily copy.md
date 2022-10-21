---
layout: ../../../layouts/project.astro
title: SharedDaily
client: Self
publishDate: 2021-03-04 00:00:00
img: /assets/shareddaily.png
github: https://github.com/bryanmontalvan/shareddaily
deployment: https://shareddaily.herokuapp.com/
description: |
  Built a website for users to share to their daily-drivers along with browsing other cars
tags:
  - React
  - Redis-OM
  - Redis
  - AWS
---
## Description
A website with the purpose for users to share the cars they drive. 

The website is composed of using a Redis database hosted on an AWS instance. Using the [node-redis-objectmapper](https://github.com/redis/redis-om-node) which allows me to use a schema-like interface to interact with the data structures on the data-base. Essentially allowing me to interact with the data-base using an object dubbed schema.

The website itself has two sections:
1. Submission Form
2. Display field

On submit the submission form will update the database with a new car-object. This car object contains meta-data of the car. The display field will fetch the car-objects from Redis. There is also a search component which uses Redis's elastic-search for users to search by car make, model, and usernames.



