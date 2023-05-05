# Arduino Bluetooth RC Car

Este proyecto es un código de ejemplo para controlar dos motores utilizando el control serial de Arduino y añadiendo un módulo Bluetooth HC-05 o HC-06. El usuario puede enviar comandos desde la aplicación "Arduino Bluetooth RC Car" para controlar el movimiento de un robot(carrito). El código se encarga de interpretar los comandos recibidos por Bluetooth y controlar los motores en consecuencia.

## Cómo usar el proyecto

1. Conecta los pines del controlador de motores L293B a los pines de entrada y salida definidos en el código.
2. Conecta el módulo Bluetooth HC-05 o HC-06 a los pines TX y RX de la placa Arduino, y alimenta el módulo Bluetooth con una fuente de alimentación externa o a través del pin Vcc de la placa Arduino (asegúrate de que la alimentación sea compatible con el módulo Bluetooth que estás utilizando).
3. Carga el código en tu placa Arduino.
4. Empareja el módulo Bluetooth con tu dispositivo móvil a través de la configuración Bluetooth del dispositivo.
5. Abre la aplicación "Arduino Bluetooth RC Car" en tu dispositivo móvil y selecciona el dispositivo Bluetooth emparejado.
6. Usa la aplicación para enviar comandos y controlar el movimiento del robot.

## Archivos incluidos

- `control_motores_bluetooth.ino`: el código principal del proyecto, que incluye la funcionalidad Bluetooth.

## Autores

- Grupo #3
