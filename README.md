# “Monitoreo de la calidad del agua de un canal en Mixquiahuala” 

### Introducción

El presente trabajo se enfoca en la investigación de la calidad del agua en el canal ubicado en las coordenadas 20.2058333,-99.2275431, ubicado en el
municipio de Mixquiahuala de Juárez en el Estado de Hidalgo, México. Esta región tiene una importancia económica y ambiental debido a que el canal su 
uso principal es para el riego de cultivos como maíz, trigo, frijol, entre otros.

La importancia de este prototipo radica en su capacidad para identificar los contaminantes clave presentes en el agua para que los especialistas puedan 
evaluar su impacto directo en el riego agrícola y, por consiguiente, en la producción de alimentos. 

Para abordar esta problemática, se ha diseñado un prototipo integral que busca evaluar y mejorar la calidad del agua en el canal. Los aspectos clave de esta solución son:

  - Monitoreo Estratégico: Sensores inalámbricos recopilan datos en tiempo real sobre parámetros como pH, turbidez y temperatura.
  
  - Visualización y Análisis: Los datos recopilados se visualizan en gráficos. El historial de datos ayuda a identificar patrones y eventos críticos.


## Antecedentes y planteamiento de problema

Con base en los antecedentes, se ha detectado que en la calidad del agua surge la siguiente problemática; de acuerdo con Mendoza, Cervantes, Valenzuela, Guzmán,
Orona, & Cervantes (2021), el crecimiento demográfico y la urbanización han llevado a un incremento en la generación de aguas residuales. Este fenómeno se debe a 
la mayor concentración de población en áreas urbanas y al consecuente aumento en el consumo y producción de desechos.

La demanda de líquido por este sector se incrementó entre 2001 y 2014 en 15.4% (Mapa 1). El 64.5 % del agua para uso agrupado agrícola proviene de fuentes superficiales 
(ríos, arroyos y lagos), mientras que el 35.5% procede de fuentes subterráneas (acuíferos), ver el recuadro Agua virtual en México.
 
De acuerdo con Mendoza, Cervantes, Valenzuela, Guzmán, Orona, & Cervantes (2021), indican que el uso de aguas residuales sin tratamiento adecuado puede llevar a la contaminación
del suelo y cultivos, afectando la calidad de los alimentos y la salud pública. Estos hechos indican la necesidad de implementar estrategias para la gestión del agua y soluciones 
tecnológicas para dar solución a los desafíos relacionados con la calidad y disponibilidad del recurso hídrico en México, dando más énfasis en el contexto de la creciente demanda 
agrícola y la problemática asociada con el uso de aguas residuales para riego.

Por lo anterior, las consecuencias derivadas de estas problemáticas son las siguientes:
Según la Organización de Agua en México (2011), nos dice que en 2015 murieron en México 3 754 personas debido a enfermedades infecciosas intestinales. 
Según Ayres & Duncan (2017) El uso de aguas residuales puede transmitir enfermedades a través de cultivos contaminados, especialmente si las aguas contienen nematodos intestinales 
y bacterias fecales. De acuerdo con Mendoza, Cervantes, Valenzuela, Guzmán, Orona, & Cervantes (2021), indican que el uso de aguas residuales sin tratamiento adecuado puede llevar
a la contaminación del suelo y cultivos, afectando la calidad de los alimentos y la salud pública.

El incumplimiento de las normas y regulaciones en el problema de la calidad del agua no solo pone en riesgo la salud de la población y el medio ambiente, sino que también afecta de 
forma inmediata y negativa la seguridad alimentaria, así como la sostenibilidad de las prácticas agrícolas que usan el canal ya mencionado. La implementación de un sistema de monitoreo 
avanzado no solo facilitará la implementación detección pronta de contaminantes, sino que también permitirá la adopción de medidas preventivas y correctivas oportunas para proteger la 
calidad del agua y garantizar la calidad de los alimentos producidos.

## Justificación

La contaminación del agua en la zona persiste a lo largo de los años debido a la contaminación del río Tula, provocando una violación de las normas establecidas para la calidad del agua
utilizada en la agricultura. 

A continuación, se destacan los beneficios y objetivos del desarrollo del prototipo.
En primer lugar, incluyen la protección de la salud pública al garantizar la calidad de los alimentos cultivados con agua proveniente del canal.  Asimismo, el cumplimiento normativo, la 
preservación del medio ambiente, la promoción de prácticas sostenibles y la mejora de la calidad de vida de las comunidades afectadas, al llevar a cabo un monitoreo para el análisis en la
toma de decisiones de los agricultores. 

Además, con la implementación de este monitoreo se espera mejorar la calidad de vida de las comunidades agrícolas afectadas al proporcionar información precisa y actualizada para la toma de
decisiones informadas por parte de los agricultores. Esto facilitará la adopción de medidas preventivas y mejoras adecuadas, contribuyendo a optimizar el uso del recurso hídrico y reducir los
riesgos asociados con la contaminación del agua, salvaguardando la salud de la población.


## Objetivos

Objetivo General
El objetivo general de este proyecto es diseñar y desarrollar un prototipo que utilice el módulo de desarrollo ESP32 LoRa V2 para monitorear los niveles de pH, temperatura y turbidez 
en las aguas residuales de los canales de riego del municipio de Mixquiahuala. El prototipo tiene como finalidad identificar la calidad del agua y detectar los niveles de contaminantes,
con el propósito de contribuir a la protección del medio ambiente, promover una agricultura sostenible y facilitar la toma de decisiones informadas en la gestión del agua.

 Objetivos Especificos
   - Investigar y seleccionar los sensores adecuados para medir los niveles de PH, temperatura y turbidez en las aguas negras de los canales de riego.
   - Diseñar el circuito electrónico y la configuración del módulo ESP32 LoRa V2 para la adquisición de datos de los sensores.
   - Desarrollar el software y la interfaz de usuario para la visualización y registro de los datos de PH, temperatura y turbidez.
   - Realizar pruebas de calibración y validación del prototipo para asegurar la precisión y confiabilidad de las mediciones.
   - Implementar el prototipo en los canales de riego del municipio de Mixquiahuala y realizar un monitoreo continuo de los niveles de PH, temperatura y
     turbidez durante un período de tiempo determinado.

  
## Desarrollo del prototipo

  El estándar de la pila de comunicación ISO, LoRa contiene sólo el protocolo de la capa deenlace. El protocolo de la capa de enlace se refiere a los  protocolos utilizados 
  para la comunicación entre nodos adyacentes en una red.
  LoRa permite tasas de datos bajas a moderadas y ofrece flexibilidad en la configuración de frecuencias y potencia de transmisión, adaptándose así a diversas regulaciones 
  regionales y requerimientos de alcance. Sin embargo, algunos parámetros físicos interfieren como la atenuación, reflexión, dispersión, entre otros.

Al iniciar el prototipo se tenía previsto una investigación y análisis, definición de requisitos, el desarrollo del software obteniendo una lectura de datos desde un ID sin embargo, para
que al pasar a la siguiente fase del prototipo se realizaron algunas configuraciones. En una placa raspberry pi 3 se realizó la instalación de los programas node-red, mosquitto MQTT y
grafanna, donde en el caso de node-red se realizó la instalación de algunos plugins, de igual manera por comandos en bash se realizaron configuraciones de mosquitto donde se asigna el puerto
1883 y de usuarios anónimos, para la asignación de usuarios y contraseña se creó un archivo txt para después ser encriptado, en seguida se asigna estas configuraciones en el archivo que se modificó primero.
