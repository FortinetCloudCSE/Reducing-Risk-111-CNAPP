---
title: "Lab 4 - Web Security"
linkTitle: "Lab 4 - Web Security"
weight: 4
#archetype: "chapter"
---

## Lab overview
In this lab you will try manipulate a web application to access a flag on the root file system. Hidden with in the website is an hacker interface that can be used to run arbitrary commands.

The goal of this lab is to gain some understanding of how easy it can be to use a weakness in an web application to gain unauthorized access.

## Access the Battle web site

Click on the link below and checkout the 'Battle' website.

http://battle.corpldap.net

{{< figure src="imgs/battle.png" >}}

There are some clues hidden in the site that should help you along.

## Don't just click around

View the website, but do not get caught in the battle over the banner color. Poke around and see if you can find any hints on how to access other parts of the site.

The application backed is written in Python and the web interface uses Flask and JQeury.

Recall your goal is to:
* discover this hidden hacker interface
* find the hidden flag file on the root file system
* read the flag file to reveal the contents

Happy hacking!