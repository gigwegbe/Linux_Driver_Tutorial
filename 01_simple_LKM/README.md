To compile the script:
`make`

To run the kernel: 
`sudo insmod mymodule.ko`

To verify the kernel is running: 
`lsmod`

To verify the kernel is running: 
`lsmod | grep mymodule`

To check the log from the kernel:
`dmesg | tail`

To remove the kernel:
`sudo rmmod mymodule`