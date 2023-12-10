# trailcambot
Activate Wifi in GardePro trailcam and download pictures

# Reverse Engineering a Trailcam
## Information gathering

- The App connects to the camera using Bluetooth Low Eneregy (BLE)
- The App writes "something" via BLE
- The camera then turns on Wifi
-- SSID is
-- Password is 12345678
- The App then connects via Wifi to the camera on port 8080


