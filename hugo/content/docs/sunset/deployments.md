---
title: Deployments
description: Deployment options to be removed on Janury 1st, 2020 .
date: 2019-08-07T13:00:00.000+00:00
publishdate: 2019-06-30T13:00:00.000+00:00
expirydate: 2020-03-01T22:00:00.000+00:00
authors:
- team forestry
headline: ''
textline: ''
images: []
categories: []
tags: []
cta:
  headline: ''
  textline: ''
  calls_to_action: []
weight: ''
aliases: []
layout: ''
menu:
  sunset:
    weight: 1
    parent: Sunset Notices

---
Starting today, we will be removing support for deployments (FTP, GitHub Pages, Amazon S3) on all newly created sites.

Deployments will work for existing sites but we encouraged those people to move to other best-of-breed deployment services like [Netlify](https://netlify.com) or [Circle CI](https://circleci.com).

Why this change? Only a small percentage of our users make use of Forestry deployments. For those users, we spend a lot of effort ensuring build and deployments work. We prefer to focus on our core features like content modelling and the editing experience. Plus, services like [Netlify](https://netlify.com), [Circle CI](https://circleci.com), and [Zeit](https://zeit.co/) are doing a far better job of deployment and we think our users will be better off using those services.   
  
Even if the current option has served you well until now, we think it's a smart move for everyone.

**We will be sunsetting deployments on January 1st, 2020**

[Continuous deployment with Netlify](https://www.netlify.com/docs/continuous-deployment/)

[How to automate your deployments with Circle CI](https://forestry.io/blog/automate-deploy-w-circle-ci/)

[Introduction to Zeit Now](https://zeit.co/docs/v2/introduction/)