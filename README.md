## USBasp firmware
Latest version of USBasp firmware with TPI support and Green Photon hack for chinese ISP programmers based on ATmega8/48/88.
See [Thomas Fischl's website](https://www.fischl.de/usbasp/) and [Green Photons's blog](https://www.sciencetronics.com/greenphotons/?p=1937) for details.

To build the patched version, just type:
`make main.hrx`
To build original version, just type:
`make -f Makefile.genuine main.hrx`
