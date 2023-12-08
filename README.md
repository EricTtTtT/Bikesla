# Bikesla
The final project of Embedded-System Lab, NTUEE

# set up
1. Import Program from http://os.mbed.com/teams/mbed-os-examples/code/mbed-os-example-ble-Button/  
2. Update Libraries, mbed-os.6.15.1  
5. copy codes:  
```bash
cd Bikesla
cp source/* MbedFolder/source/  
cp mbed_app.json MbedFolder  
// MbedFolder  
rm -r shields img  
```
6. change mini_printf to std if needs. (in mbed-os/targets/targets.json::19)

# Images
Here are some images related to the project:

### Control Buttons
![Control Buttons](images/control_buttons.png)

### Device Box
![Device Box](images/device_box.png)

### Speed Panel
![Speed Panel](images/speed_panel.png)

### Start Button
![Start](images/start.png)

### Device
![Device](images/device.png)

### Flash LED
![Flash LED](images/flash_led.png)

### Speed Sensor
![Speed Sensor](images/speed_sensor.png)
