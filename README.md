# Automated Threat Ingestion Pipeline for Financial Gateways
## Project Overview
This project establishes an automated cybersecurity data pipeline designed to ingest, transport, and analyze critical security events from a simulated financial application. Using Python automation, raw application logs are securely streamed over an API to Sumo Logic Cloud SIEM for real-time visibility and threat analysis.
## Core Features
* **Automated Telemetry Transport:** Built a custom Python script using the `requests` library to securely forward logs over an HTTPS webhook.
* **Cloud SIEM Integration:** Configured a hosted live cloud collector in Sumo Logic to index incoming streams.* **Threat Visibility:** Simulates a localized credential-stuffing/brute-force attack scenario against authentication endpoints (`/api/v1/auth/login`).
## Architecture Highlights
* **Log Generator:** Google Colab (Python 3)
* **SIEM Platform:** Sumo Logic Cloud Analytics
* **Protocol:** HTTPS POST Webhook API
