# PicoWireless.net Keyboard

Keyboard with 108 keys v1.0

Size: 100%

Controller: AT90USB1286

Last Update: 2019/05


PicoWireless.net (c) 2021

website:

http://www.picowireless.net

store:

http://store.picowireless.net



## Development Team


Nuno Mendes aka nmm aka picowireless

nuno.mendes@picowireless.net


## URL's

Keyboard Layout Editor

http://www.keyboard-layout-editor.com/


Keyboard Firmware Builder

https://kbfirmware.com/


EasyEDA - PCB design

https://easyeda.com/pt


## PCB Connections

### Controller AT90USB1286

#### Rows (#/Pin)

0 	B0 

1 	E4 -> NOT USED

2 	B1

3 	B2

4 	B3

5 	F5

6 	F4


#### Columns (#/Pin)

0 	C5

1 	C6

2 	C7

3 	C4

4 	C3

5 	C2

6 	C1

7 	C0

8 	D7

9 	D6

10 	D5

11 	D4

12 	D3

13 	D2

14 	D1

15 	D0

16 	F7

17 	F6

18 	E2

19 	F0

20 	F1

21 	F2

22 	F3


#### Configure LED pins (led/pin)

Num Lock 		E1

Caps Lock 		E0

Scroll Lock 	B6

Compose 		E5

Kana 			E6

Backlight 		B7

WS2812 Strip	B5



## Components

R1, R2, R3, R4, R5  -> 4x 	Resistência 100R 1/4w

R6, ... R29			-> 23x 	Resistência 470R 1/4w

Led1, Led2, Led3 	-> 3x 	Led Amarelo 3mm

Led4 				-> 1x 	Led Verde 3mm

Led5				-> 5x 	Led Branco 3mm

U1, U2				-> 2x	Chante (jumper) 2 pinos

D91 a D198			-> 108x Diodo 1N4148

S1 a S108			-> 108x Cherry MX Switch

Estabilizadores		-> 5x 	Estabilizadores 2 

Estabilizadores Spc -> 1x 	Estabilizador   6.25

T1					-> 1x 	Controloador Teensy ++2 + Cabo Mini USB Macho to USB A Macho

Hub					-> 1x 	Hub Usb 1x Usb Micro Fêmea (to PC) & 4 portas Usb A Fêmea