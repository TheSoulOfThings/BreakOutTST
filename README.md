# BreakOutTST
BreakOut TST - Sigfox

Para la comunicación del breakout es necesario utilizar un microcontrolador o tarjeta de desarrrollo (arduino, pic, raspberry, etc), para la comunicación se puede utilizar el serialbridge que esta en la carpeta y configurarlo segun el arduino.
se debe tener encuenta que los pines a utilizar son GND, Vin (3.3 v) , TX y RX. 
Para la comunicación con el arduino el Tx del breakout va conectado al Rx del arduino y el Rx del breakout al Tx del arduino.
Paso siguiente se puede utilizar el software "EXE_SFM10R_AT_TEST_v13"  incluido en el repositorio y seguir el manual de usuario de soul one https://github.com/TheSoulOfThings/SoulOne/blob/master/Munual%20de%20usuario%20Soul%20One%20v.2.0.pdf
Cualquier duda comunicarse con gerencia@tsthings.com
