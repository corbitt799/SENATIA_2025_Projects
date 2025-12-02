# SE NATIA 2025 Conference Projects

This repository contains setup details and useful links for our 2025 projects.  

Please DO NOT try to work ahead of class.  We will reference sections of this site when appropriate.  

---

## ESP32 Camera Setup with Arduino IDE

### Arduino IDE Download
Download the latest Arduino IDE from the official Arduino website:

[https://www.arduino.cc/en/software/](https://www.arduino.cc/en/software/)

### ESP32 Board Manager URL
Add the following Board Manager URL in Arduino IDE for ESP32 board support:

`https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json`

### ESP32-CAM_MJEPG2SD

[https://github.com/s60sc/ESP32-CAM_MJPEG2SD](https://github.com/s60sc/ESP32-CAM_MJPEG2SD)

---

## Particle Boron 404x Remote Monitoring

### Useful Links
- Particle IO: [https://www.particle.io/](https://www.particle.io/)
- Blynk IO: [https://www.blynk.io/](https://www.blynk.io/)

### Webhook URLs for Particle to Blynk Integration
- Particle HTTP Get URL for batch updates:  
  `https://ny3.blynk.cloud/external/api/batch/update`
- Particle Events URL:  
  `https://ny3.blynk.cloud/external/api/logEvent`

### Generating Particle Token for Blynk Webhooks
Refer to Particle documentation for creating access tokens:  
[https://docs.particle.io/reference/cloud-apis/access-tokens/](https://docs.particle.io/reference/cloud-apis/access-tokens/)

### Example Blynk Webhook URL for Particle Device Control
`https://api.particle.io/v1/devices/YOURIDHERE/setRelay`

Replace `YOURIDHERE` with your Particle device ID.

### Content Type / Custom JSON
- 1 arg={device_pinValue}

### HTTP Headers (optional)
|                         |                                    |
|-------------------------|------------------------------------|
| Authorization           | Bearer YOURPARTICLETOKENHERE       |
| Content-Type            | application/x-www-form-urlencoded  |



---




