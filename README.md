# Prometheus-Grafana

Based on this [Udemy course](https://www.udemy.com/course/monitoring-and-alerting-with-prometheus)

## Prometheus Overview
- Prometheus uses a dimensional data model
- A set of labels identifies the metric 

Metric Name (Dimension) | Label | Sample
--- | --- |---
Temperature |location=outside | 90

- Prometheus includes a flexible query language
- The metrics are stored in memory and local disk in its own efficient format
- It is written in Go

## How does Prometheus work?
![](images/Screenshot%202020-06-30%20at%201.18.56%20PM.png)
- Prometheus collects metrics from monitored targets by scraping metrics HTTP endpoints

## Simple Installation Instructions on a Docker Container
- `docker run -t -i ubuntu /bin/bash`
- 




