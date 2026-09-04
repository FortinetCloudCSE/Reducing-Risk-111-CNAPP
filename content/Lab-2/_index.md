---
title: "Lab 2 - Code Security"
linkTitle: "Lab 2 - Code Security"
weight: 2
#archetype: "chapter"
---

## Lab overview
In this lab you will review a small Node web application and asses it for security issues. The example code-base is a trivially simple web application.

The point of this exercise is to gain some insight into the 'code to cloud' movement. That basic idea is that many security issues start as code well before they become live risks in your cloud account. The easiest (read cheapest) time to address issues (security or other) is as the code is being written. Once code is deployed it become harder to resolve issues and make improvements.

## Download the code

Click the link below to download the zip file of the code you will be reviewing.

[Download Node Code](imgs/hello-world.zip)

Once the file download is completed unzip the file.

** (optionally I can add a link to GitHub where they can review in their browser?) **

## Put on your security professional hat

Let's get started looking over the code to see what security issues you can find.

{{< figure src="imgs/hello-world-files.png" >}}

Open up the files and inspect the code to see what security issue you might be able to spot.

Takes notes so we can discuss your finding after the lab.

## Some pointers of where to look

Always read the README.md file! I mean it can't hurt. It helps ground what the project is and might have other detials

** DO WE PUT AN EASTER EGG IN THE README? **

This web application is written in Node. The entry point into the program can be found in the 'index.js' file.   This, after the README, would be a good place to start to see how the app is setup.

In Node projects the 'package.json' file is where any 3rd party dependencies are defined. Dig into that files what other code this project is pulling in.

Finally take a look at the 'terraform' directory. Terraform is a application that can manage cloud resouces as if it was code.  Almost anything you can do from the AWS/GPC/Azure console you replicate as Terraform code.

## Happy hunting!

Start reviewing the code and take notes!  Feel free to look things up, ask questions or run any tools you might have.