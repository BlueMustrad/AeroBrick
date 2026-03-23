# AERO BRICK
A fully open-source and easy-to-build air-quality monitor designed for workshops, maker spaces, and home labs. It continuously tracks particulate matter (PM1–PM10), CO₂, VOCs, temperature, humidity, pressure, and hazardous chemicals, turning the air into actionable data.

Long-term exposure to fumes and poor ventilation is a real concern, especially in the form of soldering, 3D printing, or working with chemicals. As someone who is always working on a project, I come in contact with these more often than I should. AeroBrick solves this in that it's built to live right next to your workbench or printers, providing real-time monitoring and alerts when air quality begins to degrade, so you can act immediately instead of guessing.

Now you may ask, "Can't I buy one from Amazon and have it in my workshop within a day?" To which I say that these off-the-shelf air-quality monitors can cost $300–$400 and track only basic metrics like temperature or generic VOC levels. Whereas AeroBrick can be assembled in just a few days, while having a hell of a time, using readily available components, resulting in lab-grade monitoring at a fraction of the cost.


# The Design
Go to the [Images folder](https://github.com/BlueMustrad/AeroBrick/tree/main/Images) for all pictures!

## THE [FULL ASSEMBLY](https://github.com/BlueMustrad/AeroBrick/blob/main/AeroBrick%20Full%20Assembly.step)!!
<img width="1668" height="1304" alt="Screenshot 2026-03-22 125132" src="https://github.com/user-attachments/assets/745a359d-7454-4d5d-8bad-371575fd02d6" />

### Just the housing in [Fusion](https://github.com/BlueMustrad/AeroBrick/tree/main/3D%20Files/f3d%20Files):
<img width="2058" height="1477" alt="image" src="https://github.com/user-attachments/assets/6f8b4521-2b88-47db-9d11-0ff109118545" />

<img width="2708" height="1620" alt="image" src="https://github.com/user-attachments/assets/20bed8c9-5469-4a17-81cb-1681dd9536e2" />


### And in [Bambu Studio](https://github.com/BlueMustrad/AeroBrick/tree/main/3D%20Files/3mf%20Files) for 3D printing!
<img width="1986" height="1293" alt="image" src="https://github.com/user-attachments/assets/481ceb14-7f12-42ee-b89b-72dbce122ccd" />


### To go with it, you also need these [PCBs](https://github.com/BlueMustrad/AeroBrick/tree/main/PCBs%20and%20Circuitry):
<img width="1096" height="845" alt="image" src="https://github.com/user-attachments/assets/d80cd3bc-94cc-47ca-b328-727ad5555abe" />

<img width="1096" height="1543" alt="image" src="https://github.com/user-attachments/assets/5a6b3007-7fb0-46ea-95f1-de40fd180068" />

# Bill of Materials
Disclaimer: These prices do not factor in shipping or taxes!

| Item | Type | Quantity | Price (USD) | Item Total (USD) | Link |
|------|------|----------|-------------|------------------|------|
| T-Display S3 Long | Screen | 1 | $32.13 | $32.13 | [LilyGo](https://lilygo.cc/en-us/products/t-display-s3-long?variant=44211063390389) |
| SEN54-SDN-T | Sensor | 1 | $26.85 | $26.85 | [DigiKey](https://www.digikey.com/en/products/detail/sensirion-ag/SEN54-SDN-T/15903868) |
| BME280 | Sensor | 1 | $14.95 | $14.95 | [DigiKey](https://www.digikey.com/en/products/detail/adafruit-industries-llc/2652/5604372) |
| SEN0377 | Sensor | 1 | $39.90 | $39.90 | [DigiKey](https://www.digikey.com/en/products/detail/dfrobot/SEN0377/15848107) |
| SCD41 | Sensor | 1 | $28.99 | $28.99 | [Amazon](https://www.amazon.com/HiLetgo-Temperature-Humidity-Communication-Monitoring/dp/B0CDWXWCS5) |
| Qwiic Cable (50mm) | Cable | 2 | $1.50 | $3.00 | [DigiKey](https://www.digikey.com/en/products/detail/sparkfun-electronics/17260/13629028) |
| JST GHR-06V-S | Connector | 2 | $0.15 | $0.30 | [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/GHR-06V-S/807818) |
| JST GHR-07V-S | Connector | 2 | $0.14 | $0.28 | [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/GHR-07V-S/807819) |
| JST PHR-4 | Connector | 2 | $0.10 | $0.20 | [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/PHR-4/608606) |
| Amphenol 68604-804HLF | Connector | 1 | $0.53 | $0.53 | [DigiKey](https://www.digikey.com/en/products/detail/amphenol-fci/68604-804HLF/11606373) |
| JST ASPHSPH24K51 | Connector | 4 | $0.33 | $1.32 | [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/ASPHSPH24K51/6009457) |
| JST AGHGH28K51 | Connector | 12 | $0.39 | $4.68 | [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/AGHGH28K51/6009448) |
| Custom Made Mainboard | PCB | 5 | $1.20 | $6.00 | JLCPCB (+ $10-15 for stencil) |
| Custom Made Breakout Board | PCB | 5 | $1.20 | $6.00 | JLCPCB (+ $10-15 for stencil) |
| Mainboard Components | Components | — | — | $21.00 | See [PCB files](https://github.com/BlueMustrad/AeroBrick/blob/main/PCBs%20and%20Circuitry/Main%20Board/AeroBrick%20Mainboard%20BOM.csv) for details |
| Breakout Board Components | Components | — | — | $7.00 | See [PCB files](https://github.com/BlueMustrad/AeroBrick/blob/main/PCBs%20and%20Circuitry/Breakout%20Board/AeroBrick%20Breakout%20BOM.csv) for details |
| Hardware Total (as of 02/26) | | | | $193.13 | |

| Item | Total Price | Description |
| ---- | ----------- | ----------- |
| Fasteners | $7 | Screws, heat-set inserts, bolts, and washers |
| PCB Stencils | $22.06 | Used to add solder paste to the bare PCB |
| Hidden Costs | ~$125 | Shipping/taxes/tariffs :( |
| **Final Total (as of 03/26)** | | **$347.19** |

### **Additional Considerations (see [Other Parts](https://github.com/BlueMustrad/AeroBrick/blob/main/Documents/Extra%20Parts.md) for details), not included in the BOM:**
- Screws
- 3D-printing Filament
- Heat-set Inserts
- Solder Paste
- Superglue
- Isopropyl Alcohol
