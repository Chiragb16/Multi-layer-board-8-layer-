# HoneyGuard

<div align="center">

<img src="boared.jpeg" alt="HoneyGuard PCB" width="700"/>

### AI-Powered Beehive Monitoring & Honey Purity Detection Platform

Protecting Indian beekeepers from honey adulteration while enabling data-driven hive management.

</div>

---

## Overview

HoneyGuard is a production-grade beehive intelligence platform designed to combat honey adulteration and improve hive productivity through real-time monitoring.

The system integrates honey purity detection, hive health analytics, environmental sensing, and long-term data logging into a compact **90mm × 90mm 8-layer PCB** built around the **nRF52840**.

HoneyGuard addresses an estimated **₹2000 crore annual loss** caused by honey adulteration while helping beekeepers maximize yield and maintain healthy colonies.

---

## Key Features

### Honey Purity Detection

HoneyGuard combines gas sensing and spectral analysis to identify common adulterants directly at the hive.

- BME688 VOC Gas Sensor
- AS7341 11-Channel Spectral Sensor
- Detection of:
  - Rice Syrup
  - High Fructose Corn Syrup (HFCS)
  - Cane Sugar Adulteration
- Frame-level purity analysis
- Up to **97% agreement with laboratory HPLC testing**

---

### Hive Health Monitoring

Real-time monitoring of critical hive parameters:

#### Environmental Monitoring
- SHT30 Temperature Sensor
- SHT30 Humidity Sensor
- Brood-condition optimization

#### Acoustic Monitoring
- MEMS Microphone
- Varroa mite activity detection
- Swarming pattern analysis

#### Weight Monitoring
- HX711 Load Cell Interface
- Hive weight tracking
- Honey yield prediction

#### Data Logging
- MicroSD Card Storage
- 7-Day Local Data Buffer
- Offline operation support

---

## Real-Time Dashboard

The integrated 0.96" OLED display provides:

- Honey Purity Score
- Hive Weight Delta
- Temperature
- Humidity
- Disease Alerts
- Sensor Status
- Battery Information

---

## Hardware Architecture

### Processing & Connectivity

| Component | Function |
|------------|------------|
| nRF52840 | Main MCU |
| BLE 5.4 | Wireless Connectivity |
| QSPI Flash | Extended Storage |
| OLED Display | Local Interface |
| MicroSD | Data Logging |

---

### Sensors

| Sensor | Purpose |
|----------|----------|
| BME688 | VOC-Based Purity Detection |
| AS7341 | Spectral Analysis |
| SHT30 | Temperature & Humidity |
| MEMS Microphone | Acoustic Analysis |
| HX711 + Load Cell | Weight Monitoring |

---

## PCB Specifications

| Parameter | Value |
|------------|---------|
| Board Size | 90mm × 90mm |
| Layers | 8 |
| MCU | nRF52840 |
| Communication | BLE 5.4 |
| Battery Life | 6+ Months |
| Storage | QSPI Flash + MicroSD |

---

## Applications

- Commercial Beekeeping
- Honey Authentication
- Hive Health Monitoring
- Yield Prediction
- Disease Detection
- Smart Agriculture
- Research & Analytics

---

## Impact

HoneyGuard enables:

- Early detection of honey adulteration
- Improved hive health management
- Reduced colony losses
- Better harvest forecasting
- Premium pricing for genuine honey
- Scalable digital beekeeping infrastructure

---

## Mission

Enable premium pricing for genuine multiflora honey while providing predictive hive management through scalable beekeeping intelligence.

HoneyGuard bridges the gap between traditional beekeeping and modern sensing technology, helping beekeepers improve profitability while preserving honey quality.

---

## Technology Stack

- KiCad
- nRF52840
- BLE 5.4
- BME688
- AS7341
- SHT30
- HX711
- MicroSD
- Embedded C
- Nordic SDK

---

## Project Status

Current Stage: Prototype Validation & Field Testing
