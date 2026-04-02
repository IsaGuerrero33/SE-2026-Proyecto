# **ENTREGA 1: PROYECTO DE AULA**



###### Designación de roles

Isabella Guerrero Sierra: Cumple el rol de "technical Lead" asignado por el docente de área 

Marzuq Yucef Gallego Muñoz: Su rol dentro del equipo corresponde al "Firmware Engineer"

Andrés Ramírez Arenas: Participa como "Hardware Integration Engineer"



&nbsp;	Cada uno de los roles fueron seleccionados referente a los  gustos  y habilidades personales, además de recomendaciones y limitaciones del docente



###### 1\. Introducción:

&nbsp;	Los sistemas de clasificacián automatizada estan ampliamente extendidos en la industria y resultan actualmente en unos de los mas importantes ya que reducen en gran manera la intervencion humana y aumentan la productividad considerablemente. Estos sistemas capaces de organizar mercancias segun sus caracteristicas fisicas (tamaño, color, forma, peso, etc) permiten a las empresas gestionar grandes volumenes de inventario reduciendo errores y tiempo.



&nbsp;	El problema central que este proyecto pretende solucionar es la transformacion de datos del entorno fisico en decisiones logicas. En un proceso continuo, el sistema debe ser capaz de identificar variables fisicas con gran velocidad y exactitud para poder tomar una decisión. Para este proyecto especificamente se considerara como variable fisica el volumen de una caja y la decisión a tomar será donde disponer dicha caja.



###### 2\. Alcance del Proyecto

El presente proyecto consta del diseño, desarrollo e implementación de un sistema embebido autonomo orientado a la clasificación de elemetos por tamaño.. El alcance técnico se define mediante los siguientes ejes fundamentales:



Infraestructura de Hardware y Potencia: Comprende el diseño de una estructura de transporte y un sistema fisico de desviación; además de un sistema de gestion energetica necesaria para alimentar la logica de control como los actuadores involucrados en el proceso, asegurando que el sistema responda con la velocidad, fuerza y exactitud requerida en cada tarea.



Percepción y Sensado: Comprende un sistema encargado de la adquisision de señales (medición de variables), su acondicionamiento y transmisión. Con el fin de obtener lecturas de datos limpios para que funcionen como la base de la logica de clasificación.



Logica de control y procesamiento: Centrado en una estructura de programación organizada que le permita al sistema reaccionar de forma predecible. Se implementan algoritmos para el calculo de dimensiones a partir de los datos obtenidos por el sistema de sensado; se gestionan tiempos de respuesta y la activación coordinada de los actuadores de desvío.



Gestión de Comunicaciones: El sistema debe tener canales de comunicación mediante protocolos estandarizados, para la transmisión de datos internos como externos. Esto es tanto para la lectura digital de los sensores como para la posterior visualización en una interfaz o guardado de los datos para su analisis.



Subsistema de Trazabilidad y Registro (Logging): Se contempla la creación de una función de seguimiento que documente el comportamiento del sistema. Este registro debe identificar el estado de los procesos, confirmar las clasificaciones exitosas y alertar sobre posibles anomalías operativas para facilitar el mantenimiento técnico.



Interfaz de Usuario y Gestión de Estados: Se diseñará un entorno de interacción física que permita al operador humano monitorear el estado del sistema, configurar parámetros de clasificación y/o visualizar estadisticas del sistema.



Validación y Pruebas de Integración: El proyecto concluye con una fase de verificación física donde se evaluará la respuesta del sistema ante escenarios de prueba controlados, asegurando que la integración entre el hardware, el firmware y la mecánica cumpla con los estándares de robustez planteados.



###### 3\. Objetivos

Objetivo General

Desarrollar un sistema de clasificación autónomo y eficiente, capaz de categorizar objetos según sus dimensiones físicas mediante un control electrónico preciso, garantizando la trazabilidad de los eventos y la flexibilidad ante diferentes requerimientos operativos.



Objetivos Específicos

Optimización del Proceso de Sensado: Establecer un método de captura de datos que garantice lecturas consistentes de la altura de los objetos, minimizando el impacto de factores externos en la medición.



Facilitación de la Operatividad: Proveer las herramientas necesarias para que el usuario final pueda monitorear el conteo de unidades y ajustar los parámetros de clasificación de forma intuitiva y segura.
