# RIVboard
is a compact, four-button hackpad built around the Seeed Studio XIAO RP2040. Inspired by a tutorial and adapted with custom features, it includes onboard LEDs and a 3D-printed enclosure designed in Fusion 360. It’s a simple, functional tool for testing, triggering, or building interactive projects.

**CAD**
https://hc-cdn.hel1.your-objectstorage.com/s/v3/b6abbeb8c49e329558b84f7cfd38f42fb78aa3e6_screenshot_2025-07-01_at_1.28.17___pm.png

https://hc-cdn.hel1.your-objectstorage.com/s/v3/b8c9f3609562bfc06fb39f7dfc97b07bd5cf7001_screenshot_2025-07-01_at_1.32.40___pm.png

**PCB**
https://hc-cdn.hel1.your-objectstorage.com/s/v3/a90c10278c94f68dbb0c991ab063cf812b724b7f_screenshot_2025-07-01_at_1.33.25___pm.png

**BOM**
| Quantity | Component              | Part Name / Notes                         | Source / Notes                     |
| -------- | ---------------------- | ----------------------------------------- | ---------------------------------- |
| 1        | Microcontroller Board  | Seeed Studio **XIAO RP2040**              | USB-C, used as the core controller |
| 4        | Tactile Push Buttons   | **SW\_Push** (standard momentary switch)  | For input                          |
| 4        | Keycaps (optional)     | MX-compatible or similar                  | Optional for top aesthetics        |
| 4        | RGB LEDs (optional)    | **SK6812 MINI** (Neopixels)               | Individually addressable lighting  |
| 1        | Custom PCB             | Designed in KiCad, includes routed traces | Fabricate with JLCPCB / OSH Park   |
| 1        | 3D Printed Bottom Case | Custom case designed in Fusion 360        | PLA or similar material            |
| 1        | 3D Printed Top Plate   | Holds key switches in place               | Matches button layout              |
| 4        | M3 Screws + Standoffs  | Optional hardware for mounting the case   | Nylon or metal                     |
| 1        | USB-C Cable            | For power/programming                     | Any standard USB-C                 |

