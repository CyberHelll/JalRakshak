# JalRakshak 💧

### Community Water Safety & Early Warning Platform

JalRakshak is an offline-ready community platform designed to help residents report unsafe water conditions and early illness signals while helping authorities monitor reports and respond faster.

## Problem

Information about unsafe water, illness symptoms, and water-quality issues can be scattered across different sources. JalRakshak brings these signals together so potential problems can be identified and acted upon earlier.

## Features

* Water issue reporting
* Illness reporting
* Water-quality reporting
* GPS location capture
* Voice input
* Multilingual interface
* Risk-level assessment
* Admin dashboard
* Inspection reporting
* Emergency information
* Offline-ready Progressive Web App

## Technology

* HTML
* CSS
* JavaScript
* Supabase
* PostgreSQL
* Browser Geolocation API
* Browser Speech Recognition API
* Service Worker
* Local Storage

## Basic Architecture

```text
User
  ↓
JalRakshak Web App
  ↓
Local Storage / Supabase
  ↓
Reports Database
  ↓
Risk Assessment
  ↓
Admin Dashboard
  ↓
Inspection / Response
```

## Risk Assessment

The current prototype uses a transparent rule-based scoring approach. It considers reported conditions and other available signals to assign a risk level.

The current system is a prototype and does not provide medical diagnosis.

## Offline Support

The application uses a service worker to cache important application resources and support use when connectivity is limited.

## Data & Privacy

The application is designed to collect only information needed for reporting and response. A production deployment would require stronger authentication, authorization, data protection, and privacy controls.

## Current Status

This repository contains the prototype version of JalRakshak.

## Future Improvements

* Secure role-based authentication
* Verified government accounts
* Reliable background synchronization
* SMS/WhatsApp alert integration
* Water-quality sensor integration
* Health-worker and hospital integration
* Rainfall and flooding data
* District-level visualization
* Machine-learning-based risk modelling using verified historical data

## Disclaimer

JalRakshak is a prototype intended for demonstration purposes. It is not a medical diagnostic system, and risk indicators should be verified by qualified health and water authorities before official action.
