# WeatherStation-V-3.0-Esphome
Complete monitoring wheater whit battery power

**DESCRIPTION:**
 - Create weather station and monitoring full scale weather by using ESPHome and connecting to home assistant
 
**NEWS:**

**FEATURES:**
**Wheater**
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

**Station**
   - Power on battery and solar
   - Temperature battery and solar panel
   - Full measure electricity and battery monitoring
   - Connection and failure state
   - Wifi signal

**Camera**
   - Monitoring live video
   - Spotlight
 
**PARTS AND COMPONENT:**
- REQUIRED
   - MCU
       - 1x [ESP32CAM 3.5€](https://a.aliexpress.com/_mNO3h4e)
       - 1x [ESP-32S 2.5€](https://a.aliexpress.com/_mtYXh6i) + [Adapter 0.5€](https://a.aliexpress.com/_mNiOE98)
   - MODULES
       - 1x [MQ-2 Smoke sensor 0.9€](https://a.aliexpress.com/_mqTxVIi)
       - 1x [BME280 temperature humidity pressure sensor 3.8€](https://www.aliexpress.com/item/32862421810.html)
       - 1x [MS-WH-SP-RG Rain gauge 17.1€](https://www.aliexpress.com/item/2026877912.html)
       - 1x [MH-RD Raindrop 0.8€](https://www.aliexpress.com/item/1615411920.html)
       - 1x [MHZ19 Intelligent Infrared CO2 Module 22.56€](https://www.aliexpress.com/item/4000212024923.html)
       - 1x [IKEA VINDRIKTNING Particulate Matter Sensor 11.99€ (SK store)](https://www.ikea.com/sk/sk/p/vindriktning-snimac-kvality-vzduchu-80515910/)
       - 1x [Level shifter 0.4€](https://www.aliexpress.com/item/1005002976498419.html)
       - 1x [GY-302 BH1750 light intensity illumination Sensor 1.10€](https://www.aliexpress.com/item/1005001621873442.html)
       - 1x [GY-8511 UV Sensor 8.5€](https://www.aliexpress.com/item/32847192530.html)
       - 1x [WH-SP-WS01 wind speed anemometer]
       - 1x [WH-SP-WD wind direction]
       - 1x [Geiger Counter RadiationD-v1.1-CAJOE 30.0€](https://www.aliexpress.com/item/1005004896319865.html)
    - ELECTRICITY
       - 1x [Solar Panel 18V 25W (50W) 35.0€](https://www.amazon.com/ECO-WORTHY-Solar-Panel-Module-Charging/dp/B01IFJ73X4)
       - 1x [XL4015 5A DC to DC CC CV Lithium Battery Step down Charging Board 1.42€](https://www.aliexpress.com/item/1005003112889788.html)
    - MECHANICAL


- OPTIONAL
  - 1x [OV2640 Camera Module Wide-angle 160 Degree 3.5€](https://a.aliexpress.com/_mLNkjQE)
  - 1x red LED + [8x white high britghess Leds 1.0€](https://a.aliexpress.com/_mLdLj0m)
  - 2x [DALLAS DS18B20]
  - 1x [Fan 5V 50mm 2pin low consumption]

- COMPONENT
  Required
  - 1x Power Mofset NPN Irfz44N 0.15€
  - 1x Resistor 100ohm 0.01€
  - 1x Resistor 1k 0.01€
  - 1x Resistor 1206SMD 10k 0.01€
  - 4x Resistor 10k 0.04€
  - 5x Capacitor ceramic 0.1uF 0.05€
  Optional
  - 1x Resistor 4.7k 0.01€
  - 1x NPN Darlington TIP122
  - 1x Resistor 220ohm 0.01€
  - 1x Resistor 10k 0.01€
  - 1x Protect Schottky diode SS14 0.01€

  



