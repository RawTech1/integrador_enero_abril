# Universidad Politécnica de Juventino Rosas
![screen](https://github.com/RawTech1/integrador_enero_abril/blob/main/WhatsApp%20Image%202023-08-01%20at%201.56.03%20PM%20(2).jpeg)
## KATSI-Hardware
### Presenta:
1. *Daniel Castro Reyes*
2. *Cristian Jesús Ortiz Pineda*
3. *Ramses Alejandro Ramos Guerrero*
## Asesor:
### Dr. Juan Israel Yañez Vargas
### M.C Victor Lauro García Pérez
#### Santa Cruz de Juventino Rosas, Gto.
## **Contenido**
 *   [Introducción](#Introducción)
 *   [Motivación](#Motivación)
 *   [Planteamiento_del_problema](#Planteamiento_del_problema)
 *   [Justificación](#Justificación)
 *   [Objetivo_general](#Objetivo_general)
 *   [Objetivos_particuales](#Objetivos_particuales)
# Resumen:
#### El presente documento tiene como objetivo presentar la idea principal del proyecto KATSIs, que se basa en el proyecto RIO para su desarrollo y evolución. Busca mejorar el software y crear un ambiente digital accesible para los administradores. El proyecto se centra en diseñar una interfaz para visualizar, procesar, controlar y almacenar datos de texto obtenidos por sensores en un prototipo para invernaderos. Estos sensores monitorearán la flora y captarán imágenes de los cambios en las plantas. Los datos se almacenarán en una base de datos relacionada con la interfaz para controlar la producción y el riego, así como detectar plagas.
# Introducción
#### En este capítulo será agregada la motivación del proyecto, así como la problemática que se busca resolver y la razón por la cual se busca dar una solución a la problemática, así como el objetivo general y los objetivos particulares del proyecto.
## **Motivación**
![screen](https://github.com/RawTech1/integrador_enero_abril/blob/main/Diagrama%20Motivacion.png)
#### Se realiza una descripción gráfica de la motivación y meta a seguir, este proyecto se enfoca en ayudar a la sociedad, en buscar un bien común y facilitar labores con un sistema de monitoreo, control y adquisición de información de un invernadero, más contar con una interfaz tecnológica fácil de usar y controlar para cualquier usuario que la adquiera. Representa la búsqueda de objetivos y puntos a lograr partiendo desde el interior del invernadero, lugar que se espera lograr que pueda ser monitoreado por un usuario a distancia, a través de las mediciones y valores que proporcionen los sensores utilizados hacia la interfaz donde el usuario puede visualizar estos valores. A partir de módulos XBEE se transmitirán las mediciones de los sensores, estás podrán ser visualizadas a través de la interfaz y además de lograr almacenar las variables dentro de una base de datos que pueda mostrar los datos almacenados a través de la interfaz en modo de datos y estadísticas y a partir de esto llevar un seguimiento del interior del invernadero.
## Planteamiento del problema 
#### La perdida y desperdicio de agua en cultivos de invernaderos podría evitarse creando un sistema de automatización, medición, análisis y control que pueda administrarse y  realizar consultas de información almacenada dentro de una interfaz.
## Justificación
#### Al implementar el proyecto se busca encontrar una solución y apoyo al problema de desperdicio de agua en el riego de cultivos en invernaderos, en donde la implementación de hardware propone realizar un sistema automatizado de riego mediante la recopilación de datos de sensores de humedad, temperatura y PH, y todos los datos sean almacenados en una interfaz desarrollada en python por el equipo que busque generar la automatización de invernaderos a un nivel más accesible para un usuario o administrador que busque consultar y monitorear los cambios y datos almacenados de cada cierto tiempo.
## Objetivo general
#### Diseñar y desarrollar un sistema embebido para adquisición, monitoreo, control y envío a distancia de datos de invernadero y sean visualizados en una interfaz desarrollada en python para el procesamiento, control y almacenamiento de datos.
## Objetivos partículares 
* Realizar un análisis de requerimientos a partir del uso del sistema de adquisición de datos.
* Desarrollo de un sistema de control de invernadero a partir de un sensor de humedad del suelo y del ambiente.
* Ejecutar mediciones de temperatura dentro del invernadero, así como en el exterior.
* Comparar el márgen de error que existe entre cada uno de los sensores utilizados.
* Registrar las mediciones obtenidas y representar mediante gráficas.
* Incorporar mecanismos de automatización para el control de motores mediante condiciones de temperatura.
* Anexar sensores de CO para monitorear la calidad del aire dentro del invernadero.
* Crear una topología utilizando la tecnología de XBee.
* Desarrollar una red de sensores para el monitoreo del invernadero.
* Realizar diversas pruebas para obtener datos más precisos en cuanto a mediciones y distancia entre las XBee.
# Marco Teórico
## Sistema embebido
#### Es un sistema de computacion diseñado para realizar funciones específicas, y cuyos componentes se encuentran integrados en una placa base.
![screen](https://github.com/RawTech1/integrador_enero_abril/blob/main/sistema.jpg)
## Microcontrolador
#### Un Microcontrolador es un circuito integrado que incluye sistemas para controlar elementos de entrada/salida. Incluye un procesador y una memoria que puede guardar el programa y sus variables (flash y RAM) para posteriormente ejecutar las instrucciones almacenadas en su memoria. Su funcion es la de automatizar procesos y procesar información.
![screen](https://github.com/RawTech1/integrador_enero_abril/blob/main/microcontrolador1.png)
## Sensor LM35
#### LM35 es un sensor de temperatura analogico permite medir temperatura en un rango desde -55oC hasta 150oC. Su salida es de tipo analogica y lineal con una pendiente de 10mV/oC.
![screen](https://github.com/RawTech1/integrador_enero_abril/blob/main/LM352.jpg)
## Sensor CCS811
#### El sensor de calidad de aire CCS811 es un sensor de detector de gas digital de muy baja potencia que incorpora un sensor de gas de oxido metálico para identificar una amplia gama de Compuestos Organicos Volátiles (COV) para el monitoreo de la calidad del aire con un microcontrolador que proporciona un ADC y una interfaz I2C.
![screen](https://github.com/RawTech1/integrador_enero_abril/blob/main/ccs811-arduino-code-1200x1199.jpg)
## Módulos Xbee
#### XBee es el nombre comercial del Digi de una familia de módulos de comunicación por radio y están basados en el estándar Zigbee, pero Digi tiene muchos Xbee y algunos son Zigbee estándar y otros son propietarios o modificaciones del estándar. Existen muchos módulos Xbee basados en el estándar IEEE 802.15.4
![screen](https://github.com/RawTech1/integrador_enero_abril/blob/main/modulo.jpeg)
## Análisis FODA
>[!NOTE]
>
>This is a standard NOTE block.

>[!Fortalezas]
>
> * Crecimiento en el area de la electrónica para futuros proyectos aplicados en invernaderos sustentables.
> * Independencia en el desarrollo de las tarjetas electrónicas para su libre patente.
> * Adaptabilidad para cumplir con los requerimientos solicitados, dentro de los invernaderos.
> * Calidad en el prodcuto
> * Crecimiento en el desarrollo de nuevas tecnologías para la competitividad.

>[!Oportunidades]
> * Crecimiento inteligente del sector agrícola y sostenible con el medio ambiente.
> * Comercialización de productos tecnológicos a consumidores del sector agrícola.
> * Integración con tecnologías de control remoto.
> * Colaboración con otros sectores.
> * Aplicación de energías renovables para el suministro eléctrico.

>[!Debilidades]
> * Limitaciones en el hardware en comparación con otras tecnologías.
> * Consumo de energía con respecto a la aplicación de nuevos componentes.
> * Falta de precisión en los sensores para la medición de variables ambientes.
> * Deficiencia en el mantenimiento del invernadero por falta de herramientas.
> * Falta de servicios debido a la ubicación del invernadero.

>[!Amenazas]
> * Entorno peligroso al encontrarse en una zona rural
> * Fallas en los componentes y poca disponibilidad del material.
> * Condiciones climáticas extremas, así como bajas temperaturas.
> * Costos de implementación al contar con un presupuesto limitado.
> * Competencia en el ámbito tecnológico.


> * [Reporte](https://github.com/RawTech1/integrador_enero_abril/blob/main/Reporte2.pdf)

>[!VIDEO](https://github.com/RawTech1/integrador_enero_abril/blob/main/video.mp4)








