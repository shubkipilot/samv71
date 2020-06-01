[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# Supply Controller (SUPC) entering low power mode and exiting using WKUP pin example (supc_wakeup_wkup)

This example demonstrates entering different low power modes and exiting it using the wake up pin.

## Description

This example demonstrates how to use the wakeup pin to wake up the device from low power modes.

## Downloading and building the application

To download or clone this application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_e70_s70_v70_v71) and click

![clone](../../../docs/images/clone.png)

Path of the application within the repository is **apps/supc/supc_wakeup_rtt/firmware** .

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

1. Open the Terminal application (Ex.:Tera term) on the computer
2. Connect to the EDBG Virtual COM port and configure the serial settings as follows:
    - Baud : 115200
    - Data : 8 Bits
    - Parity : None
    - Stop : 1 Bit
    - Flow Control : None
3. Build and Program the application project using its respective IDE
4. On board LED starts blinking
5. See the following message in the console

    ![output_1](images/output_supc_wakeup_wkup_1.png)

6. Select the option to enter the required Low power mode (LED is turned off when device enters a low power mode)
7. Press the switch to exit from low power mode
8. LED starts blinking and the console displays the following message based on the entered low power mode

    ![output_2](images/output_supc_wakeup_wkup_2.png)

Following table lists the name of LED and switch used on the target board

| Board | LED  | Switch |
| ----- | --------- |----- |
| [SAM E70 Xplained Ultra board](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/DM320113)    |LED1 | SW0 |
