# Awesome Smart Irrigation [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of resources for smart irrigation controllers, evapotranspiration modeling, automated watering hardware, micro-climate sensing, and water conservation technologies.

Smart irrigation systems leverage real-time weather forecasts, soil moisture dynamics, and automated valve actuators to deliver precise water volumes, minimizing agricultural runoff and maximizing crop water productivity. This list is intended for agricultural engineers, irrigation designers, IoT developers, and smart farming practitioners.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Open Source Controllers & Controllers](#open-source-controllers--controllers)
- [Evapotranspiration & Water Modeling](#evapotranspiration--water-modeling)
- [Sensors & Hardware Protocols](#sensors--hardware-protocols)
- [Software & Decision Support Systems](#software--decision-support-systems)
  - [Automated Scheduling](#automated-scheduling)
  - [Analytics & Monitoring](#analytics--monitoring)
- [Related Awesome Lists](#related-awesome-lists)

## Open Source Controllers & Controllers

Open-source firmware, micro-controller code, and DIY automation controllers for precision valve control and irrigation scheduling.

- [OpenSprinkler](https://github.com/OpenSprinkler/OpenSprinkler-Firmware) — Open-source internet-connected sprinkler and irrigation controller platform for microcontrollers like ESP8266 and Raspberry Pi.
- [Hydra-Irrigation](https://github.com/hydra-irrigation/hydra) — Open-source automated irrigation controller system built for multi-zone field setups and micro-drip networks.
- [ESP-Irrigation](https://github.com/espressif/esp-idf) — ESP32-based firmware implementations for building low-power, Wi-Fi/LoRa-enabled smart irrigation relays.

## Evapotranspiration & Water Modeling

Algorithms, equations, and data APIs for computing reference evapotranspiration ($ET_0$) and crop water requirements ($ET_c$).

- [PyETo](https://github.com/woodb/pyeto) — Python library for calculating reference crop evapotranspiration using FAO-56 Penman-Monteith, Hargreaves, and Blaney-Criddle methods.
- [OpenET](https://github.com/OpenET) — Satellite-based framework providing high-resolution evapotranspiration data across agricultural lands for field-scale water management.
- [FAO-56 Implementation Tools](https://github.com/fao) — Reference implementations of crop coefficient calculations and water balance accounting models.

## Sensors & Hardware Protocols

Schemas, designs, and communication libraries for soil moisture sensors, weather stations, and valve actuators.

- [Chirp Soil Moisture Sensor](https://github.com/MICEtech/Chirp) — Open hardware I2C capacitive soil moisture sensor with integrated thermometer and light sensor.
- [LoRaWAN Agriculture Sensor Nodes](https://github.com/TheThingsNetwork) — End-to-end hardware schemas for long-range, battery-powered soil tension and volumetric water content (VWC) probes.
- [Open-Weather-Station](https://github.com/open-weather-station) — Blueprint repository for modular micro-climate weather stations monitoring solar radiation, humidity, and rainfall.

## Software & Decision Support Systems

Platforms and decision-support engines integrating environmental data to dictate irrigation events.

### Automated Scheduling

- [AgriCloud Irrigation Optimizer](https://github.com/openag) — Decision-support tool combining soil texture, crop growth stage, and local weather forecasts to automate drip schedules.
- [SmartIrrigation-App Engine](https://github.com/smart-irrigation) — Mobile and web framework providing daily crop water deficiency estimations based on real-time sensor streams.

### Analytics & Monitoring

- [Irrigation-Water-Budgeter](https://github.com/USDA-ARS) — Open analytical engine for computing seasonal water usage footprints and pump energy efficiency metrics.

## Related Awesome Lists

- [Awesome Precision Agriculture](https://github.com/brandonhimpfen/awesome-precision-agriculture) — Resources for site-specific farming, machine guidance, and variable rate technology.
- [Awesome Farm Management Systems](https://github.com/brandonhimpfen/awesome-farm-management-systems) — Open-source and commercial platforms for enterprise agricultural planning and record-keeping.
- [Awesome Crop Monitoring & Detection](https://github.com/brandonhimpfen/awesome-crop-monitoring-detection) — Tools and datasets for crop health inspection, remote sensing, and spectral analysis.
- [Awesome Sustainability](https://github.com/brandonhimpfen/awesome-sustainability) — Projects, datasets, and platforms promoting environmental sustainability and resource management.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
