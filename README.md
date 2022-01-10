# Installing QMK on Royal Kludge RK 837 (G68)
This guide will walk you through on installing QMK on a Royal Kludge RK 837 RGB keyboard. Even though repos exist for other models and the white backlit version, this guide will only cover the RK 837 model with a SN32F24x MCU.

**There is a small chance that you may brick your keyboard in the flashing process, continue at your own risk. Use an appropriate cable, make sure you won’t lose power during flashing and follow the steps carefully.**

**SonixQMK in its current incarnation does not support Bluetooth or very fancy RGB effects and flashing your keyboard will disable the bluetooth entirely.**

This guide will have instructions to build and flash SonixQMK on RK 837.

I have not tried reverting to the original firmware after flashing SonixQMK, so this guide may be a one way road - Try it at your own risk.

This guide assumes that you have the stock bootloader and not Sonix Jumploader.

#TODO
1. Clone a rk61 port and analyze
2. Analyze RK68 matrix
