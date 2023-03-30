# ISP4520-Zephyr-Examples
Zephyr implementation of LoRa and LoRaWan examples using ISP4520 

## Overview

This project show how to use Zephyr implmentation of LoRA/LoRaWAN on a ISP4520 module.
The examples are configured for the EU variant of the ISP4520 module.

## Getting started

Before getting started, make sure you have a proper nRF Connect SDK development environment.
Follow the official
[Getting started guide](https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/getting_started.html).

Then initialize the workspace:

```shell
west init -m https://github.com/insightsip/ISP4520-Zephyr-Examples.git --mr main my-workspace
cd my-workspace
west update
```

Build the example, for example the class_a:

```shell
cd class_a
west build -b nrf52dk_nrf52832
```

Flash the device:

```shell
west flash
```