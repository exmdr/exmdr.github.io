---
layout: post
title:  "Sentinel-Log-Ingestion-Resiliency"
author: don
categories: [ sentinel ]
image: assets/images/australia2019/island.jpg
featured: true
hidden: true
---

Often time, we are hearing from our client on topic vis-a-vis know-how addressing security log ingestion capable of sustaining intermittent or periodic network connectivity failure.

This case study focus on the resiliency features of the two native software agents purpose-built to handle ingestion of the security logs from on-premises operating systems to Microsoft Sentinel, which attesting the sustainability in term of retry mechanism during temporary or prolong network connectivity downtime.

### The test kits
> The eco-friendly way, a nano box was powered-on alongsides 6-month Windows Server 2019 Server with hyper-v activated and powered-on Ubuntu Server 22.04.4 LTS. This test aimed to survive target 3 to 7 days long 24x7 uptime.
 
The two main operating systems were tested below.

1. Windows Server 2019
2. Ubuntu Server

![walking](/assets/images/australia2019/island.jpg)
