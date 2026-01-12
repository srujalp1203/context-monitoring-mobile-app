# Asynchronous Data Handling

The application relies on asynchronous data acquisition to ensure smooth user interaction while collecting sensor measurements.

## Camera-Based Heart Rate Measurement
- Camera frames are captured asynchronously using the Android Camera API
- Frame sampling prevents excessive computation
- Processing runs off the UI thread to avoid blocking interactions

## Accelerometer-Based Respiratory Rate Measurement
- Accelerometer data is streamed asynchronously
- Motion signals are buffered and processed in batches
- Signal processing occurs independently of UI updates

## Benefits
- Responsive UI during measurements
- Safe handling of sensor latency
- Improved stability across devices

