# CODETECH-TASK-2
NAME:Tanmayee Ajay Bramhankar
Company:CODETECH IT SOLUTIONS
ID:CT08DBT
Domain:Embedded systems
Duration:Dec 2024 to Jan 2025
Mentor:Neela Kumar

OVERVIEW OF PROJECT
 Vehicle Tracking System with GPS and GSM using Arduino

A **Vehicle Tracking System** with **GPS** and **GSM** is a useful project that allows tracking the location of a vehicle in real-time. By using a GPS module to fetch the current coordinates (latitude and longitude) and a GSM module to send the location data to a mobile phone, the vehicle can be tracked easily. Below is an overview and Arduino code for such a system.

 Components Needed:
1. **Arduino Uno or Nano**
2. **GPS Module (e.g., NEO-6M)**
3. **GSM Module (e.g., SIM900 or SIM800L)**
4. **Jumper Wires**
5. **External Power Supply** (for GSM module if needed)
6. **SIM card with SMS service activated**

 Circuit Diagram:

1. **GPS Module (NEO-6M)**:
   - VCC → 5V (Arduino)
   - GND → GND (Arduino)
   - TX → Pin 4 (Arduino)
   - RX → Pin 3 (Arduino)

2. **GSM Module (SIM900 or SIM800L)**:
   - VCC → 5V (Arduino or external power supply)
   - GND → GND (Arduino)
   - TX → Pin 7 (Arduino)
   - RX → Pin 8 (Arduino)

 Enhancements:
- **Real-Time Tracking**: Instead of sending SMS every few seconds, you could integrate the system with a web server (e.g., using an ESP8266 or ESP32) to track the vehicle's location on a map in real-time.
- **Geofencing**: Add a geofence feature to alert you when the vehicle enters or exits a predefined area.
- **Location Logging**: Store GPS coordinates on an SD card or send them to a cloud database for long-term tracking.

This simple vehicle tracking system provides real-time GPS data to your phone via SMS, allowing you to track the vehicle's location effectively.
