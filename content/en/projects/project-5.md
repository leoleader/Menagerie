---
date: 2022-12-28T10:58:08-04:00
description: "My School Projects so Far"
featured_image: "/images/beans.jpeg"
tags: ["cs"]
title: "Learning OOD with Java"
---

So far in my journey with CS at Northeastern, I have completed a few different projects, a couple being interesting enough that I would like to highlight them here and briefly discuss them. 

The first project I will be talking about is the Marble Solitaire project. For those that don't know, marble solitaire is a simple board game where you try to hop marbles over each other to eliminate them, the goal is to be left with one marble at the end. 
![Marbles](/images/marble.png)

Above is a screenshot of the gui for the program after I played a quick game and lost horrifically (despite spending a month or so in class on this project I never bothered to get better at playing it). It's a barebones design, with the score and game over message at the bottom and obviously the board front and center. This was one of the first programs I ever made, and I think the second GUI so just getting a working GUI was the only thing on my mind while making this project.

This program was the first time I implemented a MVC class structure properly and effectively. I had an abstract class that held the data and methods for a game of marble solitaire, then classes that extended this abstract class for each type of marble solitaire (english, triangle, european). There are two views with their respective classes, a Text View that displays the board and interfaces with the user using the terminal, and a GUI View as seen above, which we used Java Swing to implement. Finally the controller class brings it all together and helps keep the views and models from accessing information that they shouldn't be able to access. This was my first time working with the Java Swing library so it definitely took some time to get used to. This project really made clear to me how important desinging your project with the end product in mind is. As we developed this project, the professors revealed requirements and necessary design changes each couple weeks, and sometimes as I tried to implement these new elements I realized that there were key elements of my base code that I needed to alter or even redesign entirely in order to efficiently integrate the new requirements. Thinking ahead, abstracting, making reusable code, and writing tests before writing code were all big takeaways I had from this project. Here's the [repository](https://github.com/leoleader/marblesolitaire) with the code.

The second project I'd like to look at is the Image Processing Program project. 
![Home Screen](/images/leo_before.png)

Pictured above is the graphical user interface for the program with an image loaded in (say hi to my cat leo). This program allows users to load in an image from their computer and perform a variety of operations on it: brightening, darkening, flipping along with filters for blurring, sharpening, greyscale color transformations, and sepia color transformations. At the bottom is a histogram showing the color values of the image and to the right is the programs messages to the user letting them know if the operations were successful, if there is an error, etc. Once the user is satisfied with their product they simply save it to their computer and exit. The below image was created using this program, specifically the brighten, flip, and sharpen operations.  

![sillycat](/images/leo_after.png)

I found this project really interesting, we started by working with ppm files which are essentially just text files with the RGB values of each pixel, so that we could get a real understanding of what each image operationw was realy doing, and then incorporated the standard image types like png and jpeg. It was really interesting learning about kernels and applying filters and made me interested in learning more about image processing and graphics in the future. Looking back on the project I would have definitely used more efficient data structures for storing pixel information and applying kernels, and would have consolidated my classes for ppm images and file images into one class. Check out the [repository](https://github.com/leoleader/imagesprocess) for a look at the code. 



