---
layout: project
type: project
image: images/battleshiptitle.png
title: Battleship
permalink: projects/battleship
# All dates must be YYYY-MM-DD format!
date: 2020-09-04
labels:
  - Java
  - GitHub
  - GameDev
summary: A battleship game my friends and I built in high school.
---

<div class="ui large rounded images">
  <img class="ui image" src="../images/battleshiptitle.png">
  <img class="ui image" src="../images/battleshipboard.png">
  <img class="ui image" src="../images/battleshipgui.png">
</div>

This was me and 3 other friends AP Computer Science final project. We worked together as a team to create a functioning battleship game that ran over a server. My part of the project was developing the user interface, which included custom graphics for the ships. We used default images for the background on the title screen and the ocean (which did not load in the picture, gonna have to look into that) because we ran low on time. We created this over the course of 3 weeks. Getting a functional game was a great technical challenge for us, as none of us had any experience with using the tools we were using. We learned on the fly, using github to share code bits and discord to communicate while we worked. 

Developing the user interface proved to be a challenge, as getting it to work with a server on a loop required setting up a way to check if an object had updated. We did this with a while loop in the server that would detect that one of the clients had finished making their move. The UI also used custom assets which I digitally modeled and rendered from a top down view.
