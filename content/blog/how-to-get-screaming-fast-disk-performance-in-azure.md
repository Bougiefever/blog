---
title: "How to Get Screaming Fast Disk Performance in Azure"
date: 2019-09-25T10:45:21-05:00
tags: ["azure", "storage", "linux"]
draft: false
---

Sometimes, you have the need for speed in your applications hosted in Azure. If you need superior performance, this blog post lays out a good starting point. I'm warning you that this is very costly, so unless money is not a problem, use this as a starting point and scale down until you get the price/performance ratio that works for you. I'll include the price for the different components as of today in the East US 2 Azure region, but please check the prices using the pricing calculator before provisioning so you don't end up with a nasty surprise when the bill comes due. That being said, some of you require very, very fast throughput and network transfer of files, and I can show you how to achieve that. 