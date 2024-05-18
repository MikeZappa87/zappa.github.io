---
layout: post
title:  "[WIP] anycast k8s services"
date:   2024-01-15 12:00:00 -0700
categories: jekyll update
---

NAT is something that shouldn't be dragged into ipv6. We should talk about why NAT was invented and what the path forward without NAT is. A lot changes when you assign the ClusterIP inside the pod network namespace and route to it. 