## Proyecto Integrador- "Monitoreo de la calidad del agua de un canal en Mixquiahuala"

El prototipo de IoT para la agricultura en la zona de Mixquiahuala consiste en un sistema de monitoreo de la calidad del agua diseñado específicamente para los cultivos que utilizan el agua de un canal. Utilizando las tecnologías inalámbricas, este sistema detecta y analiza parámetros clave como el pH, la temperatura y la turbidez del agua en tiempo real coninformación clara.

LoRaWAN, un estándar global para comunicaciones de baja potencia y área amplia, es la tecnología subyacente utilizada en este sistema. Gracias a LoRaWAN, los datos recopilados se transmiten a larga distancia con bajo consumo de energía y costos de conectividad reducidos. Además, esta tecnología es versátil y segura, lo que la convierte en una opción ideal para aplicaciones agrícolas.

El sistema de monitoreo de calidad del agua ofrece a agricultores de Mixquiahuala la capacidad de ajustar de manera proactiva niveles de nutrientes y frecuencia de riego en función de los parámetros. Al tener información precisa en tiempo real sobre la calidad del agua, los agricultores pueden optimizar el crecimiento de cultivos y prevenir problemas relacionados con la calidad del agua.

Las tecnologías inalámbricas, en el prototipo para la agricultura en Mixquiahuala es fundamental para el éxito del sistema de monitoreo de calidad del agua. Estas tecnologías permiten una comunicación eficiente, reducen los costos y brindan información precisa, lo que ayuda a los agricultores a tomar decisiones más informadas y optimizar el crecimientode sus cultivos.

## Objetivos

Objetivo General

Diseñar y desarrollar un prototipo de monitoreo para el canal de aguas negras en Mixquiahuala. Este sistema implementará sensores para detectar parámetros como la temperatura, ph y turbidez utilizando tecnologías inalámbricas para transmitir datos en tiempo real que serán recabados en un dashboard. Este sistema busca analizar la gestión y calidad del agua utilizada para el riego en la zona agrícola de Mixquiahuala, contribuyendo así a la cooperación en conjunto con los agricultores para mitigar los impactos negativos de la contaminación en los canales de riego.

Objetivo Específico

- Implementar sensores para medir la temperatura, ph y turbidez del agua en el canal de aguas negras, garantizando una lectura precisa y confiable.
- Integrar tecnologías inalámbricas para la transmisión de datos en tiempo real desde los sensores instalados hasta un dashboard para su análisis.

## Justificación 
La contaminación del agua en la zona persiste a lo largo de los años debido a la contaminación del río Tula, provocando una violación de las normas establecidas para la calidad del agua utilizada en la agricultura. A continuación, se destacan los beneficios y objetivos del desarrollo del prototipo.
En primer lugar, incluyen la protección de la salud pública al garantizar la calidad de los alimentos cultivados con agua proveniente del canal. Asimismo, el cumplimiento normativo, la preservación del medio ambiente, la promoción de prácticas sostenibles y la mejora de la calidad de vida de las comunidades afectadas, al llevar a cabo un monitoreo para el análisis en la toma de decisiones de los agricultores. Además, con la implementación de este monitoreo se espera mejorar la calidad de vida de las comunidades agrícolas afectadas al proporcionar información precisa y actualizada para la toma de decisiones informadas por parte de los agricultores. Esto facilitará la adopción de medidas preventivas y mejoras adecuadas, contribuyendo a optimizar el uso del recurso hídrico y reducir los riesgos asociados con la contaminación del agua, salvaguardando la salud de la población.

## Desarrollo del prototipo
El estándar de la pila de comunicación ISO, LoRa contiene sólo el protocolo de la capa de enlace. El protocolo de la capa de enlace se refiere a los protocolos utilizados para la comunicación entre nodos adyacentes en una red [3]. LoRaWan incluye el otro nivel de red y estandariza el nodo para enviar
la información a cualquier puesto de base ya conectado a una plataforma en la nube [1]. LoRa permite tasas de datos bajas a moderadas y ofrece flexibilidad en la configuración de frecuencias y potencia de transmisión, adaptándose así a diversas regulaciones regionales y requerimientos de alcance. Sin embargo, algunos parámetros físicos interfieren como la atenuación, reflexión, dispersión, entre otros [2].

Al iniciar el prototipo se tenía previsto una investigación y análisis, definición de requisitos, el desarrollo del software obteniendo una lectura de datos desde un ID sin embargo, para que al pasar a la siguiente fase del prototipo se realizaron algunas configuraciones. En una placa raspberry pi 3 se realizó la instalación de los programas node-red, mosquitto MQTT y grafanna, donde en el caso de node-red se realizó la instalación de algunos plugins, de igual manera por comandos en bash se realizaron configuraciones de mosquitto donde se asigna el puerto 1883 y de usuarios anónimos, para la asignación de usuarios y contraseña se creó un archivo txt para después ser encriptado, en seguida se asigna estas configuraciones en el archivo que se modificó primero.

La conexiones empiezan entre los sensores que se conectan por cable de cobre que van a la placa Heltec Lora, desde ahí la comunicación que se realiza entre el transmisor y Gateway se realiza de forma inalámbrica por radio, para transmitir los datos a node-red es por medio inalámbrico utilizando wifi, donde como protocolo se usa Mqtt Mosquitto, para realizar tal conexión se inicializa las librerías y objetos para la comunicación LoRa y el control de una pantalla OLED, ajustando parámetros para sensores y la banda de frecuencia LoRa de igual manera se inicializa y configura los componentes necesarios para el funcionamiento del sistema, estableciendo la comunicación de los sensores, para la comunicación LoRa, y la pantalla OLED.


