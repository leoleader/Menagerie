---
date: 2023-08-01T10:58:08-04:00
description: "A Web App for Making and Taking Quizzes"
featured_image: "/images/bg_sherry.webp"
tags: ["cs"]
title: "Sherry's Quizzes"
---

Sherry's Quizzes is a quiz taking/building web app that I developed, check it out at https://sherrysquizzes-6d15ee4bcb35.herokuapp.com ! Sherry is built in Python with Django as the backend, SQLite database and HTML/CSS as the frontend, hosted on Heroku. 

NOTE: I realized on deployment that Django/Heroku is lowkey lame when it comes to serving static files so currently user uploaded images are not displaying until I set up a custom file storage backend w a CDN.

 My friends and I love taking quizzes and asking each other questions to either get to know each other better or challenge each other's knowledge of various topics, so I decided to make a web app so we would have a place to make whatever quizzes we wanted and send them to each other. While there are definitely websites out there that already do this kind of thing (I'm looking at you uquiz), I figured this would be a good starter project to do to get experience with web development. 

Locally home page looks like this:
![sherry](/images/sherryhome.png)

Users coming to the site for the first time can play any of the featured quizzes on the homepage or can search for quizzes to play using the search bar at the top. If they want to, they can sign up for an account and once they are validated and signed in, make quizzes of their own. There are two types of quizzes, knowledge and personality quizzes, and both types of quizzes can be made using the quiz builder. Users can view the quizzes they've made and edit them under the profile tab, selecting My Quizzes.

Future functionality I plan on adding:
- Ways to sort and filter available quizzes
- Fleshed out profile page
- UI Aesthetic Updates
- Comment system for leaving reviews on quizzes
- Social buttons for easy sharing

You can check out the repo at https://github.com/leoleader/sherry, or better yet, check out the site itself!