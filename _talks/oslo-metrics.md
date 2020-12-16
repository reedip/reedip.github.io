---
title: "Discover OpenStack's nerve with oslo.metrics: Have a robust private cloud on a large scale"
collection: talks
type: "Talk"
permalink: /talks/oslo-metrics
venue: "Open Infrastructure Summit 2020"
date: 2020-10-27
location: "Virtual"
---
Understanding the scale limitation and identifying the bottleneck are essential to provide a reliable large-scale cloud. The scale of the OpenStack cloud in LINE exceeded 2000+ hypervisors and started facing scalability and performance issues related to RPC. We are monitoring the RabbitMQ, however, even though RabbitMQ is working well, we can not guarantee RPC is working perfectly.

To monitor the RPC in detail, we developed production-ready oslo.metrics which exposes the internal metrics of oslo libraries and integrated it with oslo.messaging. This talk will describe how we collect the internal metrics and what kind of metrics we are collecting, showing the Grafana dashboard which visualizes the metrics from 2000+ hosts of all regions.

We will also demonstrate use cases, such as
* Bottleneck analysis with large-scale hypervisor emulation
* Metrics trend monitoring
* Integration with oslo.db


You can check out the talk at : https://www.youtube.com/watch?v=pNyjMRJViac

