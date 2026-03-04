# ESP32 + SIM7600 Sensor Board (Coyhaique)

## Descripción del Proyecto

Este repositorio contiene los archivos de diseño de hardware (esquemáticos y placa PCB) diseñados en Autodesk EAGLE para una tarjeta basada en el microcontrolador **ESP32** integrada con el módulo de comunicación **SIM7600**. 

El propósito de esta placa es facilitar la conexión y adquisición de datos de múltiples sensores.

## Características Principales

* **Microcontrolador:** ESP32 (Wi-Fi y Bluetooth integrados).
* **Comunicación Móvil:** Módulo SIM7600 (soporte para 4G/LTE, GPS, etc.).
* **Integración de Sensores:** Diseñado para agregar y leer diversos sensores a través de sus pines de expansión y borneras.
* **Diseño CAD:** Archivos de diseño creados en EAGLE (`.sch`, `.brd` y archivos de fabricación CAM `.job`).

## Contenido del Repositorio

* `Board_760032.sch` / `Board_7600.sch`: Esquemáticos del diseño del circuito.
* `Board_760032.brd` / `Board_7600.brd`: Diseño de la placa de circuito impreso (PCB).
* `*.job`: Archivos en formato CAM Job de EAGLE para la generación de archivos base de manufactura (Archivos Gerber, Taladros, etc).
* Otros respaldos y librerías generadas por la herramienta.

## Autor

**Alejandro Rebolledo**  
* Correo electrónico: [arebolledo@udd.cl](mailto:arebolledo@udd.cl)

## Descargo de Responsabilidad / Disclaimer

Este proyecto y todo el material incluido (código, esquemáticos, diseños de placa PCB y cualquier otra documentación) se proporcionan **"tal cual" ("as is")**, sin garantías de ningún tipo, ya sean expresas o implícitas. Esto incluye, pero no se limita a, las garantías de comerciabilidad, idoneidad para un propósito particular y no infracción. 

El código se ofrece y el usuario utiliza estos diseños o fabricaciones derivadas enteramente **bajo su propio riesgo**. El autor no se hace responsable por ningún daño directo, indirecto, incidental, especial, ejemplar o consecuente (incluyendo la pérdida de datos, daños a equipos u otros daños) que surjan de alguna forma del uso de este proyecto. Asegúrese de revisar minuciosamente y validar los componentes, valores, polaridades y esquemáticos antes de la manufactura o su puesta en marcha.

## Licencia

Este proyecto se distribuye bajo la licencia **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**. 
Puede consultar el texto completo de la licencia en el archivo [LICENSE](LICENSE) incluido en este repositorio o visitar [Creative Commons CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
