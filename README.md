RepRap Firmware LPC/STM32F4 Port unified build
==================================

This repository contains the build system for the LPC and STM32F4 port of RRF V3.2 and later.

To build RRF you will require additional repositories. These should be cloned into the RRFBuild directory. To create a specific version of RRF please checkout the various branches using the associated tags.
* RepRapFirmware - the main RRF source code https://github.com/gloomyandy/RepRapFirmware/tree/v3.02-dev-unified
* RRFLibraries - Support libraries for RRF https://github.com/gloomyandy/RRFLibraries/tree/v3.02-dev-unified
* CoreLPC - MCU specific support for LPC builds https://github.com/gloomyandy/CoreLPC/tree/v3.02-dev-unified
* CoreSTM32F4 - MCU specific support for STM32F4 builds https://github.com/gloomyandy/CoreSTM32F4
* FreeRTOS - RTOS support package https://github.com/gloomyandy/FreeRTOS
* DuetWifiSocketServer - WiFi interface https://github.com/gloomyandy/DuetWiFiSocketServer

