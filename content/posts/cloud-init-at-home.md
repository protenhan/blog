---
title: "Cloud Init at Home – Automating my Raspberry Pi Setup"
date: 2018-01-01T23:33:11+01:00
draft: true
authors: ["protenhan"]
tags:
  - raspi
  - docker
  - cloud
---

I have been playing around with a total of 3 Raspberry Pis for some years. Two of them are running software related to my home audio streaming and I just touch them for updating the base OS or the software running on them. The third one is for my personal software experiments and is more or less regularly reinstalled because I want to play with a different OS or I messed up my Docker installation. 
Luckily I stumbled across [this blog article](https://blog.hypriot.com/post/cloud-init-cloud-on-hypriot-x64/) of the hypriot guys that sounded like fun and also that it would solve some of my problems.

### Setup
Since I'm using [hypriotOS](https://blog.hypriot.com/downloads/) for my raspberries anyway, there was actually not that much to do. This is because hypriotOS already ships with the cloud-init packages pre-installed. For other OSes, like Raspbian, I do not know how this will work.