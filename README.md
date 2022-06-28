# Csma-cd-protocol-gui

Código implementado en el lenguaje Python que simula una red LAN para mostrar el desempeño y el ancho de banda (en Mbps) del protocol CSMA/CD persistente y no persistente. A través de una interfáz gráfica se pueden revisar cada una de las variables obtenidas en la simulación y se generan reportes con estos datos. Este codigo fue implementado usando el siguiente algoritmo como codigo base: [thanujann - CSMA/CD Protocol Simulator](https://github.com/thanujann/CSMA-CD-Protocol-Simulator)

## Mejora en el codigo base

Haciendo uso de hilos en el lenguaje, la libreria Tkinter y la libreria MathPlotLib se realizó una muestra en tiempo real de como se ejecuta el protocolo en el codigo base y a medida que se obtienen los datos de cada host se pueden revisar graficos para entender mejor el comportamiento del simulador.


## Instalacion de librerias

Para instalar las librerias necesarias para la correcta ejecución del codigo ejecute el siguiente comando:

`$ pip install -r requirements.txt` o `$ pip3 install -r requirements.txt` 

## Ejecución del simulador

Una vez instaladas las librerias necesarias para ejecutar el codigo implementado se debe usar el siguiente comando:

`python app.py` o `python3 app.py`