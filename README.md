
---

## 🧠 **ACA-Zigbee-SyncLED**
```markdown
# ACA-Zigbee-SyncLED

### Overview
This project explores Zigbee networking fundamentals using two ESP32-C6 boards.  
One board acts as a Zigbee Coordinator (network creator) and the other as an End Device, exchanging On/Off cluster commands to synchronize LED states.

### Objectives
- Learn Zigbee stack initialization and network formation.
- Configure the ESP32-C6 as both coordinator and end device.
- Implement Zigbee On/Off cluster control for LED toggling.

### Milestones
- **v0.1** – Coordinator forms Zigbee network
- **v0.2** – End device joins and syncs LED state
- **v0.3** – Bidirectional LED control verified

### Build & Flash
```bash
idf.py set-target esp32c6
idf.py build
idf.py -p <PORT> flash monitor
