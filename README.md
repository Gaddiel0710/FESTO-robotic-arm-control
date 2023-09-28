# FESTO-robotic-arm-control
##_control of a FESTO robotic arm for organizing containers on a base_

Objetivo: controlar un brazo robotico festo mediante el uso de software destinado Festo Robocim

## Materials
- Software festo Robocim
- Festo robotic arm
- three bottles
- reception structure

## Control code
```Arduino
001 | SPEED 30
002 | INPUT(1) HIGH
003 | GRIP 60
004 | DELAY 2
005 | MOVETO ORIGEN_A
006 | DELAY 2
007 | GRIP 30
008 | DELAY 2
009 | MOVETO PASO_1A
010 | DELAY 2
011 | MOVETO ORDEN_A
012 | DELAY 2
013 | MOVETO ENTRA_A
014 | DELAY 2
015 | GRIP 45
016 | DELAY 2
017 | MOVETO PASO_1A
018 | DELAY 2
019 | MOVETO PAUSA
020 | DELAY 2
021 | INPUT(2) HIGH
022 | GRIP 60
023 | DELAY 2
024 | MOVETO ORIGEN_B
025 | DELAY 2
026 | GRIP 30
027 | DELAY 2
028 | MOVETO PASO_1B
029 | DELAY 2
030 | MOVETO ORDEN_B
031 | DELAY 2
032 | MOVETO ENTRA_B
033 | DELAY 2
034 | GRIP 45
035 | DELAY 2
036 | MOVETO PASO_1B
037 | DELAY 2
038 | MOVETO PAUSA
039 | DELAY 2
040 | INPUT(3) HIGH
041 | GRIP 60
042 | DELAY 2
043 | MOVETO ORIGEN_C
044 | DELAY 2
045 | GRIP 30
046 | DELAY 2
047 | MOVETO PASO_1C
048 | DELAY 2
049 | MOVETO ORDEN_C
050 | DELAY 2
051 | MOVETO ENTRA_C
052 | DELAY 2
053 | GRIP 45
054 | DELAY 2
055 | MOVETO PASO_1C
056 | DELAY 2
057 | MOVETO PAUSA
058 | DELAY 2
059 | HOME
060 | END
```

## simulation in robocim software
_vista completa del simulador del brazo robotico_
[![Captura-de-pantalla-168.png](https://i.postimg.cc/Vv6WfLQS/Captura-de-pantalla-168.png)](https://postimg.cc/34sv9hw7)

_vista en todos los ejes del simulador del brazo robotico_
[![image2.png](https://i.postimg.cc/FRmfm9kj/image2.png)](https://postimg.cc/VSGsWPR6)


## video of the practice carried out physically
_video final de la practica llevada a fisico_

https://github.com/Gaddiel0710/FESTO-robotic-arm-control/assets/135661300/c4a121f6-21d0-4fb9-818b-18f538a2204e

