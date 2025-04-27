# Splunk Cloud SSH Security Dashboard

This project demonstrates SSH login monitoring using **Splunk Cloud** to analyze Linux authentication logs.  
It is designed to showcase SIEM (Security Information and Event Management) fundamentals and real-world log analysis techniques.

## Tools Used

- **Splunk Cloud** (SIEM platform)
- **Search Processing Language (SPL)** for data queries
- **Sample SSH authentication log** (`auth.log`)

## Features

- Searches for failed SSH login attempts using SPL queries
- Tracks failed login events by time, source IP address, and username
- Visualizes login trends and anomalies through a custom Splunk Cloud dashboard
- Demonstrates SIEM functionality, log ingestion, and security event analysis workflows

## Dashboard Preview

![SSH Security Dashboard Screenshot](images/dashboard_screenshot.png)

## Project Contents

- `auth.log` — Contains sample Linux SSH login events for ingestion and analysis
- `spl_query.txt` — Includes SPL queries used to build dashboard visualizations
- `dashboard_screenshot.png` — Shows the final Splunk Cloud SSH Security Monitoring dashboard

## Purpose

This project demonstrates practical cloud-based SIEM skills in monitoring SSH security events, highlighting proactive threat detection and security analytics in Splunk Cloud environments.
