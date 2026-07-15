# ProMicro-E22-22dBm
A PCB for nRF52840 promicro using Ebyte E22-xxxM22S 22dBm modules

As with a lot of my boards, the extra components are optional. Reset button and 2x 1M ohm 1206 (R1/R2) resistors recomended at minimum.
A hardware low voltage reset IC was included in the design but never tested.

Compatible modules are:
* E22-170M22S SX1262 150MHz to 170MHz (works great at 173MHz)
* E22-400M22S SX1268 410MHz to 493MHz
* E22-900M22S SX1262 850MHz to 930MHz (works with MeshCore faketec firmware)

The production folder contains a .zip file suitable for PCB production (JLCPCB etc.)