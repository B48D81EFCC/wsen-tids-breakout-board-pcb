# Würth Elektronik WSEN-TIDS Breakout Board PCB
*KiCad project files for a breakout board using the Würth Elektronik WSEN-TIDS temperature sensor.*

## Overview
The breakout board simplifies integration of the **WSEN-TIDS temperature sensor** into your projects.  
The main goal of this PCB is to fit into stainless steel sleeve of around 5mm diameter.  

### JST SH connector pinout

| Pin # | Function |
|-------|----------|
| 1     | GND      |
| 2     | 3.3V     |
| 3     | SDA      |
| 4     | SCL      |

The pinout layout is widely used across different vendors of breakout boards with JST SH connector, allowing to use multiple different sensors on one bus more easily. Although the pin layout is (often) the same, each vendor uses their own brand names (e.g: STEMMA, μŠup)

> [!CAUTION]
> The design is not 5V compliant and 5V will destroy the sensor.  
> **Use 3.3V only.** 

---

![WSEN-TIDS Breakout Board Front](/docs/wsen-tids-breakout-board-pcb-01-front.png)

![WSEN-TIDS Breakout Board Front](/docs/wsen-tids-breakout-board-pcb-02-front.png)

![WSEN-TIDS Breakout Board Front](/docs/wsen-tids-breakout-board-pcb-01-back.png)

![WSEN-TIDS Breakout Board Front](/docs/wsen-tids-breakout-board-pcb-02-back.png)

# Additional resources
[Official WSEN-TIDS Product Page (Würth Elektronik Website)](https://www.we-online.com/de/components/products/WSEN-TIDS)
