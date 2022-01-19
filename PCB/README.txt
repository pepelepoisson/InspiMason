The PCB for this project is a reuse of a previous project WITH A CHANGE AND A CORRECTION.

REf: https://github.com/pepelepoisson/CroqueLivresSaint2021/tree/main/PCB/CroqueLivreSaintGerard2021_V1

CHANGES TO BE MADE: 
(1) Must connect WS2812B_DATA_IN to D4 (pin 11) rather than D1 (pin 14)
(2) Must connect epaper RST pin to D1 (pin 14) rather than D4 (pin 11). Failing to do this swap with create a boot problem (at least with the library/code I tried)
(3) The orientation of D1 diode is wrong on the PCB silk-screen. Must solder it in reverse! 
