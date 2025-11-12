A lightweight, real-time, privacy-friendly website analytics system built entirely using Firebase Firestore, JavaScript, and HTML/CSS — without using Google Analytics or third-party tools.

This project tracks and visualizes how users interact with a website, providing deep insights such as:

### Real-time event tracking

### Time-on-page analytics

### Scroll-depth tracking

### Button-click tracking

### Hover interactions

### Engagement metrics

### Session flow & funnel tracking

### Dynamic charts and dashboards

### CSV Export for all data

Designed for frontend developers, students, projects, and small websites needing custom analytics without sending data to external services.

### Features
1. Real-Time Event Tracking

Tracks every event such as:

page visits

button clicks

scroll activity

hover events

timestamps & session IDs

All events are instantly stored in Firestore.

2. Dynamic Dashboard

A beautiful, responsive analytics dashboard with:

Bar charts

Pie charts

Session overview

Page-wise analytics

Button click distribution

Funnel visualization

Charts are generated using Chart.js.

3. Engagement Metrics

Automatically calculates:

Bounce rate

Average session duration

Pages per session

Engaged sessions

Total events per user

All metrics are fetched from the “events” collection and displayed inside stat cards.

4. Session Flow & Funnel Tracking

A step-by-step funnel to understand user navigation:

Landing page

Product page

Add-to-cart

Checkout

Success

Helps measure drop-off points.

5. CSV Export

Download analytics data in a single click as:

events.csv
sessions.csv
button_clicks.csv


Useful for presentations and external reports.

6. Firebase Integration

Powered using:

Firebase Firestore

Firebase Hosting (optional)

Real-time queries

Fully modular and scalable for any website.

🛠️ Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript, Chart.js
Backend	Firebase Firestore
Hosting	GitHub Pages / Firebase Hosting
Tools	Webpack (optional), Git
Version Control	GitHub

# Project Structure
/analytics-tracker
    /js
        analytics.js
        dashboard.js
    /css
        style.css
    dashboard.html
    index.html
    firebase-config.js
    README.md

# How It Works

Each visitor is assigned a unique session ID

Every event (scroll, click, hover, time-on-page) is captured

Data is pushed to Firestore in real time

Dashboard pulls data using queries

Charts + metrics update automatically

# Live Demo

👉 Insert your GitHub Pages Link here
(: https://palosubhasis-11.github.io/Website-analytics-tracker/
)

🎯 Project Goal

To build a complete, production-ready custom analytics platform from scratch — useful for learning:

Firebase

Data visualization

Event handling

Dashboard development

Real-world website analytics concepts
