# Flashing Klipper to the Raspberry Pi

For the most part, this guide reflects the official documentation for flashing Klipper to the Raspberry Pi. The official documentation can be found [here](https://docs-os.mainsail.xyz/getting-started/raspberry-pi-os-based).

1. Download the latest version of the Raspberry Pi Imager from the official website: [Raspberry Pi Imager](https://www.raspberrypi.com/software/) and install it on your computer.
2. Insert the microSD card into your computer.
3. Open the Raspberry Pi Imager and select the "Choose OS" option.
4. Aelect "Other specific-purpose OS" -> "3D Printing" -> "Mainsail OS".
5. Select the microSD card as the storage location and click "Write".
6. Once the flashing process is complete, safely eject the microSD card from your computer.
7. Insert the microSD card into the Raspberry Pi and power it on.
8. Connect to the Raspberry Pi via SSH to update the `printer.cfg` using the settings specified during the flashing process. The default username is "pi" and the default password is "raspberry".
