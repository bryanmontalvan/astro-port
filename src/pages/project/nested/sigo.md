---
layout: ../../../layouts/project.astro
title: Should I Go Out? (SIGO)
client: Self
publishDate: 2021-03-04 00:00:00
img: ../../../../public/assets/sigo.png
github: https://github.com/bryanmontalvan/SIGO
description: |
  SIGO for short, a CLI tool which helps user decide if they want to go outside. 
tags:
  - Golang
  - Docker
---
## Description
SIGO was originally created with the intention of learning the lexical structure of GoLang. The program will take in user input and return some basic information such as
- City Inputted
- Temperature
- SIGO
- Note

The **SIGO** part is essentially an algorithm (which is completely biased by my standards of what is good temperature outside) which outputs whether you should go outside or not depending on the temperature.

## Future Goals
Some goals I had for this project was to:
- Create a web-app version
- The SIGO model should take in more parameters (air quality, humidity, UV, etc) to display more accurate 
- Have a feedback feature where users could share whether they agree with the SIGO decision. That way the model could eventually be fine-tuned by the general consensus on what exactly is good or bad weather.



