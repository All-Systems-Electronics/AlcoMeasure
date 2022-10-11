 # About Firmware
Firmware files are zipped to make them easier to download.  
The binary file needs to be extracted (unzipped) before attempting to update.
 
 # Firmware Versions
Firmware versions 1.1XXX should be used in all new devices.  
Firmware versions 1.08XX should only be used for devices with serial numbers less than 400.
 
 # Updating firmware

See the [AlcoMeasure WM1 User Manual](https://github.com/All-Systems-Electronics/AlcoMeasure/tree/master/documentation) for more information

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
