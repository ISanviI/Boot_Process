# Boot Process

This includes an image that contains complete information about how booting works in electronic devices.

In simple words, what happens internally when the power on button is pressed before the device UI is visible.

It is as below...
![Booting](/Boot_Process.jpg)

# What happens internally when a C file is compiled and then executed?

### During Compilation
GCC or Clang when used for compilation it uses libraries from **CRT** like *startup files* (crtn.o, crti.o etc), *standard functions* (libc.a libc.so etc), the *entry point address* (from crt1.o --> **_start**) and links these all together using a *linker* (example ld) to compile it to an **ELF** binary file.

Below is the image describing the flow
![Run_C_File](/Run_C_File.jpg)

# Bare Metal vs Hypervisor

When is OS present and when not?
![Device_Structure](/Device_Structure.jpg)