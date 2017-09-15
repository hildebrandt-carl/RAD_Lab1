# Team RAD - Lab 1

Advanced Embedded Systems Course

## About

This lab was setting up two wizzimote to send and recieve strings. Wizzimotes provide low-power communication, and will be used in a larger system during the rest of this course. We are using a cc430 microprocessor and a ported version of Contiki. The native version of Contiki is not compatible with the cc430 platform.

### Prerequisites

You will need to install wizzimote-contiki:

```
git clone https://suman2135@bitbucket.org/suman2135/wizzimote-contiki.git
```

Move the libmsp430.so into /usr/lib

Once this is installed you will need multiple packages for compliting and running Contiki. They can be installed using:

```
sudo apt-get install build-essential binutils-msp430 gcc-msp430 msp430-libc msp430mcu mspdebug gcc-arm-none-eabi gdb-arm-none-eabi ant libncurses5-dev
```

## Authors

* **Carl Hildebrandt** - *Initial work* - [hildebrandt-carl](https://github.com/hildebrandt-carl)
* **Member1** - *Initial work* - [rhorzewski](https://github.com/rhorzewski)
* **Mebere2** - *Initial work* - [SilverShadowx](https://github.com/SilverShadowx)


