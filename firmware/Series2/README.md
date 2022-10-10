 # About Firmware
Firmware files are zipped to make them easier to download.  
The binary file needs to be extracted (unzipped) before attempting to update.
 
 # Firmware Versions
Firmware versions 1.2XXX must be used in all Series 2 WM1's. These were manufactured starting in August 2022.
Series 2 AlcoMeasure's will not work with 1.1XXX firmware.

Series 1 AlcoMeasure's after serial no 400 can be updated with firmware 1.2XXX.
If it is desired to convert the device to use the AS 3547:2019 configuration, this can be done by selecting "Reset STD Items" in the onboard menu after updating the firmware to 1.2XXX.

Please note: For a Series 1 AlcoMeasure to become fully compliant with AS 3547:2019 it must be returned to All-Systems Electronics for a factory upgrade.

 
 # Updating firmware
AlcoMeasure Utility is the preferred option for upgrading the firmware in devices manufactured after 2019.
See the [AlcoMeasure WM1 User Manual](https://github.com/All-Systems-Electronics/AlcoMeasure/tree/master/documentation) for more information

For older devices, the following procedure must be used:
1. Place the relevant firmware file on a SanDisk or other reputable USB stick.  
   The firmware file must keep the original name, be in the root folder of the stick, and should be the only firmware file in the folder.
2. Power off the AlcoMeasure.
3. Insert the USB stick into the Type-A port on the AlcoMeasure processor board.  
   Make sure there is no cable connected to the Mini-B port.
4. Press and hold the "Clear" button on the AlcoMeasure processor board.  
   While holding clear, power on the AlcoMeasure.
5. For AlcoMeasures newer than April 2019, the display will show the status of the update.  
   *  For older devices, the green heartbeat LED on the top left of the processor board indicates status.  
      * A solid green LED, followed by a fast flashing LED indicates that the update has started.
      * Once the LED stops, and just periodically flashes twice, the device update is complete.  
6. The clear button can be released once the firmware update is initiated.
7. Power off the AlcoMeasure.
8. Remove the USB stick.
9. Power on the AlcoMeasure and check its new firmware version. There should also be a log entry indicating that the firmware was updated. 
