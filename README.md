# Guardian Band - Device designed for SOS alerts and real-time GPS tracking
The term "Smart Location Band" can refer to various wearable devices designed to enhance personal safety, health monitoring, and navigation. 
The Smart Location Band is a wearable device designed to enhance personal safety using ESP 32 component.
It continuously monitors the wearer’s location through GPS and sends alerts in case of emergencies.
  - The device can notifies caregivers or family members via SMS, mobile apps, or through vibration alerts.
  - It is lightweight, portable, and suitable for children, elderly, women, or workers in hazardous environments.
By providing real-time tracking and emergency alerts, it ensures safety and peace of mind for both users and their guardians.
## Project Overview :
The Smart Location Band is a wearable IoT device that provides real-time location tracking and emergency alerts.
It uses GPS and GSM modules to send location data to caregivers or guardians when the user is in distress.
The band also supports geofencing, vibration alerts, and smartphone connectivity for instant notifications.
Lightweight and portable, it is suitable for children, elderly individuals, and workers in hazardous environments.
By combining safety and technology, it ensures reliable monitoring.
## Components :
## Workflow :
  - The band powers on and initializes the ESP32 microcontroller along with GPS and GSM modules.
  - GPS continuously tracks the real-time location of the wearer.
  - The location data is processed and monitored by the ESP32.
  - If the wearer presses the SOS button or exits a predefined geofenced area, an emergency is triggered.
  - The ESP32 sends the location and alert message through the GSM module to predefined contacts.
  - Simultaneously, the band notifies the wearer with vibration and LED signals.
  - Caregivers or guardians receive the alert (via SMS or mobile app notification) and can track the user’s location.
  - The system continues monitoring until the emergency is resolved or manually reset.
## Key features :
      1. Real-time GPS Tracking – Provides accurate location updates of the wearer to the guardian.
      2. SOS Emergency Alert – Sends instant SMS/app notifications to predefined contacts when triggered.
      3. IoT Connectivity – Works with GSM/Bluetooth for seamless communication.
      4. Vibration & LED Indicators – Notifies the wearer during emergencies or alerts.
      5. Lightweight & Portable Design – Comfortable to wear for long durations.
      6. Rechargeable Battery – Ensures long-lasting, low-power operation.
      7. Smartphone Integration – Compatible with mobile apps for monitoring and alerts with a notification.
      8. Multi-user Application – Useful for children, elderly, women’s safety, and industrial workers.
## Why it matters :
