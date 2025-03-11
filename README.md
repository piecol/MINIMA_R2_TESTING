# MINIMA_R2_TESTING

## 1. Install the CM5
![BOTTOM](https://github.com/user-attachments/assets/60494fc7-2574-42d5-9d8c-7e5b62b9094a)

## 2. nRPIBOOT
If flashing of OS is required, set the nRPIBOOT microswitch according to the label.
If the CM5 is already flashed with OS, reset the switch to opposite side.
![nRPIBOOT](https://github.com/user-attachments/assets/4bc92f91-fb2c-4bff-8013-3b35c0da66d9)

## 3. Top view of the MINIMA R2 board
![TOP](https://github.com/user-attachments/assets/51ba81de-5662-43ef-aea4-b668e7ca048b)

## USB2.0
For easy interaction with the OS, insert an USB-C adapter to install the dongle for mouse and keyboard.
Please note that the latest Raspberry Pi OS supports the pairing of bluetooth mouse and keybord at the first boot, so the dongle might not be needed.
![MOUSE_KEYBOARD_DONGLE](https://github.com/user-attachments/assets/29881437-bda7-46c8-a738-f751389eb756)

## 4. Fan cable
For testing the fan, just connect the cable. Be sure that the polarity of the wires corresponds to the lable:
"T-P+"
T: tacho
-: GDN
P: PWM
+: VCC
![20240115_014444](https://github.com/user-attachments/assets/302a785b-1fc1-422d-ab77-5817c00dd633)

## 5. SSD
If testing of SSD is required, intall an "M" key 2230 unit, and secure it with a M2 screw.
Some operations are required to flash/mount the SSD, please refer to this guide:

https://www.waveshare.com/wiki/Compute_Module_5_IO_Board#Mount

![20240115_014504](https://github.com/user-attachments/assets/bf5a809a-c4e0-4cfe-a8ca-1d0c2c703480)
![20240115_014526](https://github.com/user-attachments/assets/4e64c892-0fde-4393-a0d0-baf07d4e1b57)

## 6. Camera
For camera testing, please install an official Raspberry Pi V3 camera module according to the pictures.
Drivers should be already present in the latest OS, for further info about camera interfacing, please refer to following guides:

https://www.waveshare.com/wiki/Compute_Module_5_IO_Board#CSI

https://forums.raspberrypi.com/viewtopic.php?t=382380

![20240115_014557](https://github.com/user-attachments/assets/48e39da2-a4b6-4b17-b0a0-8727243eebf9)
![20240115_014621](https://github.com/user-attachments/assets/aeeb97bc-b582-4d8e-aa3b-7c9c50eee080)

## 7. HDMI
Connect a screen with a HDMI cable.
![20240115_014905](https://github.com/user-attachments/assets/0a3b81ee-099c-4183-80b2-28e03589295a)

## 8. Powering the system
Power up the system by inserting a USB-C cable in the USB-PD labelled port. Ensure that your power supply is capable of delivering sufficient energy to the system.
The CM5 should start right away, without the need to push the PWR button. The two LEDs labelled "PWR" and "ACT" will firstly stay ON, and afterwards start blinkinig. The ACT LED will blink as a result of interan operation.
The OS starts showing the Desktop. Test mouse and keyboard for correct functioning.
![20240115_014944](https://github.com/user-attachments/assets/583baedc-8a3b-42cd-b3a5-399fc5a99975)
![20240115_015003](https://github.com/user-attachments/assets/916d0214-3095-48e6-a1af-0a7429a659b2)
![20240115_015104](https://github.com/user-attachments/assets/e1a9bf88-d843-4ade-b0bb-9a779284d80a)

## 9. Switch OFF with the PWR button
A pop-up will appear after pushing the PWR button, showing three options:

- Shutdown
- Reboot
- Log-out

If PWR button is pressed for some seconds, the system will shut down automatically.
![20240115_015123](https://github.com/user-attachments/assets/ca0b70e2-a3dd-4f83-ba0d-8b24d386f9ff)
![20240115_015138](https://github.com/user-attachments/assets/743f5190-cf4d-4ad1-a92e-8d4dae48b2f0)

## Power consumption
If the microswitch on the bottom side is set to the nRPIBOOT position for flashing of the OS, power consumption is about 0.035A.
If the switch is not set to the nRPIBOOT position, the OS will start, with a power consumption of about 2.5/3.5A, depending on the tasks the CM5 is performing.
![20240115_015404](https://github.com/user-attachments/assets/4edc339b-6c62-4442-9904-15058cbdf34d)
![20240115_015457](https://github.com/user-attachments/assets/3c87073c-5437-4204-b376-1ad07c62f4ee)
