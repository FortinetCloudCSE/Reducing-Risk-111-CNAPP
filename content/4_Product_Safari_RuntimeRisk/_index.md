---
title: "Lab 4 - Intro to FortiCNAPP: Runtime Risk"
linkTitle: "4. Safari Lab (Runtime Risk)"
weight: 1
#archetype: "chapter"
---

## Lab Overview

The goal of this lab is to get you hands on in the product interface with FortiCNAPP's Runtime Risk offerings (Vulnerability Management, *SPM, and CIEM). Your instructor will guide you through the product interface and inline challenges as you go collectively. Please feel encouraged to ask questions and interject as you progress (or ignore your instructor completely and click around -- just learn something!).

## Tools / Access

Accounts for FortiCNAPP will be handed out as part of the course. If you are doing this asynchronously from a live event, please reach out to either [Adam](mailto:alarson@fortinet.com) or [Gabe](mailto:gobrien@fortinet.com) to gain appropriate credentials:

0. **Pre-requisite:** Log into [FortiCNAPP Console](https://gameday.lacework.net/)
**When logging into the FortiCNAPP console, you will use ONLY the user ID you were provided (i.e. NOT using the '@corpldap.com' postpend).**

## Introduction to Runtime Risk's Vulnerability Management (Vuln) interface

This section will help you understand how FortiCNAPP can identify CVEs in your third-party dependencies and system libraries.

1. Navigate to the Vulnerabilities page: On the left-hand navigation go to "Findings -> Vulnerabilities". 

{{< figure src="imgs/lab4-vuln-nav.png" >}}

2. **Pause here and the instructor will walk you through the interface to orient you!**

## Introduction to Runtime Risk's Cloud Security Posture Management (CSPM) interface

This section will help you understand how FortiCNAPP can help scan your cloud infrascture configurations at runtime to identify deviations from accepted best practices.

1. Navigate to Compliance page: On the left-hand navigation go to "Findings -> (Compliance) Cloud".

{{< figure src="imgs/lab4-cspm-nav.png" >}}

2. **Pause here and the instructor will walk you through the interface to orient you!**

## Introduction to Runtime Risk's Cloud Identity Entitlement Managmeent (CIEM) interface

This section will help you understand how FortiCNAPP can do full audits of all of your cloud identities to find overprovisioned identities that add broad risk if compromised.

1. Navigate to the CIEM page: On the left-hand navigation go to "Findings -> Identities".

{{< figure src="imgs/lab4-ciem-nav.png" >}}

2. **Pause here and the instructor will walk you through the interface to orient you!**

## Mini Challenge

Identify which of the aforementioned tools would be used for the following scenarios:

1. Find EC2 instances that are exposed to the public internet.
2. Find places that I am susceptible to the Log4Shell CVE.
3. Find places that my S3 buckets are not properly encrypted.
4. Find places that my EC2 instances have unused entitlements.
5. Find places that internet exposed CVEs could expose admin IAM roles.