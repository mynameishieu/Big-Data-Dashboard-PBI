# 🧠 Big Data Monitoring Report

## System stages: `APPLICATION` & `ORBP`
### PRODCUTS: `CLX`, `CCX`, `CCW`, `ACL`, `CD`, `TW`, `BNPL`

This repository contains real-time monitoring dashboards for **Big Data query performance** across multiple systems and data domains. The dashboards are divided into two key systems:

- **APPL** – Application-Level Monitoring  
- **ORBP** – Online-Based Processing Monitoring  

These tools help track, analyze, and ensure the reliability and accuracy of large-scale data operations involving clients, triggers, and third-party data sources.

---
### REPORT DEMO
![demo](Dashboard/BD-dashboard-APPL.gif)
![demo](Dashboard/BD-dashboard-ORBP.gif)
---

## 🎯 Objectives

- Monitor system-level **query health and data hit performance**.
- Track **hit rates, error rates**, and **found percentages**.
- Identify and alert on **unexpected error spikes or query anomalies**.
- Support engineering & data teams with **transparent, visual diagnostics**.
- Enhance the **resilience of data services** through proactive oversight.

---

## 📊 Dashboard Overview

**Key Metrics:**
- `HIT_RATE`
- `CB_FOUND_RATE`, `CACHE_FOUND_RATE`
- `ERROR_RATE`, `ERROR_EXPECTED_RATE`, `ERROR_UNEXPECTED_RATE`

**Visual Components:**
- `% Found-In by Date`
- `NO_FOUND by Seller Channels`
- `HIT_RATE and AVG_OR_SCORE` trends

---

## ✅ Use Cases

- **Daily monitoring** of data retrieval processes.
- **Early detection** of broken data pipelines or low hit scenarios.
- **Optimization** of cache/query architecture.
- Enhanced **collaboration between data, engineering, and operations** teams.

---

> 📁 For further details, refer to individual dashboard modules in `/dashboards`.

