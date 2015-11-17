---
layout: post
title:  "Major change in conception for the framework"
date:   2015-09-01 16:00
categories: blog
---

After several try of conceptions (workflow managers such as Airflow or home-made
solution), we have decided to choose Galaxy as the base for the framework. Galaxy
workflow conception relies on dependencies between inputs and outputs. This model 
of data flow is better for meta-omics data processing than dependencies between
the tasks (as proposed by the majority of workflow managers).