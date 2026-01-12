# Sensor Interaction Design

The application separates sensor interaction from UI logic.

## Sensor Controller
- Manages access to camera and accelerometer APIs
- Handles lifecycle-aware sensor activation
- Ensures sensors are released when inactive

## Data Flow
- Raw sensor signals → preprocessing → estimation
- Results are forwarded to application logic and UI

