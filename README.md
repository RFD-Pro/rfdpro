# Privacy Policy for RFD Pro

**Effective Date**: October 15, 2026  
**Last Updated**: October 15, 2026

## 1. Overview
**RFD Pro** ("we", "our", or "us") respects your privacy. This Privacy Policy explains how our Android application and Wear OS companion app collect, use, and protect your information when you use our services.

## 2. Information We Collect

### A. Sensor, Velocity & Acceleration Data
RFD Pro accesses your device's built-in accelerometer and Bluetooth Low Energy (BLE) sensors to measure physical force, acceleration (m/s²), Mean Propulsive Velocity (MPV), and Rate of Force Development (RFD).
- **Processing**: All sensor data is processed **100% locally on your device**.
- **Transmission**: Sensor data is streamed strictly between your own paired devices (e.g. phone to smartwatch or phone to phone) via local Bluetooth LE. No sensor data is uploaded to external servers or third parties.

### B. Device & Bluetooth Permissions
To scan for and connect to BLE sensor devices or smartwatches, RFD Pro requests the following permissions:
- `BLUETOOTH_SCAN`, `BLUETOOTH_CONNECT`, `BLUETOOTH_ADVERTISE` (Android 12+)
- `ACCESS_FINE_LOCATION` (Required by Android OS for legacy Bluetooth LE discovery)

**Note**: RFD Pro does **NOT** track, record, store, or transmit your geographical location. Location permissions are utilized solely to satisfy Android OS requirements for discovering nearby Bluetooth LE hardware.

### C. In-App Purchase & Billing Data
Purchases of PRO and TRAIN lifetime access are processed securely by **Google Play Billing**.
- We do not store or collect financial information, credit card details, or personal billing addresses.
- Google Play handles all transaction data in accordance with the [Google Play Terms of Service](https://play.google.com/about/play-terms/).

## 3. Data Storage & Security
All workout records, velocity traces, session tags, personal 1RM profiles, and custom settings are stored locally on your device in a private local SQLite database. You may delete your data at any time by clearing history within the app or uninstalling the application. We do not maintain any cloud-hosted copies of your workout data.

## 4. Analytics & Tracking
RFD Pro contains **no third-party tracking scripts, advertising SDKs, or analytics frameworks**. We do not track your usage across other apps or websites.

## 5. Children's Privacy
RFD Pro is intended for general audiences (ages 13 and older) and does not knowingly collect personal information from children under the age of 13.

## 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be posted within the application and on our store listing.

## 7. Contact Us
If you have any questions regarding this Privacy Policy, please contact us at:  
**Email**: `carlosgilglez@gmail.com`
