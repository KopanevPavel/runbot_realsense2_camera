# Notes

## Start several cameras

```sh
roslaunch realsense2_camera rs_camera.launch camera:=cam_1 serial_no:=<serial number of the first camera>
roslaunch realsense2_camera rs_camera.launch camera:=cam_2 serial_no:=<serial number of the second camera>
...
```

### Serial numbers:

To check:
```sh
rs-enumerate-devices
```

Current:

    Name                          : 	Intel RealSense D435
    Serial Number                 : 	920312071661
    Firmware Version              : 	05.12.07.100
    Recommended Firmware Version  : 	05.12.07.100
    Physical Port                 : 	/sys/devices/pci0000:00/0000:00:14.0/usb2/2-3/2-3.2/2-3.2:1.0/video4linux/video0
    Debug Op Code                 : 	15
    Advanced Mode                 : 	YES
    Product Id                    : 	0B07
    Camera Locked                 : 	YES
    Usb Type Descriptor           : 	3.2
    Product Line                  : 	D400
    Asic Serial Number            : 	923123022841
    Firmware Update Id            : 	923123022841

    Name                          : 	Intel RealSense D435
    Serial Number                 : 	944122074449
    Firmware Version              : 	05.11.01.100
    Recommended Firmware Version  : 	05.12.07.100
    Physical Port                 : 	/sys/devices/pci0000:00/0000:00:14.0/usb2/2-3/2-3.3/2-3.3:1.0/video4linux/video6
    Debug Op Code                 : 	15
    Advanced Mode                 : 	YES
    Product Id                    : 	0B07
    Camera Locked                 : 	YES
    Usb Type Descriptor           : 	3.2
    Product Line                  : 	D400
    Asic Serial Number            : 	939423021873
    Firmware Update Id            : 	939423021873

    Name                          : 	Intel RealSense T265
    Serial Number                 : 	21322110312
    Firmware Version              : 	0.2.0.951
    Physical Port                 : 	2-4-8
    Product Id                    : 	0B37
    Usb Type Descriptor           : 	3.1
    Product Line                  : 	T200

    Name                          : 	Intel RealSense T265
    Serial Number                 : 	21322110467
    Firmware Version              : 	0.2.0.951
    Physical Port                 : 	2-2-7
    Product Id                    : 	0B37
    Usb Type Descriptor           : 	3.1
    Product Line                  : 	T200













