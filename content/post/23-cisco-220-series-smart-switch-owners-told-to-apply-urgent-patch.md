---
title: "Cisco 220 Series Smart Switch Owners Told to Apply Urgent Patch"
date: 2019-08-09T08:12:19+05:30
draft: false
image: "uploads/cisco.png"
tags: ["Security10x News"]
---

Multiple vulnerabilities in the web management interface of Cisco Small Business 220 Series Smart Switches could allow an unauthenticated, remote attacker to overflow a buffer, which then allows the execution of arbitrary code with root privileges on the underlying operating system.

The vulnerabilities are due to insufficient validation of user-supplied input and improper boundary checks when reading data into an internal buffer. An attacker could exploit these vulnerabilities by sending malicious requests to the web management interface of an affected device. Depending on the configuration of the affected switch, the malicious requests must be sent via HTTP or HTTPS.

Read the full story on **[Cisco](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20190806-sb220-rce)**.