# Linux on HP Chromebook Elite C1030
The aim of this project is to gather information, patches, and slim down the overall kernel configuration down to the bare essentials.

Linux on this device has been made possible by MrChromebox and the Coreboot community. Without their help there would be no audio and no gpu.

###  What's not working
- [ ] [Speaker not recognised](https://github.com/thesofproject/sof/issues/5439)
- [ ] Privacy screen key (require CBI reprogramming)

### Components requiring patching
- [X] [Touchscreen](https://lore.kernel.org/all/20211220210643.47842-1-pmenzel@molgen.mpg.de/#iZ31Documentation:devicetree:bindings:i2c:i2c.txt)

### Coreboot fixes
- [X] [SMBIOS](https://review.coreboot.org/c/coreboot/+/62796)
