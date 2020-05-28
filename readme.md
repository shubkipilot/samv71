﻿[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# Harmony 3 peripheral library application examples for SAM E70/S70/V70/V71 family

MPLAB® Harmony 3 is an extension of the MPLAB® ecosystem for creating embedded firmware solutions for Microchip 32-bit SAM and PIC® microcontroller and microprocessor devices.  Refer to the following links for more information.

- [Microchip 32-bit MCUs](https://www.microchip.com/design-centers/32-bit)
- [Microchip 32-bit MPUs](https://www.microchip.com/design-centers/32-bit-mpus)
- [Microchip MPLAB X IDE](https://www.microchip.com/mplab/mplab-x-ide)
- [Microchip MPLAB® Harmony](https://www.microchip.com/mplab/mplab-harmony)
- [Microchip MPLAB® Harmony Pages](https://microchip-mplab-harmony.github.io/)

This repository contains the MPLAB® Harmony 3 peripheral library application examples for SAM E70/S70/V70/V71 family

- [Release Notes](release_notes.md)
- [MPLAB® Harmony License](mplab_harmony_license.md)

To download or clone these application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71) page and click:

![clone](./docs/images/clone.png)

## Contents Summary

| Folder     | Description                             |
| ---        | ---                                     |
| apps       | Peripheral library example applications |
| docs       | Applications help documentation         |

## Code Examples

The following applications are provided to demonstrate the typical or interesting usage models of one or more peripheral libraries.

| App Name | Description|
|:---------|:-----------|
|[Analog Comparator Controller PWM example (acc_wave_gen)](apps/acc/acc_wav_gen/readme.md) | This application example uses ACC peripheral Library to generate PWM waveform with variable duty cycle|
|[Analog Front-End Controller DMA striding example (afec_dma_striding)](apps/afec/afec_dma_striding/readme.md) | This application example uses AFEC peripheral Library to sample multiple ADC channels using DMA striding|
|[Analog Front-End Controller polling mode example (afec_polled_mode)](apps/afec/afec_polled_mode/readme.md) | This example uses AFEC peripheral library to demonstrate how to sample an analog input in polled mode and send the converted data to console|
|[Analog Front-End Controller user sequencer Example (afec_user_sequence)](apps/afec/afec_user_sequence/readme.md) | This example uses AFEC peripheral library to demonstrate how to sample three analog inputs using the user sequencer in triggered conversion mode and send the converted data to the console|
|[Cache maintenance operations example (cache_maintainenace)](apps/cache/cache_maintenance/readme.md) | This example demonstrates the cache maintenance operation by cleaning and invalidating the cache for the DMA buffers located in the cacheable SRAM region|
|[Clock configurations example (clock_config)](apps/clock/clock_config/readme.md) | This example application demonstrates how to configure the clock system to run the device at maximum frequency|
|||
____

[![License](https://img.shields.io/badge/license-Harmony%20license-orange.svg)](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71/blob/master/mplab_harmony_license.md)
[![Latest release](https://img.shields.io/github/release/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71.svg)](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71/releases/latest)
[![Latest release date](https://img.shields.io/github/release-date/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71.svg)](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71/releases/latest)
[![Commit activity](https://img.shields.io/github/commit-activity/y/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71.svg)](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71/graphs/commit-activity)
[![Contributors](https://img.shields.io/github/contributors-anon/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71.svg)]()

____

[![Follow us on Youtube](https://img.shields.io/badge/Youtube-Follow%20us%20on%20Youtube-red.svg)](https://www.youtube.com/user/MicrochipTechnology)
[![Follow us on LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20us%20on%20LinkedIn-blue.svg)](https://www.linkedin.com/company/microchip-technology)
[![Follow us on Facebook](https://img.shields.io/badge/Facebook-Follow%20us%20on%20Facebook-blue.svg)](https://www.facebook.com/microchiptechnology/)
[![Follow us on Twitter](https://img.shields.io/twitter/follow/MicrochipTech.svg?style=social)](https://twitter.com/MicrochipTech)

[![](https://img.shields.io/github/stars/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71.svg?style=social)]()
[![](https://img.shields.io/github/watchers/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71.svg?style=social)]()
