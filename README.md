# **ENTREGA 1: PROYECTO DE AULA**



###### Designación de roles

Isabella Guerrero Sierra: Cumple el rol de "technical Lead" asignado por el docente de área 

Marzuq Yucef Gallego Muñoz: Su rol dentro del equipo corresponde al "Firmware Engineer"

Andrés Ramírez Arenas: Participa como "Hardware Integration Engineer"



&nbsp;	Cada uno de los roles fueron seleccionados referente a los  gustos  y habilidades personales, además de recomendaciones y limitaciones del docente



###### 1\. Introducción:

&nbsp;	El diseño y la implementación de sistemas autónomos capaces de navegar en entornos estructurados pero desconocidos representa uno de los desafíos más significativos en la ingeniería electrónica y de control contemporánea. En el ámbito de los sistemas embebidos, este problema se sintetiza tradicionalmente a través de la plataforma de competencia Micro Mouse, la cual sirve como un banco de pruebas riguroso para la integración de hardware y firmware de alta precisión.



&nbsp;	El problema fundamental que aborda este sistema es la incertidumbre espacial y la optimización de trayectorias bajo restricciones de recursos. En un entorno industrial o de exploración, los dispositivos a menudo deben operar en áreas donde la señal de GPS es inexistente y los mapas no están disponibles de forma previa. Esto exige que el sistema embebido posea una arquitectura de procesamiento capaz de ejecutar algoritmos de mapeo probabilístico y toma de decisiones en tiempo real, transformando señales analógicas y digitales de baja fidelidad en un modelo lógico del entorno.



&nbsp;	Contextualmente, un robot de este tipo no es solo un vehículo móvil; es una unidad de procesamiento distribuido que debe gestionar simultáneamente el control de lazo cerrado de motores, la filtración de ruido en señales de sensores y la gestión de protocolos de comunicación síncronos y asíncronos. La relevancia de este sistema radica en su capacidad para demostrar cómo la aplicación de buenas prácticas de ingeniería —como el determinismo en el tiempo de ejecución y la modularidad del código— permite resolver problemas complejos de navegación autónoma que son directamente escalables a vehículos de guiado automático (AGVs) en logística y robots de inspección en infraestructuras críticas.



###### 2\. Alcance del Proyecto

El presente proyecto se circunscribe al diseño, desarrollo e implementación de un sistema embebido autónomo de alta precisión, cuya arquitectura está orientada a la resolución de problemas de navegación y optimización de trayectorias. El alcance técnico se define mediante los siguientes ejes fundamentales:



Infraestructura de Hardware y Potencia: El proyecto abarca el diseño e integración de una plataforma física autopropulsada. Esto incluye la gestión de energía, el acondicionamiento de señales provenientes de transductores y la implementación de etapas de potencia capaces de accionar elementos electromecánicos con resolución variable.



Capa de Percepción y Sensado: Se establece la integración de un subsistema de adquisición de datos para la medición de variables físicas del entorno y del estado interno del sistema. El alcance incluye la digitalización, el filtrado y el procesamiento de estas variables para alimentar los algoritmos de toma de decisiones.



Arquitectura de Firmware y Control: El desarrollo de software embebido se fundamenta en un diseño estructurado y modular. Se implementarán lazos de control realimentados, algoritmos de búsqueda y una lógica de navegación basada en eventos que garantice un comportamiento determinista ante cambios en el entorno.



Gestión de Comunicaciones Multiprotocolo: El sistema integrará canales de comunicación normalizados para la interacción con periféricos externos. Esto incluye buses de datos de alta velocidad para el intercambio de información local y enlaces de telemetría para el diagnóstico del sistema en tiempo real.



Subsistema de Trazabilidad y Registro (Logging): El alcance contempla la creación de un motor de persistencia de datos. Este subsistema debe ser capaz de registrar eventos críticos, estados del procesador y lecturas sensoriales en una unidad de memoria no volátil para su posterior auditoría técnica.



Interfaz de Usuario y Gestión de Estados: Se diseñará un entorno de interacción física que permita al operador humano monitorear el estado del sistema, configurar parámetros de operación y ejecutar rutinas de prueba de manera directa sobre el hardware.



Validación y Pruebas de Integración: El proyecto concluye con una fase de verificación física donde se evaluará la respuesta del sistema ante escenarios de prueba controlados, asegurando que la integración entre el hardware, el firmware y la mecánica cumpla con los estándares de robustez planteados.



###### 3\. Objetivos

Objetivo General

Desarrollar un sistema embebido funcional y autónomo basado en la arquitectura de un robot móvil, orientado a la resolución de problemas de navegación compleja mediante la aplicación rigurosa de estándares de ingeniería, asegurando un diseño de firmware determinista, hardware trazable y una gestión robusta de fallos.



Objetivos Específicos

Ingeniería de Requisitos y Trazabilidad: Establecer una matriz de requisitos técnicos que vincule cada sensor, actuador y línea de código con una funcionalidad específica del sistema, garantizando que el diseño final sea una respuesta directa a las necesidades del proyecto.
