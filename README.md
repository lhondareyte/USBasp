## USBasp firmware
Latest version of USBasp firmware with TPI support and Green Photon hack for chinese ISP programmers based on ATmega8/48/88.

See [Thomas Fischl's website](https://www.fischl.de/usbasp/) and [Green Photons's blog](https://www.sciencetronics.com/greenphotons/?p=1937) for details.


### Build
Make sure you have avr-gcc toolchain installed. To build the patched version, just type:

`make main.hex`

To build original version, just type:

`make -f Makefile.genuine main.hex`
