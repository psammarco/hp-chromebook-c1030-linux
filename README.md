# Linux on HP Chromebook Elite C1030
The aim of this project is to gather information, patches, and slim the overall kernel configuration down to the bare essentials.

Linux on this device has been made possible by MrChromebox and the Coreboot community. Without their help there would be no audio and no gpu.

###  What's not working
- [ ] [Speaker not recognised](https://github.com/thesofproject/sof/issues/5439)
- [ ] Privacy screen key (require CBI reprogramming)

### Components requiring patching
- [X] [i2c / Touchscreen](https://lore.kernel.org/all/20211220210643.47842-1-pmenzel@molgen.mpg.de/#iZ31Documentation:devicetree:bindings:i2c:i2c.txt)

### Coreboot fixes
- [X] [SMBIOS / sound](https://review.coreboot.org/c/coreboot/+/62796)

### kernel configuration optimizations
- [X] [Hardening](https://kernsec.org/wiki/index.php/Kernel_Self_Protection_Project/Recommended_Settings)
- [ ] Low latency devices 
- [X] General housekeeping
- [ ] [Vivaldi](https://chromium-review.googlesource.com/c/chromiumos/platform/ec/+/2142536)
- [ ] Further trimming
