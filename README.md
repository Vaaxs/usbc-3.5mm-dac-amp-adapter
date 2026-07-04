# usbc-3.5mm-dac-amp-adapter
Project for Stasis, a DAC amp that is also an adapter, to go from USB-C to 3.5mm.

## How it works

USB-C in → PCM2704CDB DAC → 3.5mm TRS out. The chip enumerates as a standard USB Audio Class device, so there is no firmware or drivers needed.

Specs

| Parameter | Value |
|---|---|
| DAC IC | Texas Instruments PCM2704CDB |
| Package | SSOP-28, 0.65mm pitch |
| USB | Full-speed USB 2.0 via USB-C receptacle |
| Output | 3.5mm TRS (stereo, no mic) |
| Sample rate | Up to 48 kHz, 16-bit |
| Crystal | 12 MHz ABM8-12.000MHZ-12-B1U-T |
| Power | Bus-powered from USB (500mA max) |
| Protection | 500mA polyfuse on VBUS |
| Board size | ~72mm × 22mm |
| Mounting | Two M2 mounting holes |
