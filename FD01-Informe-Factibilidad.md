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

# **Informe de Factibilidad**

# 

# **Versión *{1.0}***

| CONTROL DE VERSIONES |  |  |  |  |  |
| :---: | :---: | :---: | :---: | :---: | ----- |
| Versión | Hecha por | Revisada por | Aprobada por | Fecha | Motivo |
| 1.0 | MPV | ELV | ARV | 10/10/2020 | Versión Original |

**ÍNDICE GENERAL**

[1\.	Descripción del Proyecto	3](#descripción-del-proyecto)

[2\.	Riesgos	3](#riesgos)

[3\.	Análisis de la Situación actual	3](#análisis-de-la-situación-actual)

[4\.	Estudio de Factibilidad	3](#estudio-de-factibilidad)

[4.1	Factibilidad Técnica	4](#factibilidad-técnica)

[4.2	Factibilidad económica	4](#factibilidad-económica)

[4.3	Factibilidad Operativa	4](#factibilidad-operativa)

[4.4	Factibilidad Legal	4](#factibilidad-legal)

[4.5	Factibilidad Social	5](#factibilidad-social)

[4.6	Factibilidad Ambiental	5](#factibilidad-ambiental)

[5\.	Análisis Financiero	5](#análisis-financiero)

[6\.	Conclusiones	5](#conclusiones)

**Informe de Factibilidad**

1. Descripción del Proyecto  
   1. Nombre del proyecto

Sistema de documentación de base de datos

2. Duración del proyecto

2 meses

3. Descripción 

El proyecto consiste en el desarrollo de un sistema documentador de bases de datos que permita generar, organizar y mantener documentación estructurada de bases de datos de manera automatizada o semiautomatizada. Este sistema facilitará la visualización de tablas, relaciones, atributos, restricciones y otros elementos clave, permitiendo una mejor comprensión y mantenimiento de los sistemas de información.

La importancia del proyecto radica en que muchas organizaciones carecen de documentación actualizada de sus bases de datos, lo cual genera dificultades en el mantenimiento, desarrollo y escalabilidad de los sistemas. La ausencia de documentación adecuada provoca dependencia de conocimiento técnico específico y aumenta el riesgo de errores en modificaciones futuras. La propuesta permitirá centralizar la documentación, mejorar la trazabilidad de cambios y optimizar el trabajo de desarrolladores, analistas y administradores de bases de datos, alineándose con las buenas prácticas de ingeniería de software y gestión de datos.

1.4 Objetivos

       1.4.1 Objetivo general

Desarrollar un sistema documentador de bases de datos que permita organizar, visualizar y gestionar la información estructural de bases de datos de manera eficiente.

        1.4.2 Objetivos Específicos

* Implementar un módulo de conexión a bases de datos para extraer automáticamente su estructura, con el fin de obtener tablas, campos, claves y relaciones de forma automática.  
* Diseñar una interfaz que permita visualizar la estructura de la base de datos, para facilitar la comprensión del modelo de datos.  
* Generar documentación en formatos accesibles como PDF o HTML, el cual permita compartir y almacenar documentación fácilmente.  
* Mantener un historial de cambios en la base de datos para mejorar la trazabilidad y el control de versiones.  
* Facilitar la gestión y mantenimiento de bases de datos existentes, para poder reducir errores y tiempos de análisis.

2. Riesgos

El desarrollo del sistema puede verse afectado por diversos riesgos que podrían comprometer su éxito:

* **Falta de experiencia técnica:** El equipo podría presentar dificultades en el uso de tecnologías como frameworks backend o conexión a múltiples bases de datos.  
* **Limitaciones de tiempo:** El proyecto tiene una duración corta (2 meses), lo que podría afectar la calidad si no se gestiona adecuadamente.  
* **Problemas de compatibilidad:** Posibles inconvenientes al conectar con diferentes gestores de bases de datos (MySQL, PostgreSQL, etc.).  
* **Errores en la extracción de datos:** Fallos en la automatización que generen documentación incompleta o incorrecta.  
* **Dependencia tecnológica:** Dependencia de herramientas externas o librerías que podrían cambiar o dejar de ser compatibles.  
* **Fallas en el servidor:** Problemas de disponibilidad o rendimiento en el entorno de despliegue.  
* **Riesgos de seguridad:** Acceso no autorizado a bases de datos durante la extracción de información.

3. Análisis de la Situación actual  
   1. Planteamiento del problema

En la actualidad, muchas organizaciones y equipos de desarrollo de software presentan deficiencias en la documentación de sus bases de datos, lo que genera dificultades significativas en la gestión, mantenimiento y evolución de los sistemas de información. En la mayoría de los casos, la estructura de las bases de datos no se encuentra debidamente documentada o dicha documentación está desactualizada, incompleta o dispersa en diferentes medios.

Como antecedente, se observa que tradicionalmente la documentación de bases de datos se realiza de forma manual, mediante archivos de texto, hojas de cálculo o diagramas elaborados sin una estandarización clara. Este enfoque no solo demanda tiempo, sino que también incrementa la probabilidad de errores humanos, inconsistencias y pérdida de información relevante.

La situación actual se caracteriza por varios problemas principales. En primer lugar, existe una alta dificultad para comprender la estructura de las bases de datos, especialmente cuando los sistemas han sido desarrollados por múltiples programadores o han evolucionado a lo largo del tiempo, lo que genera una fuerte dependencia del conocimiento tácito de ciertos desarrolladores, representando un riesgo cuando estos no están disponibles.

En segundo lugar, la falta de documentación actualizada provoca errores durante la modificación o ampliación de los sistemas, ya que no se tiene claridad sobre las relaciones entre tablas, restricciones o reglas de negocio implementadas a nivel de base de datos. Esto puede derivar en fallos funcionales, pérdida de integridad de los datos o inconsistencias en la información.

Asimismo, se evidencia una carencia de herramientas automatizadas que permitan extraer, organizar y presentar la información estructural de las bases de datos. Esta limitación dificulta el análisis de sistemas complejos, especialmente en entornos donde las bases de datos contienen múltiples tablas, relaciones y dependencias.

Otro aspecto relevante es el retrabajo constante en actividades de análisis, ya que los desarrolladores deben invertir tiempo adicional en comprender estructuras existentes antes de realizar cualquier cambio, lo que reduce la productividad y aumenta los costos de desarrollo.

En consecuencia, la problemática central radica en la falta de un sistema automatizado y centralizado para la documentación de bases de datos, lo que afecta la eficiencia, calidad y mantenibilidad de los sistemas de información.

Frente a esta situación, surge la necesidad de implementar un sistema documentador de bases de datos que permita automatizar la extracción de información, organizarla de manera estructurada y facilitar su acceso, contribuyendo así a una mejor gestión, comprensión y evolución de los sistemas.

2. Consideraciones de hardware y software  
1. Estaciones de trabajo (desarrolladores y usuarios técnicos)

Las estaciones de trabajo estarán destinadas a los desarrolladores y posibles usuarios técnicos del sistema, por lo que deben cumplir con las siguientes características mínimas:

* Procesador: Intel Core i3 o equivalente  
* Memoria RAM: 4 GB mínimo  
* Almacenamiento: 256 GB HDD/SSD (preferiblemente SSD para mejor rendimiento).  
* Monitor: Resolución mínima de 1366x768.  
* Conectividad: Acceso a red local e internet estable.

Arquitectura del sistema  
Para el correcto funcionamiento del sistema documentador, se consideran dos componentes principales:

1. Lado del servidor (Backend y API)

En este componente se gestionará la lógica del sistema, el procesamiento de archivos, la integración con IA y la generación de documentación.

* Lenguaje de programación: Node.js  
* Framework backend: Express.js  
* API de IA: OpenAI GPT-4o-mini  
* Servidor de aplicaciones: Node.js integrado  
* Librerías principales: Multer (manejo de archivos), XLSX (procesamiento Excel), CORS  
* Entorno de desarrollo: Visual Studio Code  
* Sistema operativo: Linux (Ubuntu/Debian) para desarrollo y producción  

2. Lado del cliente (Frontend)

Este componente permitirá a los usuarios interactuar con el sistema, subir archivos, visualizar resultados y generar documentación.

* Tecnologías web:  
  * HTML5  
  * CSS3 con diseño Glassmorphism  
  * JavaScript ES6+  
* Librerías: Mermaid.js (diagramas), Marked.js (Markdown)  
* Navegadores compatibles:  
  * Google Chrome  
  * Mozilla Firefox  
  * Microsoft Edge  
* Diseño: Interfaz responsive y moderna

4. Estudio de Factibilidad

El estudio de factibilidad tiene como objetivo determinar la viabilidad del desarrollo del sistema documentador de bases de datos en términos técnicos, económicos, operativos y legales.

Para ello, se realizaron actividades como el análisis de requerimientos, evaluación de recursos disponibles, revisión de herramientas tecnológicas y estimación de costos. Este estudio fue elaborado por el equipo de desarrollo y aprobado por el docente responsable del curso.

Se espera como resultado confirmar que el proyecto es viable, sostenible y beneficioso para la organización, permitiendo mejorar la gestión de bases de datos mediante la automatización de su documentación.

1. Factibilidad Técnica

Actualmente, el equipo de desarrollo está conformado por estudiantes de Ingeniería de Sistemas con conocimientos en desarrollo web y bases de datos.

* Equipos de desarrollo: Computadoras con procesadores Intel Core i3 o superior, 8 GB de memoria RAM y almacenamiento mínimo de 256 GB en disco SSD.  
* Tecnologías principales: Node.js, Express.js, OpenAI API, HTML5/CSS3/JavaScript.  
* Librerías y frameworks: Multer, XLSX, Mermaid.js, Marked.js, CORS.  
* Servidor de desarrollo: Node.js integrado con capacidad de procesamiento local.  
* Cliente final: El sistema podrá ser utilizado desde cualquier dispositivo con acceso a un navegador moderno, facilitando su accesibilidad.  
* Navegadores compatibles: Google Chrome, Mozilla Firefox, Microsoft Edge y otros navegadores modernos compatibles con tecnologías HTML5, CSS3 y JavaScript.  
* Sistemas operativos compatibles:  
  * Desarrollo: Windows 10/11 y Linux (Ubuntu).  
  * Producción: Linux (Ubuntu Server/Debian) con Node.js.

  2. Factibilidad Económica

El estudio de viabilidad económica permite determinar si el proyecto es rentable, comparando los beneficios esperados frente a los costos de desarrollo e implementación.

Se evalúa si el equipo cuenta con los recursos necesarios o si se requiere inversión adicional. En este caso, el proyecto presenta una inversión baja, ya que se utilizan herramientas de desarrollo gratuitas y equipos propios.

Definir los siguientes costos:

1. Costos Generales 

| Concepto | Cantidad | Costo Unitario (S/.) | Total (S/.) |
| ----- | ----- | ----- | ----- |
| Hojas bond | 1 paquete | 25 | 25 |
| Lapiceros | 5 | 2 | 10 |
| Internet (mensual) | 2 meses | 80 | 160 |
| Energía eléctrica | 2 meses | 50 | 100 |
| Computadora (uso) | 1 | 0 | 0 |
| **Total** |  |  | **295** |

   2. Costos operativos durante el desarrollo 

| Concepto | Cantidad | Costo Unitario (S/.) | Total (S/.) |
| ----- | ----- | ----- | ----- |
| Internet | 2 meses | 80 | 160 |
| Energía eléctrica | 2 meses | 50 | 100 |
| Transporte | 2 meses | 40 | 80 |
| Mantenimiento equipos | 1 | 50 | 50 |
| **Total** |  |  | **390** |

      3. Costos del ambiente

El proyecto utiliza infraestructura existente, por lo que no se requiere inversión significativa:

* Dominio: No requerido (fase académica)  
* Hosting: Opcional (puede usarse local o VPS)  
* Red: Uso de internet doméstico

**Costo estimado:** S/ 0 – S/ 50 (opcional VPS)

4. Costos de personal

| Rol | Cantidad | Pago mensual (S/.) | Duración | Total (S/.) |
| ----- | ----- | ----- | ----- | ----- |
| Desarrollador Backend | 1 | 800 | 2 meses | 1600 |
| Desarrollador Frontend | 1 | 800 | 2 meses | 1600 |
| **Total** |  |  |  | **3200** |

   5. Costos totales del desarrollo del sistema 

| Tipo de costo | Monto (S/.) |
| :---- | :---- |
| Costos generales | 295 |
| Costos operativos | 260 |
| Costos ambiente | 50 |
| Costos personal | 3200 |
| **Total** | **3805** |

   3. Factibilidad Operativa

El sistema documentador de bases de datos ofrece importantes beneficios operativos para los equipos de desarrollo y gestión de sistemas de información. Este sistema permitirá automatizar la documentación de bases de datos, facilitando la visualización de estructuras, relaciones y atributos, lo que reduce significativamente los tiempos de análisis y comprensión.

Asimismo, optimiza el flujo de trabajo al disminuir la necesidad de documentar manualmente, reduciendo errores y mejorando la calidad de la información disponible. Esto permite que los procesos de mantenimiento, actualización y desarrollo de sistemas se realicen de manera más eficiente y organizada.

En cuanto a la capacidad operativa, el personal involucrado (desarrolladores, analistas y administradores de bases de datos) cuenta con los conocimientos necesarios para utilizar el sistema, ya que su diseño estará orientado a la facilidad de uso y no requerirá capacitación especializada.

Lista de interesados:

* Desarrolladores de software: responsables de implementar y mantener los sistemas.  
* Administradores de bases de datos: encargados de la gestión y optimización de la información.  
* Analistas de sistemas: responsables del análisis y diseño de soluciones.  
* Jefe de proyecto: supervisa el desarrollo y uso del sistema.  
* Organización/empresa usuaria: beneficiaria directa del sistema.  
* Usuarios finales (beneficiarios indirectos): reciben sistemas más estables y eficientes.  
  4. Factibilidad Legal

El proyecto cumple con las normativas legales vigentes relacionadas con el uso de software y manejo de información:

* No infringe derechos de autor, ya que se utilizarán herramientas de código abierto.  
* Se respetarán las normas de protección de datos personales.  
* No se almacenará información sensible sin autorización.  
* El sistema se utilizará con fines académicos y organizacionales.

Por lo tanto, no existen restricciones legales que impidan su desarrollo.

5. Factibilidad Social

* Facilita el acceso a herramientas que mejoran la forma en que se organiza y comprende la información dentro del desarrollo de software. Al tratarse de un sistema accesible para cualquier usuario, contribuye a que más personas puedan entender y trabajar con bases de datos de manera más sencilla.  
* La implementación del sistema ayuda a ordenar y estructurar la información, evitando la desorganización y la pérdida de conocimiento técnico. Esto permite que los equipos de trabajo no dependan únicamente de una persona para entender una base de datos, sino que cualquier miembro pueda acceder a la información de forma clara y rápida.  
* Fomenta una forma de trabajo más ordenada y responsable, donde la documentación deja de ser una tarea olvidada y pasa a ser parte importante del desarrollo. Esto mejora la calidad de los proyectos y facilita la colaboración entre desarrolladores, analistas y otros usuarios.  
* Promueve el uso adecuado de la información, asegurando que los datos estén bien organizados, disponibles y sean comprensibles. De tal forma que es importante en entornos donde la información es un recurso importante, ya que permite tomar decisiones más acertadas y trabajar con mayor confianza.


  6. Factibilidad Ambiental

El impacto ambiental del proyecto es mínimo debido a su naturaleza digital:

* Reducción del uso de papel al generar documentación digital.  
* Bajo consumo energético al utilizar equipos existentes.  
* No genera residuos contaminantes.

En consecuencia, el proyecto es amigable con el medio ambiente.

5. Análisis Financiero

El proyecto requiere una inversión moderada, principalmente en tiempo de desarrollo y recursos tecnológicos básicos.

*La inversión se justifica debido a que el sistema permitirá optimizar procesos, reducir errores y mejorar la gestión de bases de datos, generando beneficios tanto económicos como operativos.*

1. Justificación de la Inversión

*5.1.1 Beneficios* del Proyecto  
*{El beneficio se calcula como el margen económico menos los costes de oportunidad, que son los márgenes que hubieran podido obtenerse de haber dedicado el capital y el esfuerzo a otras actividades.*   
*El beneficio, obtenido lícitamente, no es sólo una recompensa a la inversión, al esfuerzo y al riesgo asumidos por el empresario, sino que también es un factor esencial para que las empresas sigan en el mercado e incorporen nuevas inversiones al tejido industrial y social de las naciones.*   
*Describir beneficios tangibles e intangibles*

*Beneficios tangibles: son de fácil cuantificación, generalmente están relacionados con la reducción de recursos o talento humano.*

*Beneficios intangibles: no son fácilmente cuantificables y están relacionados con elementos o mejoras en otros procesos de la organización.*

*Ejemplo de beneficios:*

* *Mejoras en la eficiencia del área bajo estudio.*  
  * *Reducción de personal.*  
    * *Reducción de futuras inversiones y costos.*  
      * *Disponibilidad del recurso humano.*  
      * *Mejoras en planeación, control y uso de recursos.*  
      * *Suministro oportuno de insumos para las operaciones.*  
      * *Cumplimiento de requerimientos gubernamentales.*  
      * *Toma acertada de decisiones.*  
      * *Disponibilidad de información apropiada.*  
      * *Aumento en la confiabilidad de la información.*  
      * *Mejor servicio al cliente externo e interno*  
      * *Logro de ventajas competitivas.*  
      * *Valor agregado a un producto de la compañía.*

* Beneficios tangibles:  
  * Reducción del tiempo de documentación en un 50%  
  * Disminución de errores en modificaciones de base de datos  
  * Reducción de costos en mantenimiento  
* Beneficios intangibles:  
  * Mejora en la organización de la información  
  * Mayor eficiencia en el trabajo del equipo  
  * Mejor toma de decisiones  
  * Incremento en la calidad del software

5.1.2 Criterios de Inversión  
   
*5.1.2.1 Relación Beneficio/Costo (B/C)*

Se estima:

* Beneficios: S/ 6000 (ahorro en tiempo y recursos)  
* Costos: S/ 3805

**B/C \= 6000 / 3805 \= 1.58**

*Como el resultado es mayor a 1, el proyecto es viable.*

                    *5.1.2.2 Valor Actual Neto (VAN)*

Se estima un VAN positivo:

**VAN ≈ S/ 2195**

Esto indica que el proyecto genera beneficios económicos.

*5.1.2.3 Tasa Interna de Retorno (TIR)*

Se estima:

**TIR ≈ 25%**

Dado que es mayor al costo de oportunidad (10%), el proyecto es rentable.

6. Conclusiones

El análisis de factibilidad demuestra que el proyecto es viable desde el punto de vista técnico, económico, operativo y legal.

Se cuenta con los recursos necesarios para su desarrollo, los costos son bajos y los beneficios son significativos. Además, el sistema contribuirá a mejorar la organización, eficiencia y calidad en la gestión de bases de datos.

Por lo tanto, se concluye que el proyecto es factible y recomendable para su implementación.

[image1]: <data:image/png;base64,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>
