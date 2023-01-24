# WeatherStation-V-3.0-Esphome
Complete monitoring wheater whit battery power

**DESCRIPTION:**
 - Create weather station and monitoring full scale weather by using ESPHome and connecting to home assistant
 
**NEWS:**

**FEATURES:**
**- Wheater**
  - WIND
    - Speed (km/h)
    - Direction (coordinates)
  
  - RAIN
    - Precipitation rate (mm)
    - Quantity (mm/min)
    - Detection (WET/DRY)
  
  - SUN
    - Lighting intensity (Lux)
    - Ultraviolet radiation UVA, UVB (UV)
    - UV intenzity (mW/cm^2)
    - Solar Radiation ((W/m2)/day)
  
  - AIR
    - Temperature (°C)
    - Dew point (°C)
    - Humidity (%)
    - Pressure (hPa)
    - Smoke (%)
    - CO2 (ppm)
    - Particulate Matter pm2.5 (ppm)
    - Active Radiation shield whit fan
    
  - IONIZING RADIATION
    - Radiation counter (CPM) 
    - Radiation power Beta and Gamma (µSv/h)

**- Station**
   - Power on battery and solar
   - Temperature battery and solar panel
   - Full measure electricity and battery monitoring
   - Connection and failure state
   - Wifi signal

**- Camera**
   - Monitoring live video
   - Spotlight
 
**PARTS AND COMPONENT:**
- REQUIRED
   - MCU
       - 1x [ESP32CAM 3.5€](https://a.aliexpress.com/_mNO3h4e)
       - 1x [ESP-32S 2.5€](https://a.aliexpress.com/_mtYXh6i) + [Adapter 0.5€](https://a.aliexpress.com/_mNiOE98)
   - MODULES
       - 1x [MQ-2 Smoke sensor](€ 0,92  15%OFF | TZT MQ-2 MQ2 Smoke Gas LPG Butane Hydrogen Gas Sensor Detector Module For Arduino
https://a.aliexpress.com/_mqTxVIi)
       - 1x [BME280]
       - 1x [MS-WH-SP-RG Rain gauge]

   
- OPTIONAL
  - [OV2640 Camera Module Wide-angle 160 Degree 3.5€](https://a.aliexpress.com/_mLNkjQE)
  - 1x red LED + [8x white high britghess Leds 1.0€](https://a.aliexpress.com/_mLdLj0m)
  - 2x [DALLAS DS18B20]
  - 1x [Fan 5V 50mm 2pin low consumption]

- COMPONENT
  Required
  - 1x Power Mofset NPN Irfz44N 0.15€
  - 1x Resistor 100ohm 0.01€
  - 1x Resistor 1k 0.01€
  - 1x Resistor 1206SMD 10k 0.01€
  - 1x Resistor 10k 0.01€
  

  Optional
  - 1x Resistor 4.7k 0.01€
  - 1x NPN Darlington TIP122
  - 1x Resistor 220ohm 0.01€
  - 1x Resistor 10k 0.01€

  



