[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# Quad Serial Peripheral Interface (QSPI) flash read write example (qspi_read_write)

This example application demonstrates how to use the QSPI Peripheral library to perform erase, write and read operation with the QSPI Serial Flash memory in Quad IO mode.

## Description

This example uses the QSPI peripheral library to erase and write an array of values to the QSPI Serial Flash memory. It verifies the value written by reading the values back and comparing it to the value written.

## Downloading and building the application

To download or clone this application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71) and click

![clone](../../../docs/images/clone.png)

Path of the application within the repository is **apps/qspi/qspi_read_write/firmware** .

To build the application, refer to the following table and open the project in their respective IDEs.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| sam_e70_xult.X    | MPLABX Project for [SAM E70 Xplained Ultra board](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/DM320113)|     |

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
|sam_e70_xult.X|[![sam_e70_xult](https://www.microchip.com/_ImagedCopy/180730-MCU32-PHOTO-DM320113-Angle-7x5.jpg)](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/DM320113)|

### Setting up [SAM E70 Xplained Ultra board](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/DM320113)

- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and Program the application using its respective IDE
2. LED indicates success or failure:
    - The LED is toggled when the value read from the QSPI Serial Flash memory matched with the written value
    - The LED is turned ON when the value read from the QSPI Serial Flash did not match with the written value

The following table provides the LED name

| Board      | LED name |
| ----------------- | ---------------------------------------------- |
| [SAM E70 Xplained Ultra board](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/DM320113)    | LED1 |


