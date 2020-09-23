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

## Basic Concepts

![](images/Screenshot%202020-06-30%20at%203.33.55%20PM.png)

- All data is stored as a time series
- Every time series is identified by metric name and labels (key value pairs)
- The time series data also consists of samples which can be float64 or ms time stamp
- Notation: `<metric-name>{<key>=<value>, <key2>=<value2>,...}`
- GQL used




