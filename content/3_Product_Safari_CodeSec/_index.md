---
title: "Lab 3 - Intro to FortiCNAPP: Code Security"
linkTitle: "3. Safari Lab (CodeSec)"
weight: 1
#archetype: "chapter"
---

## Lab Overview

The goal of this lab is to get you hands on in the product interface with FortiCNAPP's Code Security offerings (SAST, SCA, and IaCS). Your instructor will guide you through the product interface and inline challenges as you go collectively. Please feel encouraged to ask questions and interject as you progress (or ignore your instructor completely and click around -- just learn something!).

## Tools / Access

Accounts for FortiCNAPP will be handed out as part of the course. If you are doing this asynchronously from a live event, please reach out to either [Adam](mailto:alarson@fortinet.com) or [Gabe](mailto:gobrien@fortinet.com) to gain appropriate credentials:

**Pre-requisite:** Log into [FortiCNAPP Console](https://gameday.lacework.net/)
**When logging into the FortiCNAPP console, you will use ONLY the user ID you were provided (i.e. NOT using the '@corpldap.com' postpend).**

## Introduction to Code Security's Infrastructure as Code Security (IaCS)

This section will help you understand how FortiCNAPP can protect your IaC files (e.g. Terraform, CloudFormation, Kubernetes, Docker, etc). 

1. Navigate to Code Security's IaC page: On the left-hand navigation go to "Findings -> Infrastructure (IaC)". 

{{< figure src="imgs/lab3-iac-nav.png" >}}

2. **Pause here and the instructor will walk you through the interface to orient you!**

## Introduction to Code Security's Software Composition Analysis (SCA)

This section will help you understand how FortiCNAPP can help scan your application dependencies for known vulnerabilities (CVEs). 

1. Navigate to Code Security's SCA page: On the left-hand navigation go to "Findings -> Application" and then ensure the top nav's 'Vulnerabilities: 3rd Party' is selected.  

{{< figure src="imgs/lab3-sca-nav.png" >}}

2. **Pause here and the instructor will walk you through the interface to orient you!**

## Introduction to Code Security's Static Application Security Testing (SAST)

This section will help you understand how FortiCNAPP can do full audits of your application logic including looking for known worst practices and exposed secrets.

1. Navigate to Code Security's SAST page: On the left-hand navigation go to "Findings -> Application" and ensure the top nav's 'Vulnerabilities: Internal Code' is selected. 

{{< figure src="imgs/lab3-sast-nav.png" >}}

2. **Pause here and the instructor will walk you through the interface to orient you!**

## Mini Challenge

Identify which of the aforementioned tools would be used for the following scenarios:

1. Find any mistakes in my EC2 configurations.
2. Verify that I am not susceptible to PHP2Shell.
3. Find out whether or not Claude code is properly sanitizing User input? 
4. Discover if I checked in my AWS IAM Secret Key?