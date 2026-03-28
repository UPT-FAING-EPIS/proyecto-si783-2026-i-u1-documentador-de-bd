<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *Sistema de documentación de base de datos***

Curso: *Base de datos II*

Docente: *Mag. Patrick Cuadros Quiroga*

Integrantes:

- ***Andia Navarro, Diego Fabrizio (2022073906)***
- ***Quipe Chileno, Clara Briyith Mayra (2024080129)***

**Tacna – Perú**

***2026***

**  
**
</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

Sistema *de documentación de base de datos*

Informe de Factibilidad

Versión *{1.0}*

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

# **INDICE GENERAL**

[1. Descripción del Proyecto](#_Toc52661346)

[2. Riesgos](#_Toc52661347)

[3. Análisis de la Situación actual](#_Toc52661348)

[4. Estudio de Factibilidad](#_Toc52661349)

[4.1 Factibilidad Técnica](#_Toc52661350)

[4.2 Factibilidad económica](#_Toc52661351)

[4.3 Factibilidad Operativa](#_Toc52661352)

[4.4 Factibilidad Legal](#_Toc52661353)

[4.5 Factibilidad Social](#_Toc52661354)

[4.6 Factibilidad Ambiental](#_Toc52661355)

[5. Análisis Financiero](#_Toc52661356)

[6. Conclusiones](#_Toc52661357)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Factibilidad</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Descripción del Proyecto**

### **1.1 Nombre del proyecto**
Sistema de documentación de base de datos

### **1.2 Duración del proyecto**
3 meses

### **1.3 Descripción**
El proyecto consiste en el desarrollo de un sistema documentador de bases de datos que permita generar, organizar y mantener documentación estructurada de bases de datos de manera automatizada o semiautomatizada. Este sistema facilitará la visualización de tablas, relaciones, atributos, restricciones y otros elementos clave, permitiendo una mejor comprensión y mantenimiento de los sistemas de información.
La importancia del proyecto radica en que muchas organizaciones carecen de documentación actualizada de sus bases de datos, lo cual genera dificultades en el mantenimiento, desarrollo y escalabilidad de los sistemas. La ausencia de documentación adecuada provoca dependencia de conocimiento técnico específico y aumenta el riesgo de errores en modificaciones futuras. La propuesta permitirá centralizar la documentación, mejorar la trazabilidad de cambios y optimizar el trabajo de desarrolladores, analistas y administradores de bases de datos, alineándose con las buenas prácticas de ingeniería de software y gestión de datos.

    1.4. Objetivos
#### **1.4.1 Objetivo general**
Desarrollar un sistema documentador de bases de datos que permita organizar, visualizar y gestionar la información estructural de manera eficiente.

#### **1.4.2 Objetivos específicos**
- Implementar un módulo de conexión a bases de datos para extraer automáticamente su estructura, con el fin de obtener tablas, campos, claves y relaciones de forma automática.
- Diseñar una interfaz que permita visualizar la estructura de la base de datos, para facilitar la comprensión del modelo de datos.
- Generar documentación en formatos accesibles como PDF o HTML, el cual permita compartir y almacenar documentación fácilmente.
- Mantener un historial de cambios en la base de datos para mejorar la trazabilidad y el control de versiones.
- Facilitar la gestión y mantenimiento de bases de datos existentes, para poder reducir errores y tiempos de análisis.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>**Riesgos**

    Señale los riesgos que pudieran afectar el éxito del proyecto.}*

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>**Análisis de la Situación actual**

#### **3.1. Planteamiento del problema**
En la actualidad, muchas organizaciones y equipos de desarrollo de software presentan deficiencias en la documentación de sus bases de datos, lo que genera dificultades significativas en la gestión, mantenimiento y evolución de los sistemas de información. En la mayoría de los casos, la estructura de las bases de datos no se encuentra debidamente documentada o dicha documentación está desactualizada, incompleta o dispersa en diferentes medios.
Como antecedente, se observa que tradicionalmente la documentación de bases de datos se realiza de forma manual, mediante archivos de texto, hojas de cálculo o diagramas elaborados sin una estandarización clara. Este enfoque no solo demanda tiempo, sino que también incrementa la probabilidad de errores humanos, inconsistencias y pérdida de información relevante.
La situación actual se caracteriza por varios problemas principales. En primer lugar, existe una alta dificultad para comprender la estructura de las bases de datos, especialmente cuando los sistemas han sido desarrollados por múltiples programadores o han evolucionado a lo largo del tiempo, lo que genera una fuerte dependencia del conocimiento tácito de ciertos desarrolladores, representando un riesgo cuando estos no están disponibles.
En segundo lugar, la falta de documentación actualizada provoca errores durante la modificación o ampliación de los sistemas, ya que no se tiene claridad sobre las relaciones entre tablas, restricciones o reglas de negocio implementadas a nivel de base de datos. Esto puede derivar en fallos funcionales, pérdida de integridad de los datos o inconsistencias en la información.
Asimismo, se evidencia una carencia de herramientas automatizadas que permitan extraer, organizar y presentar la información estructural de las bases de datos. Esta limitación dificulta el análisis de sistemas complejos, especialmente en entornos donde las bases de datos contienen múltiples tablas, relaciones y dependencias.
Otro aspecto relevante es el retrabajo constante en actividades de análisis, ya que los desarrolladores deben invertir tiempo adicional en comprender estructuras existentes antes de realizar cualquier cambio, lo que reduce la productividad y aumenta los costos de desarrollo.
En consecuencia, la problemática central radica en la falta de un sistema automatizado y centralizado para la documentación de bases de datos, lo que afecta la eficiencia, calidad y mantenibilidad de los sistemas de información.
Frente a esta situación, surge la necesidad de implementar un sistema documentador de bases de datos que permita automatizar la extracción de información, organizarla de manera estructurada y facilitar su acceso, contribuyendo así a una mejor gestión, comprensión y evolución de los sistemas.

    3.2. Consideraciones de hardware y software
#### **Estaciones de trabajo**
- Procesador: Intel Core i3 o equivalente  
- Memoria RAM: 4 GB mínimo (recomendado 8 GB)  
- Almacenamiento: 256 GB (preferible SSD)  
- Conectividad: Internet estable  

### **Arquitectura del sistema**
Para el correcto funcionamiento del sistema documentador, se consideran dos componentes principales:
#### **Lado del servidor (Backend y Base de Datos)**
- Lenguaje: Python  
- Framework: Flask o Django  
- Servidor: Apache o Nginx  
- Base de datos: PostgreSQL o MySQL  
- Sistema operativo: Linux (Ubuntu/Debian)  

#### **Lado del cliente (Frontend)**
- Navegadores:
  - Google Chrome  
  - Mozilla Firefox  
  - Microsoft Edge  
- Tecnologías:
  - HTML5  
  - CSS3  
  - JavaScript  
  - Bootstrap  

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>**Estudio de
    Factibilidad**


    4.1. <span id="_Toc52661350" class="anchor"></span>Factibilidad Técnica
Actualmente, el equipo de desarrollo está conformado por un pequeño grupo de personas, donde cada integrante dispone de su propia laptop o computadora personal.
- Equipos de desarrollo: Computadoras con procesadores Intel Core i3 o superior, 8 GB de memoria RAM y almacenamiento mínimo de 256 GB en disco SSD o HDD.
- Servidor de pruebas: Puede utilizarse un equipo local o un servidor VPS con sistema operativo Linux, con una configuración mínima de 2 CPU, 4 GB de RAM.
- Cliente final: El sistema podrá ser utilizado desde cualquier dispositivo con acceso a un navegador moderno, lo que facilita su accesibilidad.
- Navegadores compatibles: Google Chrome, Mozilla Firefox, Microsoft Edge y otros navegadores modernos compatibles con tecnologías HTML5, CSS3 y JavaScript.
-Sistemas operativos compatibles:
    - Desarrollo: Windows / Linux
    - Producción: Ubuntu Server / Debian 


    4.2. <span id="_Toc52661351" class="anchor"></span>Factibilidad Económica

        El propósito del estudio de viabilidad económica, es determinar los beneficios económicos del proyecto o sistema propuesto para la organización, en contraposición con los costos.
        Como se mencionó anteriormente en el estudio de factibilidad técnica wvaluar si la institución (departamento de TI) cuenta con las herramientas necesarias para la implantación del sistema y evaluar si la propuesta requiere o no de una inversión inicial en infraestructura informática.
        Se plantearán los costos del proyecto.
        Costeo del Proyecto: Consiste en estimar los costos de los recursos Humanos, materiales o consumibles y/o máquinas) directos para completar las actividades del proyecto}.*

        Definir los siguientes costos:

        4.2.1. Costos Generales

                Los costos generales son todos los gastos realizados en accesorios y material de oficina y de uso diario, necesarios para los procesos, tales como, papeles, plumas, cartuchos de impresora, marcadores, computadora etc. Colocar tabla de costos.

        4.2.2. Costos operativos durante el desarrollo 
        
                Evaluar costos necesarios para la operatividad de las actividades de la empresa durante el periodo en el que se realizara el proyecto. Los costos de operación pueden ser renta de oficina, agua, luz, teléfono, etc.

        4.2.3. Costos del ambiente

                Evaluar si se cuenta con los requerimientos técnicos para la implantación del software como el dominio, infraestructura de red, acceso a internet, etc.

        4.2.4. Costos de personal

                Aquí se incluyen los gastos generados por el recurso humano que se necesita para el desarrollo del sistema únicamente.

                No se considerará personal para la operación y funcionamiento del sistema.

                Incluir tabla que muestra los gastos correspondientes al personal.

                Indicar organización y roles. Indicar horario de trabajo del personal.

        4.2.5.  Costos totales del desarrollo del sistema

                {Totalizar costos y realizar resumen de costo final del proyecto y la forma de pago.

   
  4.3. <span id="_Toc52661352" class="anchor"></span>Factibilidad Operativa
El sistema documentador de bases de datos ofrece importantes beneficios operativos para los equipos de desarrollo y gestión de sistemas de información. Este sistema permitirá automatizar la documentación de bases de datos, facilitando la visualización de estructuras, relaciones y atributos, lo que reduce significativamente los tiempos de análisis y comprensión.
Asimismo, optimiza el flujo de trabajo al disminuir la necesidad de documentar manualmente, reduciendo errores y mejorando la calidad de la información disponible. Esto permite que los procesos de mantenimiento, actualización y desarrollo de sistemas se realicen de manera más eficiente y organizada.
En cuanto a la capacidad operativa, el personal involucrado (desarrolladores, analistas y administradores de bases de datos) cuenta con los conocimientos necesarios para utilizar el sistema, ya que su diseño estará orientado a la facilidad de uso y no requerirá capacitación especializada.
Lista de interesados:
- Desarrolladores de software: Responsables de implementar y mantener los sistemas.
- Administradores de bases de datos: Encargados de la gestión y optimización de la información.
- Analistas de sistemas: Responsables del análisis y diseño de soluciones.
- Jefe de proyecto: Supervisa el desarrollo y uso del sistema.
- Usuarios finales (beneficiarios indirectos): Reciben sistemas más estables y eficientes.


    4.4. <span id="_Toc52661353" class="anchor"></span>Factibilidad Legal

        Determinar si existe conflicto del proyecto con restricciones legales como leyes y regulaciones del país o locales relacionadas con seguridad, protección de datos, conducta de negocio, empleo y adquisiciones.

    4.5. <span id="_Toc52661354" class="anchor"></span>Factibilidad Social
  
- Facilita el acceso a herramientas que mejoran la forma en que se organiza y comprende la información dentro del desarrollo de software. Al tratarse de un sistema accesible para cualquier usuario, contribuye a que más personas puedan entender y trabajar con bases de datos de manera más sencilla.
- La implementación del sistema ayuda a ordenar y estructurar la información, evitando la desorganización y la pérdida de conocimiento técnico. Esto permite que los equipos de trabajo no dependan únicamente de una persona para entender una base de datos, sino que cualquier miembro pueda acceder a la información de forma clara y rápida.
- Fomenta una forma de trabajo más ordenada y responsable, donde la documentación deja de ser una tarea olvidada y pasa a ser parte importante del desarrollo. Esto mejora la calidad de los proyectos y facilita la colaboración entre desarrolladores, analistas y otros usuarios.
- Promueve el uso adecuado de la información, asegurando que los datos estén bien organizados, disponibles y sean comprensibles. De tal forma que es importante en entornos donde la información es un recurso importante, ya que permite tomar decisiones más acertadas y trabajar con mayor confianza.


    4.6. <span id="_Toc52661355" class="anchor"></span>Factibilidad Ambiental

        Evaluar influencias y asuntos de índole ambiental como el impacto y repercusión en el medio ambiente.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

5. <span id="_Toc52661356" class="anchor"></span>**Análisis Financiero**

    El plan financiero se ocupa del análisis de ingresos y gastos asociados a cada proyecto, desde el punto de vista del instante temporal en que se producen. Su misión fundamental es detectar situaciones financieramente inadecuadas.
    Se tiene que estimar financieramente el resultado del proyecto.

    5.1. Justificación de la Inversión

        5.1.1. Beneficios del Proyecto

            El beneficio se calcula como el margen económico menos los costes de oportunidad, que son los márgenes que hubieran podido obtenerse de haber dedicado el capital y el esfuerzo a otras actividades.
            El beneficio, obtenido lícitamente, no es sólo una recompensa a la inversión, al esfuerzo y al riesgo asumidos por el empresario, sino que también es un factor esencial para que las empresas sigan en el  mercado e incorporen nuevas inversiones al tejido industrial y social de las naciones.
            Describir beneficios tangibles e intangibles*
            Beneficios tangibles: son de fácil cuantificación, generalmente están relacionados con la reducción de recursos o talento humano.
            Beneficios intangibles: no son fácilmente cuantificables y están relacionados con elementos o mejora en otros procesos de la organización.
>
            Ejemplo de beneficios:

            - Mejoras en la eficiencia del área bajo estudio.
            - Reducción de personal.
            - Reducción de futuras inversiones y costos.
            - Disponibilidad del recurso humano.
            - Mejoras en planeación, control y uso de recursos.
            - Suministro oportuno de insumos para las operaciones.
            - Cumplimiento de requerimientos gubernamentales.
            - Toma acertada de decisiones.
            - Disponibilidad de información apropiada.
            - Aumento en la confiabilidad de la información.
            - Mejor servicio al cliente externo e interno
            - Logro de ventajas competitivas.
            - Valor agregado a un producto de la compañía.
        
        5.1.2. Criterios de Inversión

            5.1.2.1. Relación Beneficio/Costo (B/C)

                En base a los costos y beneficios identificados se evalúa si es factible el desarrollo del proyecto. 
                Si se presentan varias alternativas de solución se evaluará cada una de ellas para determinar la mejor solución desde el punto de vista del > retorno de la inversión
                El B/C si es mayor a uno, se acepta el proyecto; si el B/C es igual a uno es indiferente aceptar o rechazar el proyecto y si el B/C es menor a uno se rechaza el proyecto

            5.1.2.2. Valor Actual Neto (VAN)
            
                Valor actual de los beneficios netos que genera el proyecto. Si el VAN es mayor que cero, se acepta el proyecto; si el VAN es igual a cero es indiferente aceptar o rechazar el proyecto y si el VAN es menor que cero se rechaza el proyecto

            5.1.2.3 Tasa Interna de Retorno (TIR)*
                Es la tasa porcentual que indica la rentabilidad promedio anual que genera el capital invertido en el proyecto. Si la TIR es mayor que el costo de oportunidad se acepta el proyecto, si la TIR es igual al costo de oportunidad es indiferente aceptar o rechazar el proyecto, si la TIR es menor que el costo de oportunidad se rechaza el proyecto

                Costo de oportunidad de capital (COK) es la tasa de interés que podría haber obtenido con el dinero invertido en el proyecto

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

6. <span id="_Toc52661357" class="anchor"></span>**Conclusiones**

Explicar los resultados del análisis de factibilidad que nos indican si el proyecto es viable y factible.
