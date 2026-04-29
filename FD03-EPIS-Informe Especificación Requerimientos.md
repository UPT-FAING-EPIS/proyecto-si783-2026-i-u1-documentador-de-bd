<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

# UNIVERSIDAD PRIVADA DE TACNA
## FACULTAD DE INGENIERÍA
### Escuela Profesional de Ingeniería de Sistemas

**Proyecto:** Sistema de documentación de Base de Datos

**Curso:** Base de Datos II
**Docente:** Mag. Patrick Cuadros Quiroga

**Integrantes:**
- Andia Navarro, Diego Fabrizio (2022073906)
- Quispe Chileno, Clara Briyith Mayra (2024080129)

**Tacna – Perú**
**2026**

---

# CONTROL DE VERSIONES

| Versión | Hecha por | Revisada por | Aprobada por | Fecha | Motivo |
|--------|----------|-------------|--------------|-------|--------|
| 1.0 | DAN,CQC | DAN,CQC | ARV | 10/10/2020 | Versión Original |

---

# **Sistema de documentación de base de datos**

# **Especificación de Requerimientos**


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|












**Sistema *Sistema de documentación de Base de Datos***

**Informe Especificación de Requerimientos**

**Versión *{1.0}***
**


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

# ÍNDICE GENERAL

- [Introducción](#introducción)  
  - [1. Generalidades de la Empresa](#1-generalidades-de-la-empresa)  
    - [1.1 Nombre de la Empresa](#11-nombre-de-la-empresa)  
    - [1.2 Visión](#12-visión)  
    - [1.3 Misión](#13-misión)  
    - [1.4 Organigrama](#14-organigrama)  

  - [2. Visionamiento de la Empresa](#2-visionamiento-de-la-empresa)  
    - [2.1 Descripción del Problema](#21-descripción-del-problema)  
    - [2.2 Objetivos de Negocio](#22-objetivos-de-negocio)  
    - [2.3 Objetivos de Diseño](#23-objetivos-de-diseño)  
    - [2.4 Alcance del Proyecto](#24-alcance-del-proyecto)  
    - [2.5 Viabilidad del Sistema](#25-viabilidad-del-sistema)  
    - [2.6 Información obtenida del levantamiento de Información](#26-información-obtenida-del-levantamiento-de-información)  

  - [3. Análisis de Procesos](#3-análisis-de-procesos)  
    - [3.1 Diagrama del Proceso Actual](#31-diagrama-del-proceso-actual)  
    - [3.2 Diagrama del Proceso Propuesto](#32-diagrama-del-proceso-propuesto)  

  - [4. Especificación de Requerimientos de Software](#4-especificación-de-requerimientos-de-software)  
    - [4.1 Requerimientos Funcionales Inicial](#41-cuadro-de-requerimientos-funcionales-inicial)  
    - [4.2 Requerimientos No Funcionales](#42-cuadro-de-requerimientos-no-funcionales)  
    - [4.3 Requerimientos Funcionales Final](#43-cuadro-de-requerimientos-funcionales-final)  
    - [4.4 Reglas de Negocio](#44-reglas-de-negocio)  

  - [5. Fase de Desarrollo](#5-fase-de-desarrollo)  
    - [5.1 Perfiles de Usuario](#51-perfiles-de-usuario)  
    - [5.2 Modelo Conceptual](#52-modelo-conceptual)  
    - [5.3 Modelo Lógico](#53-modelo-lógico)  

- [Conclusiones](#conclusiones)  
- [Recomendaciones](#recomendaciones)  

---

# INTRODUCCIÓN

# 1 Generalidades de la Empresa

## 1.1 Nombre de la Empresa

DB Smart Solutions S.A.C.

## 1.2 Visión

Ser una empresa líder en soluciones tecnológicas orientadas a la automatización, análisis y documentación inteligente de bases de datos a nivel nacional e internacional.

## 1.3 Misión

Brindar herramientas innovadoras que faciliten la gestión, comprensión y mantenimiento de bases de datos mediante soluciones eficientes, seguras y accesibles.

## 1.4 Organigrama

---

# 2 Visionamiento de la Empresa

## 2.1 Descripción del Problema

Muchas bases de datos no cuentan con documentación actualizada. Esto genera dependencia del conocimiento técnico de ciertos desarrolladores, incrementa errores en modificaciones futuras y retrasa el mantenimiento de los sistemas.

Esta situación dificulta la comprensión de la estructura de la base de datos, incluyendo tablas, relaciones, restricciones y reglas de negocio implementadas. Como consecuencia, los procesos de análisis, desarrollo y actualización se vuelven más lentos y propensos a fallos, afectando la calidad del software y la eficiencia del equipo de trabajo.

Asimismo, la falta de documentación estructurada complica la integración con otros sistemas y limita la trazabilidad de los cambios realizados en la base de datos. Esto también impacta negativamente en la incorporación de nuevos desarrolladores, quienes deben invertir tiempo considerable en entender el funcionamiento del sistema sin contar con una referencia clara.

En este contexto, se hace necesario contar con una solución que permita generar y mantener automáticamente la documentación de las bases de datos, facilitando su entendimiento, reduciendo errores y mejorando los procesos de mantenimiento y evolución del sistema.

## 2.2 Objetivos de Negocio

- Reducir tiempos de análisis de bases de datos.- Esto permitirá a los equipos técnicos comprender de manera más rápida la estructura y funcionamiento de las bases de datos, optimizando los procesos de desarrollo, mantenimiento y toma de decisiones.
- Mejorar la mantenibilidad de sistemas.- Se busca facilitar la actualización, modificación y evolución de los sistemas mediante una documentación clara y automatizada, reduciendo la dependencia del conocimiento individual y minimizando errores.
- Ofrecer una solución web escalable.- La solución estará diseñada para adaptarse al crecimiento de usuarios y volumen de datos, permitiendo su implementación en diferentes entornos organizacionales sin afectar el rendimiento.
- Generar valor mediante automatización documental.- A través de la automatización de la documentación de bases de datos, se pretende mejorar la eficiencia operativa, reducir costos asociados a errores y retrabajos, y aportar mayor valor a los procesos tecnológicos de la organización.
  

## 2.3 Objetivos de Diseño

- Diseñar una interfaz amigable.- Se desarrollará una interfaz intuitiva y de fácil uso que permita a los usuarios interactuar con el sistema sin necesidad de conocimientos técnicos avanzados, mejorando la experiencia de uso. 
- Automatizar la extracción de metadatos.- El sistema será capaz de obtener automáticamente información relevante de la base de datos, como tablas, atributos, relaciones y restricciones, evitando procesos manuales. 
- Visualizar relaciones entre tablas.- Se implementarán representaciones gráficas que permitan entender de manera clara la estructura y conexiones dentro de la base de datos, facilitando el análisis. 
- Exportar reportes en PDF/HTML.- Se permitirá generar documentación en formatos estándar, facilitando su almacenamiento, distribución y uso en distintos contextos, tanto técnicos como administrativos. 


## 2.4 Alcance del Proyecto

El sistema permitirá conectarse a motores de base de datos compatibles, analizar tablas, campos, claves, relaciones y generar documentación estructurada con diagramas ER. 

Además, el sistema estará orientado a facilitar la comprensión de la estructura interna de las bases de datos mediante la generación automática de documentación técnica, permitiendo a los usuarios visualizar de forma clara los componentes y sus interrelaciones. La solución incluirá funcionalidades de análisis de metadatos, generación de diagramas entidad-relación y exportación de documentación en formatos accesibles.

El alcance del proyecto se limita al análisis y documentación de bases de datos, por lo que no contempla la modificación directa de la información ni la administración completa del motor de base de datos. Asimismo, no se incluirán integraciones avanzadas con sistemas externos en esta etapa, enfocándose exclusivamente en mejorar la comprensión, mantenimiento y documentación de las estructuras existentes.


## 2.5 Viabilidad del Sistema

El proyecto es viable técnicamente, económicamente y operativamente, debido al uso de tecnologías open source y recursos disponibles. 

Desde el punto de vista técnico, la implementación del sistema es factible gracias a la disponibilidad de herramientas y librerías que permiten la conexión con distintos sistemas gestores de bases de datos, así como la extracción y procesamiento de metadatos. Esto facilita el desarrollo de una solución robusta sin requerir infraestructura compleja.

En el aspecto económico, el uso de tecnologías de código abierto reduce significativamente los costos de desarrollo e implementación, haciendo que el proyecto sea accesible y sostenible. Además, la automatización de la documentación permitirá disminuir costos asociados a errores, retrabajos y tiempos prolongados de análisis.

En cuanto a la viabilidad operativa, el sistema está diseñado para ser accesible mediante una interfaz web intuitiva, lo que permitirá su uso por parte de desarrolladores y otros usuarios sin necesidad de capacitación extensa, mejorando la productividad y eficiencia en el manejo de bases de datos.


## 2.6 Información obtenida del levantamiento de Información

Durante el proceso de levantamiento de información se identificaron las siguientes necesidades principales:

- Necesidad de documentación automatizada  
- Compatibilidad con múltiples SGBD  
- Acceso web  
- Exportación de documentación  

La información fue recopilada a partir del análisis de necesidades en entornos de desarrollo, donde se evidenció la falta de herramientas eficientes para documentar bases de datos de forma automatizada. En este contexto, se identificó que los usuarios requieren soluciones que les permitan reducir el tiempo de análisis y mejorar la comprensión de estructuras complejas.
Asimismo, se determinó la importancia de contar con compatibilidad con múltiples sistemas gestores de bases de datos, lo que permite que la herramienta sea flexible y adaptable a distintos entornos tecnológicos. De igual manera, se destacó la necesidad de acceso a través de navegadores web, facilitando su uso sin depender de instalaciones locales y mejorando la accesibilidad.
Finalmente, se identificó como un requisito clave la capacidad de exportar la documentación generada en formatos estándar, lo que permite su distribución, almacenamiento y utilización en distintos contextos, tanto técnicos como administrativos.


Se identificó la falta de herramientas eficientes, necesidad de accesibilidad y soporte multiplataforma.

---

# 3 Análisis de Procesos

## 3.1 Diagrama del Proceso Actual

## 3.2 Diagrama del Proceso Propuesto

---

# 4 Especificación de Requerimientos de Software

## 4.1 Cuadro de Requerimientos Funcionales Inicial

| Código | Nombre | Descripción | Prioridad |
|--------|--------|------------|----------|
| RF01 | Conectar BD | Permitir conexión | Alta |
| RF02 | Leer Tablas | Obtener tablas | Alta |
| RF03 | Detectar Relaciones | Identificar PK y FK | Alta |
| RF04 | Generar Documentación | Crear documentación | Alta |

## 4.2 Cuadro de Requerimientos No Funcionales

| Código | Categoría | Descripción | Métrica |
|--------|----------|------------|--------|
| RNF01 | Rendimiento | < 15 seg | <=15 seg |
| RNF02 | Disponibilidad | Permanente | 99% |
| RNF03 | Seguridad | Cifrado | Obligatorio |
| RNF04 | Usabilidad | Responsive | Sí |

## 4.3 Cuadro de Requerimientos Funcionales Final

| Código | Nombre | Descripción | Prioridad |
|--------|--------|------------|----------|
| RF01 | Login | Autenticación | Alta |
| RF02 | Registrar Conexión | Guardar conexión | Alta |
| RF03 | Analizar BD | Inspeccionar | Alta |
| RF04 | Generar Diagramas | ER | Media |
| RF05 | Exportar Reportes | PDF/HTML | Alta |
| RF06 | Historial | Guardar consultas | Media |

## 4.4 Reglas de Negocio

- El sistema solo tendrá permisos de lectura.- El acceso a las bases de datos se realizará exclusivamente en modo lectura, garantizando que no se ejecuten operaciones de inserción, actualización o eliminación de datos. Esta regla asegura la integridad de la información original y evita cualquier impacto negativo en los sistemas fuente. 
- Usuario autenticado para acceder.- El acceso al sistema estará restringido a usuarios previamente autenticados, con el fin de garantizar la seguridad de la información procesada y evitar accesos no autorizados. Esto permitirá también mantener un control sobre el uso de la herramienta y las acciones realizadas. 
- Toda documentación debe generarse desde una conexión válida.- La generación de documentación sólo será posible cuando exista una conexión activa y válida con la base de datos o cuando el archivo proporcionado cumpla con los requisitos establecidos. Esto asegura que la información procesada sea consistente, confiable y completa. 
- No se modificará información de la BD origen.- El sistema no realizará ningún tipo de alteración sobre la base de datos de origen, ya sea en su estructura o en sus datos. Su función se limita al análisis y documentación, manteniendo la integridad y seguridad de la información original en todo momento. 


---

# 5 Fase de Desarrollo

## 5.1 Perfiles de Usuario

### Administrador
- Función.- Gestionar el acceso al sistema, controlar usuarios y supervisar el correcto funcionamiento de la plataforma. También se encarga de la configuración general del sistema y la seguridad. 
- Necesidades.- Acceso completo al sistema, control de usuarios autenticados, monitoreo de procesos y visualización de resultados generados. 


### Desarrollador
- Función.- Utilizar la herramienta para analizar bases de datos, generar documentación automática y comprender la estructura de los sistemas para su mantenimiento o mejora.
- Necesidades.- Acceso a funcionalidades de carga de archivos o conexión a bases de datos, visualización clara de diagramas ER, documentación generada automáticamente y exportación de resultados. 

### Analista
- Interpretar la información generada por el sistema, analizar estructuras de bases de datos y apoyar en la toma de decisiones basadas en la documentación obtenida.
- Necesidades.- Acceso a reportes claros, documentación estructurada, visualización comprensible de relaciones entre datos y facilidad para exportar información. 

## 5.2 Modelo Conceptual

Incluye:
- Diagrama de paquetes  
- Diagrama de casos de uso  

### Escenarios

## Caso de uso: Generar Reporte

| Campo | Descripción |
|------|------------|
| Id Caso de Uso | RF-04 |
| Nombre | Generar Reporte |
| Tipo | Obligatorio ( X ) / Opcional ( ) |
| Requisito ID (RF) | RF-04 |
| Versión | 1.0 |
| Autor | Equipo de Desarrollo |
| Actores | Usuario |
| Interacción | Fase de Generación de Documentación |
| Descripción | Permite generar documentación estructurada de la base de datos analizada con diagramas y exportación de archivos. |
| Referencias | Ninguna |
| Anexos | Ninguno |
| Precondiciones | Usuario autenticado y estructura previamente analizada. |
| PostCondiciones | Reporte generado y disponible para descarga. |
| Flujo Normal | 1. Usuario solicita reporte.<br>2. Sistema procesa datos.<br>3. Genera documentación.<br>4. Muestra resultado.<br>5. Usuario descarga archivo. |
| Flujo de Excepción E001 | Error en generación: el sistema falla en la creación del reporte y muestra mensaje de error. |

---

## Caso de uso: Analizar Estructura

| Campo | Descripción |
|------|------------|
| Id Caso de Uso | RF-03 |
| Nombre | Analizar Estructura de Base de Datos |
| Tipo | Obligatorio ( X ) / Opcional ( ) |
| Requisito ID (RF) | RF-03 |
| Versión | 1.0 |
| Autor | Equipo de Desarrollo |
| Actores | Usuario |
| Interacción | Fase de Procesamiento |
| Descripción | Permite analizar la estructura de la base de datos identificando tablas, atributos y relaciones. |
| Referencias | Ninguna |
| Anexos | Ninguno |
| Precondiciones | Usuario autenticado y base de datos conectada o archivo cargado. |
| PostCondiciones | Estructura analizada correctamente. |
| Flujo Normal | 1. Usuario solicita análisis.<br>2. Sistema procesa estructura.<br>3. Identifica tablas y relaciones.<br>4. Muestra resultados. |
| Flujo de Excepción E001 | Error de análisis: el sistema no puede procesar los datos y muestra mensaje de error. |

---

## Caso de uso: Conectar BD

| Campo | Descripción |
|------|------------|
| Id Caso de Uso | RF-02 |
| Nombre | Conectar Base de Datos |
| Tipo | Obligatorio ( X ) / Opcional ( ) |
| Requisito ID (RF) | RF-02 |
| Versión | 1.0 |
| Autor | Equipo de Desarrollo |
| Actores | Usuario |
| Interacción | Fase de Configuración |
| Descripción | Permite establecer una conexión con una base de datos para su análisis posterior. |
| Referencias | Ninguna |
| Anexos | Ninguno |
| Precondiciones | Usuario autenticado y credenciales de base de datos disponibles. |
| PostCondiciones | Conexión establecida correctamente. |
| Flujo Normal | 1. Usuario ingresa datos de conexión.<br>2. Sistema intenta conexión.<br>3. Usuario confirma.<br>4. Sistema valida acceso. |
| Flujo de Excepción E001 | Error de conexión: el sistema no logra conectarse y muestra mensaje de error. |

---

## Caso de uso: Iniciar Sesión

| Campo | Descripción |
|------|------------|
| Id Caso de Uso | RF-01 |
| Nombre | Iniciar Sesión |
| Tipo | Obligatorio ( X ) / Opcional ( ) |
| Requisito ID (RF) | RF-01 |
| Versión | 1.0 |
| Autor | Equipo de Desarrollo |
| Actores | Usuario (Administrador, Desarrollador, Analista) |
| Interacción | Fase de Autenticación |
| Descripción | Permite al usuario autenticarse en el sistema mediante sus credenciales para acceder a las funcionalidades disponibles. |
| Referencias | Ninguna |
| Anexos | Ninguno |
| Precondiciones | Usuario registrado en el sistema. |
| PostCondiciones | Usuario accede al sistema correctamente. |
| Flujo Normal | 1. Usuario ingresa credenciales.<br>2. Sistema valida credenciales.<br>3. Usuario solicita acceso.<br>4. Sistema permite el ingreso. |
| Flujo de Excepción E001 | Credenciales incorrectas: el sistema detecta el error y muestra mensaje de autenticación inválida. |

## 5.3 Modelo Lógico

### Análisis de Objetos

- Usuario.- Representa al actor que interactúa con el sistema, encargado de iniciar sesión, cargar archivos o establecer conexiones y solicitar la generación de reportes. 
- ConexionBD.- Gestiona la conexión con distintos sistemas gestores de bases de datos, validando credenciales y acceso. 
- AnalizadorBD.- Se encarga de procesar la estructura de la base de datos, identificando tablas, atributos, relaciones y restricciones. 
- GeneradorReporte.- Responsable de crear la documentación estructurada, incluyendo diagramas, descripciones y formatos exportables. 
- Proyecto.- Representa el conjunto de datos analizados y los resultados generados, permitiendo su almacenamiento y posterior consulta. 


### Diagramas

- Actividades  
- Secuencia  
- Clases  

---

# CONCLUSIONES

El desarrollo del sistema propuesto permite automatizar la documentación de bases de datos, reduciendo tiempos de análisis y errores humanos. Su implementación mejora la comprensión estructural de la información y facilita el mantenimiento de sistemas existentes. 

En este contexto, la incorporación de funcionalidades como el análisis estructural automatizado, la generación de diagramas entidad-relación y el uso de inteligencia artificial fortalece significativamente la calidad de la documentación generada, permitiendo a desarrolladores y analistas contar con información clara, precisa y de fácil interpretación.

Finalmente, el enfoque basado en una solución web, junto con la compatibilidad con múltiples formatos y sistemas gestores de bases de datos, garantiza altos niveles de escalabilidad, accesibilidad y adaptabilidad. Esto posiciona al sistema como una herramienta eficiente y versátil, capaz de responder a las necesidades actuales y futuras en la gestión y documentación de bases de datos.


---

# RECOMENDACIONES

Se recomienda continuar con el desarrollo del sistema incorporando mejoras orientadas a ampliar la compatibilidad con distintos sistemas gestores de bases de datos, con el propósito de incrementar su flexibilidad y aplicabilidad en diversos entornos tecnológicos.

Asimismo, resulta conveniente implementar mecanismos adicionales de seguridad, tales como el cifrado de datos, la gestión de sesiones y el control avanzado de accesos, a fin de garantizar la confidencialidad e integridad de la información procesada.

De igual manera, se sugiere optimizar el rendimiento del sistema, especialmente en el procesamiento de archivos de gran tamaño, así como mejorar la precisión de los resultados generados mediante inteligencia artificial a través de ajustes, validaciones y procesos de mejora continua.

Finalmente, se recomienda evaluar la integración del sistema con otras herramientas de desarrollo y plataformas de gestión, lo que permitiría ampliar sus funcionalidades y consolidarlo como una solución más completa dentro de entornos profesionales y empresariales.


---
