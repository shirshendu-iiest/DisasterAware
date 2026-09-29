# DisasterAware

### AI-Powered Multi-Hazard Disaster Monitoring & Early Warning System

**DisasterAware** is a distributed environmental intelligence system developed
for **Smart India Hackathon 2026**.

The system combines distributed IoT sensor nodes, LoRa communication,
AI/ML-based hazard analysis and a mobile application to detect environmental
risks, generate early warnings and assist evacuation.

---

## Problem

Natural disasters such as floods, landslides, forest fires and severe
environmental pollution require continuous monitoring across large and
vulnerable geographical areas.

Traditional monitoring systems may depend heavily on centralized
infrastructure and often focus on individual hazards.

DisasterAware proposes a distributed and scalable multi-hazard monitoring
network.

---

## Proposed Solution

Multiple intelligent sensor nodes are deployed across vulnerable regions.

Each node:

- Collects environmental sensor data
- Performs local hazard-risk analysis
- Communicates using LoRa
- Relays data through intermediate nodes
- Sends important information to a monitoring station

The monitoring station combines data from multiple nodes to analyze risk
across a larger geographical area.

A mobile application is used to provide:

- Real-time disaster warnings
- Hazard visualization
- Location-based alerts
- Evacuation guidance
- Safe-zone information

---

## Hazards Covered

##  Flood
Monitoring of water level, rainfall, soil moisture and environmental conditions.

## Landslide
Monitoring of soil moisture, tilt, terrain movement, rainfall and related parameters.

## Fire & Smoke
Monitoring of temperature, humidity, particulate matter, gases and flame activity.

## Pollution
Monitoring of particulate matter, gases, temperature and environmental quality.

---
### More information

## Technologies
ESP32, LoRA commmunication, IoT sensors, Android Application, AI/ML, Gps, Disaster Risk Management.

---

## Mobile APP
A dedicated mobile application is being developed for DisasterAware.


## Repository Rodmap

DisasterAware/
│
├── app/           # Android application
├── firmware/      # ESP32 and LoRa firmware
├── ai-ml/         # Disaster prediction models
├── simulations/   # Hazard simulations
├── hardware/      # Circuit and node designs
├── docs/          # Project documentation
└── assets/        # Screenshots and prototype images



## System Architecture

```text
Environmental Sensors
        │
        ▼
Intelligent Sensor Node
        │
   Local AI/ML
        │
        ▼
      LoRa
        │
        ▼
Intermediate Nodes
        │
        ▼
Monitoring Station
        │
        ▼
Risk Analysis
        │
     ┌──┴──┐
     ▼     ▼
 Alerts   Mobile App
            │
            ▼
   Evacuation Guidance
