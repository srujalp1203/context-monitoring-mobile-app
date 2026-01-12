# Context Monitoring Mobile Application (Android)

This repository documents the design, architecture, and validation of an Android-based context monitoring application developed as part of a graduate-level mobile computing course.

The application monitors heart rate and respiratory rate using smartphone sensors and allows users to log subjective symptoms. All measurements are stored locally and visualized through a multi-screen mobile interface.

> **Note**  
> This repository contains documentation, architecture diagrams, and visual artifacts only. Source code, datasets, and sensor calibration logic are intentionally omitted to comply with academic integrity and privacy guidelines.

---

## Project Overview

The Context Monitoring Mobile Application enables:

- Heart rate estimation using camera-based video input
- Respiratory rate estimation using accelerometer signals
- Symptom self-reporting with severity ratings
- Local persistence of physiological data and symptoms
- Historical visualization of health records

The system integrates sensor processing, asynchronous data handling, local storage, and UI-driven workflows into a single on-device application.

---

## What This Project Demonstrates

- Android application architecture and multi-activity navigation
- Sensor data acquisition and signal processing pipelines
- Asynchronous handling of camera and accelerometer data
- Local data persistence using SQLite
- UI-driven visualization of physiological measurements
- Safe handling of personal health data on-device

---

## System Architecture

High-level architecture diagrams are available in the `architecture/` directory:

- **App Architecture** — Layered separation of UI, logic, and system services
- **Data Flow** — End-to-end data lifecycle from sensor to storage to UI
- **Sensor Processing Flow** — Algorithm-level signal processing pipeline

---

## Design Documentation

Detailed design decisions are documented in the `design/` directory:

- Sensor data handling and processing strategy
- Database schema and persistence model
- UI navigation and user interaction flows
- Asynchronous measurement handling

---

## Validation & Results

The application was validated using emulator-based testing and simulated sensor inputs.

Validation highlights include:

- Correct heart rate and respiratory rate computation flow
- Reliable symptom logging and storage
- Consistent database persistence and retrieval
- Stable UI navigation across measurement workflows

Summaries are available in the `results/` directory.

---

## Technologies Used

- Android SDK
- Kotlin
- Camera API
- Accelerometer API
- SQLite
- Android Emulator

---

## Academic Integrity

This project was completed as part of graduate-level coursework.

- No cloud services or external servers are used
- No personal health data is transmitted off-device
- Source code and raw datasets are intentionally excluded
- Repository contents comply with academic integrity and privacy policies
