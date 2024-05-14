# “Monitoreo de la calidad del agua de un canal en Mixquiahuala” 

### Introducción
El prototipo de IoT para la agricultura en la zona de Mixquiahuala consiste en un sistema de monitoreo de la calidad del agua diseñado específicamente
para los cultivos que utilizan el agua de un canal. Utilizando las tecnologías inalámbricas, este sistema detecta y analiza parámetros clave como el pH,
la temperatura y la turbidez del agua en tiempo real con información clara.

LoRaWAN, un estándar global para comunicaciones de baja potencia y área amplia, es la tecnología subyacente utilizada en este sistema. Gracias a 
LoRaWAN, los datos recopilados se transmiten a larga distancia con bajo consumo de energía y costos de conectividad reducidos. 

El sistema de monitoreo de calidad del agua ofrece a agricultores de Mixquiahuala la capacidad de ajustar de manera proactiva niveles de nutrientes y
frecuencia de riego en función de los parámetros. 


## Antecedentes y planteamiento de problema
La demanda de líquido por este sector se incrementó entre 2001 y 2014 en 15.4% (Mapa 1). El 64.5 % del agua para uso agrupado agrícola proviene de 
fuentes superficiales (ríos, arroyos y lagos), mientras que el 35.5% procede de fuentes subterráneas (acuíferos), ver el recuadro Agua virtual en México.

Por lo anterior, las consecuencias derivadas de estas problemáticas son las siguientes: 
Según la Organización de Agua en México (2011), nos dice que en 2015 murieron en México 3 754 personas debido a enfermedades infecciosas intestinales.
Según Ayres & Duncan (2017) El uso de aguas residuales puede transmitir enfermedades a través de cultivos contaminados, especialmente si las aguas 
contienen nematodos intestinales y bacterias fecales.

Estos hechos indican la necesidad de implementar estrategias para la gestión del agua y soluciones tecnológicas para dar solución a los desafíos
relacionados con la calidad y disponibilidad del recurso hídrico en México, dando más énfasis en el contexto de la creciente demanda agrícola y 
la problemática asociada con el uso de aguas residuales para riego.

El problema central radica en la ausencia de un monitoreo en tiempo real que permita evaluar de manera efectiva la calidad del recurso hídrico en el
canal mencionado. Esta falta de información precisa y actualizada sobre los niveles de contaminación dificulta la toma de decisiones informadas para 
mitigar los impactos ambientales y proteger la salud de los agricultores y consumidores.

Esta falta de cumplimiento de las normativas vigentes hace más visible la necesidad deimplementar soluciones tecnológicas avanzadas que permitan identificar y 
cuantificar con precisión los contaminantes presentes en el agua utilizada para el riego. La investigación y desarrollo de un sistema de monitoreo, basado en 
tecnologías innovadoras como sensores avanzados y tecnología inalámbrica (LoRa) será fundamental para contribuir a especialistas para mejorar esta problemática 
de manera holística y sostenible.

## Justificación
La contaminación del agua en la zona persiste a lo largo de los años debido a lacontaminación del río Tula, provocando una violación de las normas establecidas 
para la calidad del agua utilizada en la agricultura. A continuación, se destacan los beneficios y objetivos del desarrollo del prototipo. En primer lugar, incluyen 
la protección de la salud pública al garantizar la calidad de los alimentos cultivados con agua proveniente del canal.

Asimismo, el cumplimiento normativo, la preservación del medio ambiente, la promoción de prácticas sostenibles y la mejora de la calidad de vida de las comunidades 
afectadas, al llevar a cabo un monitoreo  para el análisis en la toma de decisiones de los agricultores. Además, con la implementación de este monitoreo se espera mejorar
la calidad de vida de las comunidades agrícolas afectadas al proporcionar información precisa y actualizada para la toma de decisiones informadas por parte de los agricultores.

## Objetivos

   Objetivo General
Diseñar y desarrollar un prototipo de monitoreo para el canal de aguas negras en Mixquiahuala. Este sistema implementará sensores para detectar parámetros como la
temperatura, ph y turbidez utilizando tecnologías inalámbricas para transmitir datos en tiempo real que serán recabados en un dashboard. 
Este sistema busca analizar la gestión y calidad del agua utilizada para el riego en la zona agrícola de Mixquiahuala, contribuyendo así a la cooperación en conjunto
con los agricultores para mitigar los impactos negativos de la contaminación en los canales de riego.

Objetivo Específico

  - Implementar sensores para medir la temperatura, ph y turbidez del agua en el canal de aguas negras, garantizando una lectura precisa y confiable.
  - Integrar tecnologías inalámbricas para la transmisión de datos en tiempo real desde los sensores instalados hasta un dashboard para su análisis.

## Desarrollo del prototipo
  El estándar de la pila de comunicación ISO, LoRa contiene sólo el protocolo de la capa deenlace. El protocolo de la capa de enlace se refiere a los  protocolos utilizados 
  para la comunicación entre nodos adyacentes en una red.
  LoRa permite tasas de datos bajas a moderadas y ofrece flexibilidad en la configuración de frecuencias y potencia de transmisión, adaptándose así a diversas regulaciones 
  regionales y requerimientos de alcance. Sin embargo, algunos parámetros físicos interfieren como la atenuación, reflexión, dispersión, entre otros.

Al iniciar el prototipo se tenía previsto una investigación y análisis, definición de requisitos, el desarrollo del software obteniendo una lectura de datos desde un ID sin embargo, para
que al pasar a la siguiente fase del prototipo se realizaron algunas configuraciones. En una placa raspberry pi 3 se realizó la instalación de los programas node-red, mosquitto MQTT y
grafanna, donde en el caso de node-red se realizó la instalación de algunos plugins, de igual manera por comandos en bash se realizaron configuraciones de mosquitto donde se asigna el puerto
1883 y de usuarios anónimos, para la asignación de usuarios y contraseña se creó un archivo txt para después ser encriptado, en seguida se asigna estas configuraciones en el archivo que se modificó primero.
