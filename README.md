# Linux Driver Tutorial

Here you can find examples for simple Linux Kernel Modules and Linux Drivers.

## Preparation

I used a Raspberry Pi 3 to develop and test my modules and drivers. To compile them, you need to install the Kernel headers on your Pi. On Raspbian you can do this with the following command:

```bash
sudo apt update
sudo apt install raspberrypi-kernel-headers
```

Raspberry Pi OS is only installs the latest kernel headers. So, make sure, you are running the latest kernel. You can do this by running: 

```bash
sudo apt upgrade
```

You also need the build utils (make, gcc, ...) but they come preinstalled on Raspbian.

## Content

In this repo you can find examples for:
- [x] Simple Kernel Module
1. Device Numbers and Device Files
2. Create device file in driver and callbacks
3. GPIO Driver
4. Text LCD Driver
5. PWM Module
6. Temperature Sensor (I2C)
7. Timer in Linux Kernel Modules
8. High Resolution Timer in Linux Kernel Modules
9.  Accessing SPI with a Linux Kernel Module (BMP280 sensor again)
10. Using a GPIO Interrupt in a Linux Kernel Module
11. Using Parameters in a Linux Kernel Module
12. IOCTL in a Linux Kernel Module
13. Threads in a Linux Kernel Module
14. Sending a signal from a Linux Kernel Module to an userspace application
15. The poll callback
16. Waitqueues in a Linux Kernel Module
17. Create procfs entries from a Linux Kernel Module
18. Create sysfs entries from a Linux Kernel Module
19. Parse the device tree from a Linux Kernel Module to get the deivce properties of a specific device
20. Device Tree GPIO Driver 
21. Device Tree Driver for I2C Device
22. Dynamical memory management in a Linux Kernel module
23. Serial (UART) Driver
24. Industrial IO compatible driver for an ATMEGA I2C ADC
25. Device Tree SPI Driver (IIO compatible driver for Atmega SPI ADC)
26. Misc Device
27. Mutex for exclusive access to shared resource
28. Completions for synchronisation
29. Direct Memory Access (DMA) memcopy example
30. Accessing files form a Linux Driver
31. The mmap callback
32. Linked Lists
33. Registering device numbers, read and write callback in character devices Take 2
34. Private Data in struct file
35. I2C Device Driver without Device Tree 


## More Information

For more information about my Linux Driver examples check out my [videos and my playlist](https://www.youtube.com/watch?v=x1Y203vH-Dc&list=PLCGpd0Do5-I3b5TtyqeF1UdyD4C-S-dMa)

## Support me

If you want to support me, you can buy me a coffee [buymeacoffee.com/johannes4linux](https://www.buymeacoffee.com/johannes4linux).
