---
layout: post
title: 2022 APFS Advent Challenge
---

As an exercise in self-discipline, I've decided to get an early start on my 2023 New Year's resolution of writing more and sharing what research I can with the community.  As a sort of Digital Forensics Advent Calendar, I'm going to attempt to publish a daily series of informative blog posts detailing internals of Apple's APFS file system.

## Why APFS?

I've chosen the topic of APFS for three main reasons:  

1)  APFS has been Apple's file system of choice for all of its devices, including Macs, since 2017, yet most of the resources that are available are somewhat lacking in completeness and correctness.  Even Apple's own [Apple File System Reference](https://developer.apple.com/support/downloads/Apple-File-System-Reference.pdf) document contains several errors and glaring omissions.

2) APFS is a fairly unique file system with many interesting design decisions.  It's also complex enough to justify a 24-part blog series.

3) Over the last five years, I've written three separate APFS parsing implementations, so it's a topic that I am well versed in and qualified to discuss.

## The Rules

All good challenges needs rules in order to keep us honest.  Luckily for me, I'm challenging myself to this task, so I get to set the requirements.

1) **I will publish a short blog post ~~every day between December 1st and 24th~~ every weekday in December.**  While I am aware that the Christian season of Advent technically starts on November 27th and ends on Christmas, I am not doing this as a part of any religious observance and most modern Advent calendars start on December 1st anyway.  Besides, I only just had this idea and haven't had time to plan out my topics.

2) **As long as it's before the clock strikes midnight on a given day *somewhere* on the planet Earth, it counts.**  Since I will have to limit myself to writing after work hours and teaching my night classes, I am not limiting myself to my own timezone.  This challenge is supposed to be rewarding, not stressful.

3) **For each failed deadline, I will donate $100 to a Ukrainian relief fund.**  As a result of the unprovoked war of aggression and the continued occupation of Ukraine, the people of Ukraine are suffering loss at a massive scale. The intentional targeting and destruction of Ukrainian civilian infrastructure and power generation capabilities as winter sets in has only increased the suffering of the civilian population.  For each day that I do not meet my self imposed deadline of publishing, I will donate additional money towards humanitarian relief for the people of Ukraine.  If I do meet my publishing goals (or even if I don't), and it is within your means, I would ask that you too consider making your own donation this holiday season.  

## The Posts

- [Day 1 - Anatomy of An APFS Object](/post/2022/12/01/Anatomy-of-an-APFS-Object)
- [Day 2 - Kinds of APFS Objects](/post/2022/12/02/Kinds-of-APFS-Objects)
- [Day 3 - APFS Containers](/post/2022/12/05/APFS-Containers)
- [Day 4 - NX Superblock Objects](/post/2022/12/06/APFS-NX-Superblock)