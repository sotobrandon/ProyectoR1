# ProyectoR1
## Integrantes 
-Brandon Jesús Soto Rangel
-Miguel Ángel Anastasio Nava
-José Manuel Sánchez Arredondo
-Victor Javier Otero

## Objetivos generales 
El objetivo en general de nuestro proyecto es proteger espacios que no estan seguros o son probables a se inseguros , por lo que proponemos
nuestro proyecto para hacer seguras de esas zonas a las que propenden la inseguridad de algun espacio .
El objetivo general de este proyecto es poder implementar un sistema de riego de cannabis , por lo que se propondra es mantener estas
plantas regadas adecuadamente cada que necesiten agua .
### Objetivos específicos 
- 1.- Planeación de prototipo.
- 2.- Diseñado del prototipo.
- 3.- Validación de prototipo.
- 4.- Prueba de prototipo.
- 5.- Realización de proyecto final.
- 6.- Prueba de proyecto.
- 7.- Liberación de proyecto.
- 7.- Liberación de proyecto. 

## Tabla de software utilizada 
| identificacion | software | Versión | tipo |
@@ -32,30 +33,31 @@ nuestro proyecto para hacer seguras de esas zonas a las que propenden la inseguri
| identificacion | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|------------|--------|-------- - -|------------|
|2.1| Esp32 | Es la denominación de una familia de chips SoC de bajo costo y consumo de energía, con tecnología Wi-Fi y Bluetooth de modo dual integrado. |![imagen](https://user-images.githubusercontent.com/106613839/217649811-9335a9c7-5a4c-4813-8f17-e03488f52967.png)| 1 | $150 |
|2.2| cables | Clabes por los cuales se harán conexiones entre sensores, actuadores y la esp32|![image](https://user-images.githubusercontent.com/106613839/217650692-88574d94-022c-44fe-a183-58dd5121c26a.png)| 20           | $ 20             |
|2.2| cables | Clabes por los cuales se harán conexiones entre sensores, actuadores y la esp32|![image](https://user-images.githubusercontent.com/106613839/217650692-88574d94-022c-44fe-a183-58dd5121c26a.png)| 30           | $ 30             |
|2.3| foco con enchufe | Foco el cual será controlado para iluminar una zona. |![imagen](https://user-images.githubusercontent.com/106613839/217650095-d221a148-1c63-45fc-8211-0f1e97fa8816.png)| 1 | $80 |
|2.4| Sensor PIR | Es un dispositivo de detección de presencia . |![imagen](https://user-images.githubusercontent.com/ 106613839/217650180-a6823830-87e4-4c25-aaa7-666262828d59 .png)| 1     | $ 70             |
|2.4| Sensor de humedad | Cuenta con dos microsensores calibrados en función de la humedad relativa del área o la zona . |![imagen](https://user-images.githubusercontent.com/ 107832766/219272302-4151c8bc-315a-4dc3-9610-5f902f33414e .png)| 2     | $ 57             |
|2.5| Relé de módulo | Es un dispositivo que funciona como un interruptor controlado por un circuito eléctrico. |![imagen](https://user-images.githubusercontent.com/106613839/217650285-e2eb47d3-dd0d-417d-8b56-bc9ed793780a.png)| 1 | $100 |
|2.6| Frambuesa Pi | Consiste en una placa base que soporta distintos componentes de un ordenador como un procesador ARM de hasta 1500 MHz, un chip gráfico y una memoria RAM de hasta 8 GB. Además, tiene otras muchas otras posibilidades. Gracias a sus puertos y entradas, permite conectar dispositivos periféricos. |![imagen](https://user-images.githubusercontent.com/106613839/217650399-cdfdb686-4b04-4740-9ed4-f50115d25a98.png)| 1 | $2750 |
|2.7| zumbadores | Es un pequeño duspositivo capaz de convertir energía eléctrica en sonido. |![imagen](https://user-images.githubusercontent.com/106613839/217650467-74e67b77-a1b1-4a00-9268-57ff7921a149.png)| 1 | $20 |

## Epicas del proyecto (Minimo debe de haber una epica por integrante de equipo) 
- Yo como usuario quiero detectar personas o algunas otras entidades agenas a un cierto espacio .
- Yo como usuario quiero iluminar la zona detectada con precencia de otras ajenas a un cierto espacio .
- Yo como usuario quiero que el dispositivo lance una alarma la cual avisa si se detecta un movimiento .
- Yo como usuario quiero poder almacenar información de las detecciones que se dieron en cada activación del dispositivo .
- Yo como usuario quiero poder consultar las detecciones que se dieron en cada activación del dispositivo .
-Yo como usuario quiero detectar si mi planta de cannabis necesita ser regada .
- Yo como usuario quiero que mi dispositivo riegue la planta cada que lo necesite .
- Yo como usuario quiero que el dispositivo active un sonido de alarma para saber cuando regar la planta .
-Yo como usuario quiero que almacene la información cada vez que se riega la planta .
- Yo como usuario quiero que el dispositivo sepa cuanta agua necesita la planta .

## Tabla de historias de usuario 
| identificacion | historia de usuario | prioridad | Estimación | Como probarlo | responsable |
|----|---------------------|-----------|---------- --|---------------|------------------|
|3.1 | Yo como usuario quiero detectar personas o algunas otras entidades agenas a un cierto espacio . | Alta | 3 meses    | Pasar frente al dispositivo y revisar el celular si llego alguna notificación de la aplicación. | Brandon y José Manuel |
| 3.2 | Yo como usuario quiero iluminar la zona detectada con precencia de otras ajenas a un cierto espacio. | Alta | 3 meses | Pasar frente al dispositivo y ver si enciende el foco.| Brandon y José Manuel |
| 3.3 | Yo como usuario quiero que el dispositivo lance una alarma la cual avisa si se detecta un movimiento . | Alta | 1 mes | Pasar frente al dispositivo y ver si emite un sonido. | Brandon |
| 3.4 | Yo como usuario quiero poder almacenar información de las detecciones que se dieron en cada activación del dispositivo . | Semi-Alta | 1 mes | Checar en el dispositivo el registro de las detecciones. | jose manuel |
| 3.5 | Yo como usuario quiero poder consultar las detecciones que se dieron en cada activación del dispositivo . | Semi-Alta | 1 mes | A través de un dispositivo móvil | Brandon |
|3.1 | Yo como usuario quiero detectar si mi planta de cannabis necesita ser regada . | Alta | 1 mes    | Que el dispositivo se de cuenta cuando la tierra de la planta este seca. | Brandon y José Manuel |
| 3.2 | Yo como usuario quiero que mi dispositivo riegue la planta cada que lo necesite | Alta | 1 mes | El dispositivo permitira el paso del agua hacia la planta. | Miguel Ángel |
| 3.3 | Yo como usuario quiero que el dispositivo active un sonido de alarma para saber cuando regar la planta . | Semi- Alta | 1 mes | Cuando la tierra de la planta este seca ver si hace el sonido. | Víctor |
| 3.4 | Yo como usuario quiero que almacene la información cada vez que se riega la planta . | Semi-Alta | 2 meses | Checar en el dispositivo el registro de las detecciones. | jose manuel y miguel angel |
| 3.5 | Yo como usuario quiero que el dispositivo sepa cuanta agua necesita la planta . | Semi-Alta | 2 meses | A través de un dispositivo móvil | Brandon y Víctor |

## Prototipo en dibujo 
- Coloca la fotografia de tu prototipo dibujado a lapiz

![ imagen ](https://user-images.githubusercontent.com/106613839/217649648-a0f05df6-cb45-4d53-8a51-706120c40393.png)
![ Imagen de WhatsApp 2023-02-16 al 00 53 29 ](https://user-images.githubusercontent.com/107832766/219290535-70bf23d2-de48-4e55-9166-8594278d453b.jpeg)
