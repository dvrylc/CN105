## Setup

- Controller: AtomS3 Lite based on ESP32-S3
- Heatpump units:
  - MSXY-FP10VG
  - MSXY-FP13VG
  - MSXY-FP24VG

## Notes

```
python3 -m venv venv
source venv/bin/activate
pip install esphome==2025.6.0

esphome compile <yml>
esphome upload <yml> // OTA
```
