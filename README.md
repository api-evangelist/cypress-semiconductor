# Cypress Semiconductor (cypress-semiconductor)

Cypress Semiconductor was a US-based semiconductor company known for its PSoC programmable system-on-chip microcontrollers, WICED Wi-Fi and Bluetooth connectivity stacks, NOR Flash memory, CapSense capacitive touch sensing, and Traveo automotive microcontrollers. Infineon Technologies completed its $9.4 billion acquisition of Cypress on April 16, 2020, and Cypress now operates as a wholly owned subsidiary of Infineon. The former Cypress product lines (PSoC, AIROC formerly WICED, NOR Flash, CapSense, Traveo) remain in active development under Infineon branding, and the cypress.com domain redirects to infineon.com. The former Cypress developer surface — including PSoC Creator (legacy) and the modern ModusToolbox embedded development ecosystem — is now hosted on the Infineon GitHub organization (github.com/Infineon) which contains 2,143 public repositories spanning code examples, board support packages, HAL libraries, middleware, and configurators for PSoC, AIROC, Traveo, XMC, and AURIX device families. The original Cypress GitHub organization (github.com/cypresssemiconductorco) has been wound down to four placeholder repos that redirect users to the Infineon org. Cypress' APIs are predominantly embedded software APIs (C/C++ HAL, PDL, middleware libraries) rather than HTTP/REST surfaces, consumed by firmware engineers via ModusToolbox, Eclipse, and Visual Studio Code workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cypress-semiconductor/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Acquired, Bluetooth, CapSense, Embedded Systems, Hardware, Infineon, IoT, Microcontrollers, NOR Flash, PSoC, Semiconductor, WiFi

## Timestamps

- **Modified:** 2026-05-23

## Acquisition Note

Cypress Semiconductor became part of Infineon Technologies on **16 April 2020** in a transaction valued at approximately **$9.4 billion**. All former Cypress product lines (PSoC, AIROC formerly WICED, CapSense, TRAVEO T2G, Semper / HyperFlash NOR Flash, USB-C PD) continue under Infineon branding. The developer surface for these products now lives on `infineon.com`, `documentation.infineon.com`, `community.infineon.com`, and `github.com/Infineon`. The legacy `cypress.com` domain redirects to `infineon.com`; the legacy `github.com/cypresssemiconductorco` organization retains only four placeholder/redirect repositories.

## APIs

### ModusToolbox Software Ecosystem

ModusToolbox is Infineon's modern embedded development ecosystem and the successor to Cypress' PSoC Creator. It is a collection of GUI and non-GUI tools, libraries, configurators, board support packages (BSPs), and middleware for building applications on PSoC Arm Cortex microcontrollers (inherited from Cypress), AIROC Wi-Fi and Bluetooth devices (formerly Cypress WICED), TRAVEO T2G automotive microcontrollers (inherited from Cypress), XMC industrial microcontrollers, and USB-C Power Delivery microcontrollers. ModusToolbox runs on Linux, macOS, and Windows, supports VS Code, Eclipse, and IAR IDEs, and ships with the GNU C compiler. The most recent stable release line as of 2026 is ModusToolbox v3.x (v3.7 reference in the Infineon developer community).

**Human URL:** [https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software/](https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software/)

#### Tags

- AIROC, Embedded Development, IDE, ModusToolbox, PSoC, TRAVEO, XMC

#### Properties

- [Documentation](https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software/)
- [APIReference](https://documentation.infineon.com/modustoolbox/docs/tpf1712593103524)
- [GitHubRepository](https://github.com/Infineon/modustoolbox-software)
- [CodeExamples](https://github.com/Infineon/Code-Examples-for-ModusToolbox-Software)
- [Training](https://github.com/Infineon/training-modustoolbox)
- [SDK](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolbox)
- [Support](https://community.infineon.com/t5/ModusToolbox/bd-p/ModusToolboxForum)

### PSoC HAL and Peripheral Driver Library (PDL)

The PSoC Hardware Abstraction Layer (HAL) and Peripheral Driver Library (PDL) are the C-language embedded APIs developers use to program Cypress-originated PSoC 4, PSoC 6, and PSoC Edge microcontrollers. The mtb-hal-cat1 and mtb-pdl-cat1 libraries — distributed as ModusToolbox components — provide register-level and abstracted drivers for GPIO, SCB, TCPWM, Crypto, USB, and other PSoC peripherals. These libraries are the modern Infineon-branded replacement for the legacy Cypress PSoC Creator component library.

**Human URL:** [https://infineon.github.io/mtb-hal-cat1/html/index.html](https://infineon.github.io/mtb-hal-cat1/html/index.html)

#### Tags

- C, Embedded Systems, HAL, Microcontrollers, PDL, PSoC

#### Properties

- [Documentation](https://infineon.github.io/mtb-hal-cat1/html/index.html)
- [GitHubRepository](https://github.com/Infineon/mtb-hal-cat1)
- [GitHubRepository](https://github.com/Infineon/mtb-pdl-cat1)

### AIROC Bluetooth (formerly WICED)

AIROC Bluetooth is the Infineon-rebranded Cypress WICED Bluetooth and Bluetooth LE software stack and SDK, supporting CYW20xxx, CYW43xxx, and AIROC combo Bluetooth/Wi-Fi parts inherited from the Cypress acquisition. Developers use the btsdk-* and AIROC libraries via ModusToolbox to build BLE peripherals, central applications, mesh networks, and Bluetooth audio products. WICED Studio has been deprecated in favor of ModusToolbox-based AIROC flows.

**Human URL:** [https://www.infineon.com/cms/en/product/promopages/airoc-bluetooth/](https://www.infineon.com/cms/en/product/promopages/airoc-bluetooth/)

#### Tags

- AIROC, Bluetooth, BLE, Embedded Systems, WICED, Wireless

#### Properties

- [Documentation](https://www.infineon.com/cms/en/product/promopages/airoc-bluetooth/)
- [GitHubRepository](https://github.com/Infineon/btsdk-include)
- [Support](https://community.infineon.com/t5/AIROC-Bluetooth/bd-p/AIROCBluetoothForum)

### AIROC Wi-Fi (formerly WICED)

AIROC Wi-Fi is the Infineon-rebranded Cypress WICED Wi-Fi stack and SDK, including the Wi-Fi Host Driver (WHD) and connectivity middleware that drives CYW43xxx and CYW55xxx Wi-Fi chipsets originally designed by Cypress (and prior to that, Broadcom). It is delivered as ModusToolbox middleware libraries (wifi-host-driver, wifi-connection-manager, wifi-mw-core) and supports station mode, AP mode, WPA3, and cloud-connected IoT applications on PSoC 6 and PSoC Edge hosts.

**Human URL:** [https://infineon.github.io/wifi-host-driver/html/index.html](https://infineon.github.io/wifi-host-driver/html/index.html)

#### Tags

- AIROC, Embedded Systems, IoT, WHD, WICED, WiFi

#### Properties

- [Documentation](https://infineon.github.io/wifi-host-driver/html/index.html)
- [GitHubRepository](https://github.com/Infineon/wifi-host-driver)
- [GitHubRepository](https://github.com/Infineon/wifi-connection-manager)

### CapSense Capacitive Touch Library

CapSense is Cypress' (now Infineon's) capacitive touch sensing technology, exposed to firmware developers as a ModusToolbox middleware library and Device Configurator personality. CapSense supports buttons, sliders, touchpads, and proximity sensing on PSoC 4, PSoC 6, and PSoC Edge devices with SmartSense auto-tuning. The CapSense Configurator GUI generates the tuning C structures consumed at runtime by the CapSense library.

**Human URL:** [https://infineon.github.io/capsense/capsense_api_reference_manual/html/index.html](https://infineon.github.io/capsense/capsense_api_reference_manual/html/index.html)

#### Tags

- CapSense, Embedded Systems, HMI, PSoC, Touch Sensing

#### Properties

- [Documentation](https://infineon.github.io/capsense/capsense_api_reference_manual/html/index.html)
- [GitHubRepository](https://github.com/Infineon/capsense)

### TRAVEO T2G Automotive Microcontroller SDK

TRAVEO T2G is the automotive Arm Cortex-M microcontroller family inherited from Cypress, now developed under Infineon. Developers program TRAVEO T2G via ModusToolbox using a dedicated PDL, HAL, and BSP set (mtb-pdl-cat1, mtb-hal-cat1 variants and the cat1c CMSIS device support) for body, cluster, and gateway ECU applications. AURIX Development Studio remains the path for Infineon's TriCore AURIX automotive MCUs, while TRAVEO T2G stays on ModusToolbox.

**Human URL:** [https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/)

#### Tags

- Automotive, Cortex-M, Embedded Systems, Microcontrollers, TRAVEO

#### Properties

- [Documentation](https://www.infineon.com/cms/en/product/microcontroller/32-bit-traveo-t2g-arm-cortex-microcontroller/)
- [GitHubRepository](https://github.com/Infineon/mtb-pdl-cat1)
- [Support](https://community.infineon.com/t5/TRAVEO-T2G/bd-p/TRAVEOT2GForum)

### Cypress / Infineon NOR Flash Memory

Cypress' Semper, HyperFlash, FL-S, and FL-L Serial NOR Flash families became part of Infineon's memory portfolio after the 2020 acquisition. Developer-facing artifacts include the Semper Flash Configuration Tool (separate from ModusToolbox), reference drivers, and the serial-flash and serial-memory ModusToolbox middleware libraries that wrap SPI/QSPI/HyperBus access for PSoC hosts. The product line is documented under infineon.com/memory.

**Human URL:** [https://www.infineon.com/cms/en/product/memories/nor-flash/](https://www.infineon.com/cms/en/product/memories/nor-flash/)

#### Tags

- Flash Memory, HyperFlash, Memory, NOR Flash, Semper

#### Properties

- [Documentation](https://www.infineon.com/cms/en/product/memories/nor-flash/)
- [GitHubRepository](https://github.com/Infineon/serial-flash)
- [GitHubRepository](https://github.com/Infineon/serial-memory)

## Common Properties

- [Portal](https://www.infineon.com)
- [DeveloperPortal](https://softwaretools.infineon.com/welcome)
- [Documentation](https://documentation.infineon.com/modustoolbox/)
- [GitHubOrganization (current)](https://github.com/Infineon)
- [GitHubOrganization (legacy)](https://github.com/cypresssemiconductorco)
- [Support](https://community.infineon.com)
- [LinkedIn](https://www.linkedin.com/company/infineon-technologies)
- [Blog](https://community.infineon.com/t5/Blogs/ct-p/Blogs)
- [TrustCenter / Acquisition Notice](https://www.infineon.com/cms/en/about-infineon/company/acquisitions/cypress/)

## Features

| Name | Description |
|------|-------------|
| PSoC Programmable System-on-Chip | Cypress' flagship PSoC 4, PSoC 6, and PSoC Edge Arm Cortex-M MCUs with configurable analog and digital fabric, now produced under Infineon. |
| AIROC Wireless Connectivity | Rebranded WICED Wi-Fi and Bluetooth combo silicon (CYW43xxx, CYW20xxx, CYW55xxx) with ModusToolbox middleware. |
| CapSense Capacitive Touch | Capacitive sensing IP for buttons, sliders, and proximity, with SmartSense auto-tuning and a dedicated Configurator GUI. |
| TRAVEO T2G Automotive MCUs | Arm Cortex-M-based automotive microcontrollers for body, cluster, and gateway ECUs, developed via ModusToolbox. |
| Semper / HyperFlash NOR Memory | High-reliability and high-bandwidth NOR Flash memory families with serial, QSPI, and HyperBus interfaces. |
| ModusToolbox Development Ecosystem | Cross-platform tools, BSPs, HAL/PDL libraries, middleware, and configurators that replaced Cypress PSoC Creator and WICED Studio. |
| Open Source Reference Code | 2,143 public repositories on the Infineon GitHub org including 87+ ModusToolbox-tagged repos, mtb-example-* code examples, and BSP packages. |

## UseCases

| Name | Description |
|------|-------------|
| Connected IoT Devices | Building Wi-Fi and Bluetooth-connected IoT endpoints on PSoC 6 + AIROC silicon using ModusToolbox middleware. |
| Touch and HMI Interfaces | Designing capacitive touch buttons, sliders, and proximity surfaces with CapSense on PSoC microcontrollers. |
| Automotive ECU Development | Programming TRAVEO T2G microcontrollers for body, cluster, and gateway electronic control units. |
| Industrial Microcontrollers | Using PSoC and XMC parts together in factory automation, motor drive, and industrial sensing applications. |
| Secured Embedded Applications | Leveraging PSoC 6 dual-core (Cortex-M4 + Cortex-M0+) architecture and OPTIGA Trust for root-of-trust IoT designs. |
| USB-C Power Delivery | Building USB-C PD controllers and chargers on Infineon's PD MCU family with ModusToolbox. |

## Integrations

| Name | Description |
|------|-------------|
| Visual Studio Code | ModusToolbox ships a VS Code extension as a primary supported IDE for embedded development. |
| Eclipse IDE | ModusToolbox integrates with Eclipse via the Eclipse IDE for ModusToolbox distribution. |
| IAR Embedded Workbench | ModusToolbox project export supports IAR EWARM for Arm Cortex-M PSoC targets. |
| Arm Mbed OS | PSoC 6 and AIROC parts have Arm Mbed OS targets, enabling Mbed-based application development. |
| Zephyr RTOS | Infineon contributes board support for PSoC 6 and PSoC Edge to the Zephyr RTOS project. |
| MicroPython | An Infineon-maintained PSoC 6 / PSoC Edge port of MicroPython enables Python-based prototyping. |
| Arduino | Arduino cores exist for XMC (XMC-for-Arduino) and PSoC 6 (arduino-core-psoc6) on the Infineon GitHub org. |
| Amazon FreeRTOS | Cypress was a launch partner for Amazon FreeRTOS; the amazon-freertos repository remains in the legacy Cypress GitHub org. |

## Artifacts

Machine-readable artifacts profiling Cypress / Infineon's developer surface.

### JSON Schema

- [Cypress Semiconductor Board Support Package Schema](json-schema/cypress-semiconductor-board-support-package-schema.json)
- [Cypress Semiconductor CapSense Configuration Schema](json-schema/cypress-semiconductor-capsense-configuration-schema.json)
- [Cypress Semiconductor ModusToolbox Application Schema](json-schema/cypress-semiconductor-modustoolbox-application-schema.json)

### JSON-LD

- [Cypress Semiconductor Context](json-ld/cypress-semiconductor-context.jsonld)

## Vocabulary

- [Cypress Semiconductor Vocabulary](vocabulary/cypress-semiconductor-vocabulary.yml) — Domain vocabulary for Cypress product lines (PSoC, AIROC/WICED, CapSense, TRAVEO, NOR Flash) and the Infineon ModusToolbox ecosystem

## Rules

- [Cypress Semiconductor Spectral Rules](rules/cypress-semiconductor-rules.yml) — Rules enforcing API Evangelist conventions for Cypress / Infineon embedded artifacts

## Plans

- [Cypress Semiconductor Plans / Pricing](plans/cypress-semiconductor-plans-pricing.yml) — Free ModusToolbox developer ecosystem bundled with silicon purchase

## Rate Limits

- [Cypress Semiconductor Rate Limits](rate-limits/cypress-semiconductor-rate-limits.yml) — Local SDK / GitHub-hosted; no centralized HTTP API rate limit

## FinOps

- [Cypress Semiconductor FinOps](finops/cypress-semiconductor-finops.yml) — FOCUS-aligned: hardware purchase, not API metering; legal counterparty is Infineon Technologies AG

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
