---
title: "WSLSnappy"
summary: I have built a software written in go to create 𝐟𝐚𝐬𝐭, 𝐫𝐨𝐛𝐮𝐬𝐭, and 𝐩𝐚𝐫𝐚𝐥𝐥𝐞𝐥 backups of your WSL instances.
date: 2024-02-07
aliases: ["/wslsnappy"]
tags: ["Open-Source", "Tools", "WSL"]
author: ["Andrea Raponi"]
draft: false
aliases: [/open-source/wslsnappy]
weight: 1
---

  
![Microsoft loves Linux](/imgs/Microsoft-loves-Linux-300x168.png#center)



Those who know me are well aware that my **preferred operating system is Linux**, but ever since we fully switched to Microsoft in the company, I found myself (once again) having to use **WSL** (which I have discussed on several occasions and in various talks).

Regarding **WSL**, after **months of intensive use** both as a Developer and DevOps, I can only **reaffirm my initial impressions**: Microsoft has done a great job.

The sore point remains the **backup issue**, which is currently only possible through CLI and in a synchronous manner.

From this consideration was born the need to develop **WSLSnappy**, a tool capable of **safely and quickly backing up one or more WSL instances**!

I used **Go** and the **power of goroutines**, and it was really fun.

I’m beginning to implement the logic to **encrypt these backups** and send them to our preferred cloud.

For now, I recommend reading the documentation on [my repository](https://github.com/andrearaponi/wslSnappy) to understand how to use it. 🙂

I’ll keep you updated!

