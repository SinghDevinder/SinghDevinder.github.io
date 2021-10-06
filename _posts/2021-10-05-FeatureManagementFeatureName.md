---
layout: post
title: "Feature Management : Feature Name is blank/ not populated / not showing up on the user interface of Dynamics 365 Finance and operations"
sitemap:
    priority: 0.7
    changefreq: 'monthly'
    lastmod: 2021-10-05T12:49:30-05:00
---

**Issue** : If you are not able to see Feature Names on Feature Management Workspace
**Resolution** : Execute the batch job "Runs Feature Translation population".   I have not explored what exactly it does but seems to be populating the labels (Feature Name) based on the Language settings.
