# 🔐 Splunk SSH Security Dashboard

This project uses Splunk to analyze Linux authentication logs and visualize failed SSH login attempts. It’s designed to demonstrate SIEM (Security Information and Event Management) fundamentals using real-world log data.

## 🧰 Tools Used
- **Splunk Cloud** (Free Trial)
- **SPL** (Search Processing Language)
- **auth.log** (sample Linux log file)
- **macOS** for environment

## 🔍 Features
- Searches for failed SSH login attempts using SPL queries
- Tracks failed login events by time, IP address, and username
- Visualizes trends in a custom Splunk dashboard with multiple panels
- Demonstrates SIEM functionality and log analysis workflow

## 📁 Project Contents
- `auth.log`: Sample log file ingested into Splunk
- `spl_query.txt`: All SPL queries used to generate dashboard insights
- `dashboard_screenshot.png`: Screenshot of final dashboard (optional)
