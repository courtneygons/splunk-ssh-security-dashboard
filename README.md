# Splunk Cloud SSH Security Dashboard

This project demonstrates SSH login monitoring using **Splunk Cloud** to analyze Linux authentication logs.  
It is designed to showcase SIEM (Security Information and Event Management) fundamentals and real-world log analysis techniques.

## Tools Used
- **Splunk Cloud** (Free Trial)
- **SPL (Search Processing Language)**
- **auth.log** (sample Linux authentication log)
- **macOS** for the local environment

## Features
- Searches for failed SSH login attempts using SPL queries
- Tracks failed login events by time, source IP address, and username
- Visualizes login trends and anomalies through a custom Splunk dashboard
- Demonstrates SIEM functionality, log ingestion, and security event analysis workflows

## Project Contents
- `auth.log` — Sample Linux authentication log file ingested into Splunk
- `spl_query.txt` — SPL queries used for dashboard panels and data analysis
- `dashboard_screenshot.png` — Screenshot of the completed SSH Security Monitoring dashboard
