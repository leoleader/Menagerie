---
date: 2023-10-01T10:58:08-04:00
description: "Data Visualization for Electric Racing"
featured_image: "/images/electricracing.jpg"
tags: ["cs"]
title: "Argos for NER"
---

This semester I am excited to announce that I will be working as a Software Engineer for the Data Visualization and Analysis Team for Notheastern Electric Racing! We are going to be working on a few different really cool projects to help our engineers access and understand data from the car so that they can better improve it. 

Currently in development is a project called Argos, essentially a telemetry hub that lets users query any and all data from the car's server, then organizes and presents it in a user-friendly series of charts and figures.

Argos uses Express backend in TypeScript, along with Prisma for easier/more efficient querey building and a SQLite database. Server communication is being done using socket IO, and the front end is using Angular. We initially had the project's frontend in React but early on we discussed the pros/cons of React vs. Angular for this project and decided to go with Angular. Finally we are using ApexCharts for our charting library. 

As the project is continuously developed I will update this article with progress reports :)

