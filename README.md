# tec-iDADmm
tec1 MINT running a digital to analog to digital repeating loop to speed calculations, eg matrix multiplication

- integer 8x8 DAC/ADC to matrix multiply 
- 8 bytes drive 8 DACs to drive 8 bias voltages into an 8x8 transistor matrix cct (88T)
- the 88T amplifies and sums the currents to derive 8 new voltages that represent and 8x8 matrix multiplication 
- then decoded into 8 ADC to get 8 bytes 
- this accomplishes a crude 8x8 matrix multiplication using analog current/voltage/resistor network


## Ref
- https://www.youtube.com/watch?v=GVsUOuSjvcg
- 
