# Nordic nRF Matter Dual Temperature Sensor

## Development environment

* [Installing the nRF Connect SDK](https://docs.nordicsemi.com/bundle/ncs-latest/page/nrf/installation/install_ncs.html)
* [Installing the toolchain]

## Firmware

To compile the firmware, run the following command in your West environment

```
west build -p -b nrf54l15dk/nrf54l15/cpuapp -- -DFILE_SUFFIX=minewsemi
```

## Firmware

- [*] Implement ADC
- [*] Add two temperature probes
- [*] Basic indicator LED (without DK)
- [ ] Press and hold to reset
- [ ] User labels to name the probes
