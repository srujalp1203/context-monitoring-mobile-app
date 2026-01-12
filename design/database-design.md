# Database Design

The application uses a local SQLite database to persist physiological and symptom data.

## Stored Attributes
- Heart rate (BPM)
- Respiratory rate (breaths per minute)
- Symptom severity ratings
- Timestamps

## Design Rationale
- Local-only storage preserves user privacy
- Structured schema enables historical analysis
- Indexed access supports efficient retrieval

## Usage
- Records are written after each measurement session
- History is retrieved for visualization and review
