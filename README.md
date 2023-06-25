# WriteOS
A small Linux OS for writing things down

## HOW TO INSTALL

### Requirements
An 64 bit Intel or AMD Processor
Intel, AMD, or Nvidia graphics card [NOTE: INTEL AND NVIDIA GRAPHICS ARE UNTESTED CURRENTLY]
Secure boot turned off
Another linux distro with the grub bootloader installed

Get the ISO image or zip file. Then, flash it to an ext-4 formatted partition on your storage device.
Run the command `sudo update-grub`. Make sure that os prober is on. Next, use a text editor and add the parameters `ro nomodeset` to the linux boot command.
