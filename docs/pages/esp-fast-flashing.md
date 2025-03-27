---
layout: page
title: ESP Flashing TL&DR
permalink: /esp-fast-flashing
---

# ESP Flashing

**The soldering must already be done!**

- Put the soldered ESP-01 with wifi module in your computer
  - While inserting in your computer, connect the loose wire with pin A (see picture below)
- Home Assistant > ESPHome Builder
  - \+ New Device
    - Pick a goofy name
    - ESP8266
    - Copy Encryption Key (just in case;)
    - Install
    - Cancel
  - Goofy name > Edit
    - Save
    - Install
    - Manual Download
- Goto: [https://web.esphome.io/](https://web.esphome.io/)
  - Connect
    - USB Serial (COM 3) - Paired
    - Connect
  - Prepare For First Use
    - Install
    - Select downloaded file
    - Install


## Pins Diagram

![Pins diagram]({{ "/assets/img/esp-flash/soldering1.png" | relative_url }})
