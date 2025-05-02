PIC18-F45K50-DevKit / Mini-USB
===================================
Basic USB Type-B DevKit I made to learn about **PIC18F45K50** microcontroller.

![overview](https://github.com/thetrung/F45K50_Devkit/blob/master/Images/Sch_DevKit_PIC18F.png)

- **PIC18F45K50-I/MV** will be used specifically as UQFN-40(5x5) instead DIP-40 package in previous THT version.

I actually tried to put all SMD components on front side only. Used Mini-USB instead of USB-B in previous THT version. So this isn't optimized by any mean, just simply a practice to experience what SMD PCB Design look like & what challenge compare to THT ? Although initial goal was same size to a DIP-40. But Port hints are so valuable to remove.


### 1. Basic functionality :
- USB-powered 5V supply.
- USB-HID controllable with PIC18F45k50 with D+/D- pins.
- Reset Button -> Trigger MLCR-pin pull-down -> GND.
- Programming/Debugging with PICKIT-3 via ICSP pins.
- 5 pluggable PORTS : RA, RB, RC, RD, RE.
- LED at RD0 for Blink Test.

![front](https://github.com/thetrung/F45K50_Devkit/blob/master/Images/3D_View.png)
![back](https://github.com/thetrung/F45K50_Devkit/blob/master/Images/Back.png)

### NOTE :
- Fixed critical issues on MCLR pin, Reset Button, ICSP..
- Should only take this design as references to parts.
- No longer update/fix bugs anymore as I move-on to new designs ( with less flaws ).
  
