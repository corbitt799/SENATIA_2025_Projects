# Particle Boron 404x Remote Monitor Project SE NATIA 2025

## Links:
Particle IO:
https://www.particle.io/

Blynk IO:
https://www.blynk.io/

## Webhook Configurations

Particle HTTP Get URL:
'https://ny3.blynk.cloud/external/api/batch/update'
Particle Events URL:
'https://ny3.blynk.cloud/external/api/logEvent'

To generate particle token for Blynk webhook:
https://docs.particle.io/reference/cloud-apis/access-tokens/

Blynk webhook URL:
'https://api.particle.io/v1/devices/YOURIDHERE/setRelay'

Blynk JSON Content:
arg={device_pinValue}

Authorization   Bearer 712c91871cea1540cd0f1a81f80955aff4e7cb49
Content-Type    application/x-www-form-urlencoded
