<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

 **Proyecto: Sistema de documentación de Base de Datos**

Curso: Base de Datos II

Docente: Mag. Patrick Cuadros Quiroga

Integrantes:

**Andia Navarro, Diego Fabrizio (2022073906)**  
**Quispe Chileno, Clara Briyith Mayra (2024080129)**

**Tacna – Perú**  
***2026***


**  
**
</center>


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|












**Sistema *Sistema de documentación de Base de Datos***

**Documento de Visión**

**Versión *{1.0}***
**


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


**INDICE GENERAL**
#
[1.	Introducción](#_Toc52661346)

1.1	Propósito

1.2	Alcance

1.3	Definiciones, Siglas y Abreviaturas

1.4	Referencias

1.5	Visión General

[2.	Posicionamiento](#_Toc52661347)

2.1	Oportunidad de negocio

2.2	Definición del problema

[3.	Descripción de los interesados y usuarios](#_Toc52661348)

3.1	Resumen de los interesados

3.2	Resumen de los usuarios

3.3	Entorno de usuario

3.4	Perfiles de los interesados

3.5	Perfiles de los Usuarios

3.6	Necesidades de los interesados y usuarios

[4.	Vista General del Producto](#_Toc52661349)

4.1	Perspectiva del producto

4.2	Resumen de capacidades

4.3	Suposiciones y dependencias

4.4	Costos y precios

4.5	Licenciamiento e instalación

[5.	Características del producto](#_Toc52661350)

[6.	Restricciones](#_Toc52661351)

[7.	Rangos de calidad](#_Toc52661352)

[8.	Precedencia y Prioridad](#_Toc52661353)

[9.	Otros requerimientos del producto](#_Toc52661354)

a) Estandares legales

b) Estandares de comunicación ](#_toc394513800)37

c) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42

d) Estandaraes de calidad y seguridad	](#_toc394513800)42

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


**<u>Informe de Visión</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Introducción**

<p style="margin-left: 20px;">1.1 Proposito</p>

El propósito del presente proyecto es desarrollar un sistema que permita analizar, interpretar y documentar de manera automática la estructura de bases de datos, generando una representación clara, organizada y actualizada de sus componentes y relaciones.

La solución propuesta busca facilitar el entendimiento integral de la base de datos, optimizar las tareas de mantenimiento y evolución de los sistemas, y disminuir la dependencia de documentación manual, la cual suele ser incompleta o propensa a inconsistencias. Asimismo, pretende contribuir a una mejor toma de decisiones durante el desarrollo de software mediante el acceso rápido y confiable a la información estructural.

<p style="margin-left: 20px;">1.2 Alcance</p>

El sistema se encuentra orientado a la generación automática de documentación a partir de bases de datos existentes, los cuales permitirá:

<ul style="margin-left: 40px;">
  <li>Extraer información estructural (tablas, campos, claves y relaciones).</li>
  <li>Generar documentación organizada y clara.</li>
  <li>Visualizar diagramas entidad-relación.</li>
  <li>Exportar documentación generada.</li>
</ul>

<p style="margin-left: 20px;">1.3 Definiciones, Siglas y Abreviaturas</p>

<ul style="margin-left: 40px;">
  <li>BD: Base de datos</li>
  <li>SGBD: Sistema de gestión de base de datos</li>
  <li>ER: Entidad-Relación</li>
  <li>Metadata: Información que describe la estructura de la base de datos</li>
</ul>

<p style="margin-left: 20px;">1.4 Referencias</p>

<ul style="margin-left: 40px;">
  <li>Documentos</li>
  <li>Registros</li>
</ul>

<p style="margin-left: 20px;">1.5 Visión General</p>

La visión del proyecto es desarrollar un sistema que permita documentar de forma automática y estructurada las bases de datos, proporcionando una representación clara y comprensible de su organización interna.

Este sistema estará orientado a facilitar el análisis de la información almacenada, permitiendo a estudiantes y profesionales comprender de manera rápida las relaciones, dependencias y componentes que conforman una base de datos. Asimismo, busca convertirse en una herramienta de apoyo para mejorar la gestión, mantenimiento y evolución de los sistemas de información.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


2. <span id="_Toc52661347" class="anchor"></span>**Posicionamiento**

<p style="margin-left: 20px;">2.1 Oportunidad de negocio</p>

En la actualidad, muchas bases de datos carecen de documentación actualizada o adecuada, lo que dificulta su interpretación y genera dependencia del conocimiento de los desarrolladores que participaron en su creación. Esta situación incrementa los tiempos de análisis y el riesgo de errores durante el mantenimiento o modificación de los sistemas.

En este contexto, el desarrollo de un sistema documentador representa una oportunidad para mejorar la gestión de la información, al permitir la generación automática de documentación estructurada, accesible y actualizada, facilitando así el trabajo colaborativo y la continuidad de los proyectos.

<p style="margin-left: 20px;">2.2 Definición del problema</p>

La problemática principal radica en la ausencia o deficiencia de documentación en las bases de datos, lo que limita la comprensión de su estructura y funcionamiento. En muchos casos, la información sobre tablas, relaciones y atributos no se encuentra disponible o está desactualizada, dificultando su uso adecuado.

Esta situación genera inconvenientes en el mantenimiento de los sistemas, en la incorporación de nuevos desarrolladores y en la correcta evolución de las aplicaciones, además de aumentar el tiempo requerido para analizar y comprender la base de datos.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


3. <span id="_Toc52661348" class="anchor"></span>**Descripción de los interesados y usuarios**

<p style="margin-left: 20px;">3.1 Resumen de los interesados</p>

| **Interesado** | **Representante** |
|------------|--------------|
| Equipo de desarrollo | Diego Fabrizio Andia Navarro y Clara Briyith Mayra Quispe Chileno |
| Usuario final / organización | Instituciones o equipos de desarrollo de software |

<p style="margin-left: 20px;">3.2 Resumen de los usuarios</p>

| **Nombre** | **Descripción** |
|--------|-------------|
| Desarrollador | Usuario encargado de analizar la estructura de la base de datos y utilizar la documentación generada para el desarrollo de sistemas |
| Administrador de base de datos (DBA) | Responsable de la gestión, control y validación de la integridad de la base de datos |
| Analista de sistemas | Usuario encargado de interpretar la información documentada y utilizarla para el análisis y toma de decisiones |

<p style="margin-left: 20px;">3.3 Entorno de usuario</p>

El sistema será una aplicación web accesible desde equipos de cómputo, utilizando navegadores modernos (Google Chrome, Mozilla Firefox o Microsoft Edge).

Su uso estará orientado principalmente a entornos académicos y de desarrollo de software, donde los usuarios requieran analizar y documentar estructuras de bases de datos de manera eficiente. Asimismo, el sistema podrá ser utilizado tanto en redes locales como mediante conexión a Internet, dependiendo del entorno de implementación.

<ul style="margin-left: 40px;">
  <li>Desarrollador: Requiere acceso a la estructura de la base de datos y visualización de relaciones para el desarrollo de aplicaciones.</li>
  <li>Administrador de Base de Datos (DBA): Necesita validar la organización de la base de datos y verificar la consistencia de la información documentada.</li>
  <li>Analista de sistemas: Utiliza la documentación generada para comprender la estructura y apoyar en procesos de análisis y toma de decisiones</li>
</ul>

<p style="margin-left: 20px;">3.4 Perfiles de los interesados</p>

<ul style="margin-left: 40px;">
  <li>Perfil del equipo de desarrollo</li>
</ul>

| **Campo** | **Descripción** |
|------|-------------|
| **Representante** | Integrantes del proyecto |
| **Descripción** | Encargados del análisis, diseño, desarrollo, pruebas e implementación del sistema |
| **Tipo** | Interno |
| **Responsabilidad** | Desarrollar el sistema cumpliendo con los requerimientos establecidos y garantizar su correcto funcionamiento |
| **Criterios de éxito** | Cumplimiento de plazos, funcionalidad del sistema y calidad de la documentación generada |
| **Implicación** | Alta durante todas las fases del proyecto |

<ul style="margin-left: 40px;">
  <li>Perfil del usuario final/organización</li>
</ul>

| **Campo** | **Descripción** |
|------|-------------|
| **Representante** | Institución o equipo de desarrollo que utilice el sistema |
| **Descripción** | Usuario que hará uso del sistema para analizar y documentar bases de datos |
| **Tipo** | Externo |
| **Responsabilidad** | Utilizar la documentación generada para mejorar los procesos de desarrollo y mantenimiento |
| **Criterios de éxito** | Facilidad de uso, claridad de la documentación y utilidad en entornos reales |
| **Implicación** | Media durante la evaluación y uso del sistema |

<p style="margin-left: 20px;">3.5 Perfiles de los Usuarios</p>

<ul style="margin-left: 40px;">
  <li>Perfil de desarrollador</li>
</ul>

| **Campo** | **Descripción** |
|------|-------------|
| **Representante** | Desarrollador |
| **Descripción** | Usuario que utiliza la documentación para comprender la estructura de la base de datos |
| **Tipo** | Interno |
| **Responsabilidad** | Analizar tablas, relaciones y atributos para desarrollar o modificar sistemas |
| **Criterios de éxito** | Acceso rápido a la información, claridad en la documentación y facilidad de navegación |
| **Implicación** | Alta, ya que depende directamente de la calidad de la documentación generada |

<ul style="margin-left: 40px;">
  <li>Perfil de administrador de base de datos (DBA)</li>
</ul>

| **Campo** | **Descripción** |
|------|-------------|
| **Representante** | DBA |
| **Descripción** | Responsable de supervisar la integridad y organización de la base de datos |
| **Tipo** | Interno |
| **Responsabilidad** | Validar la estructura de la base de datos y asegurar que la documentación sea correcta |
| **Criterios de éxito** | Precisión de la información, consistencia de los datos y confiabilidad del sistema |
| **Implicación** | Alta, debido a su rol crítico en la gestión de la base de datos |

<ul style="margin-left: 40px;">
  <li>Perfil de analista de sistemas</li>
</ul>

| **Campo** | **Descripción** |
|------|-------------|
| **Representante** | Analista |
| **Descripción** | Usuario que interpreta la información documentada para apoyar procesos de análisis |
| **Tipo** | Interno |
| **Responsabilidad** | Evaluar la estructura de la base de datos y apoyar en la toma de decisiones |
| **Criterios de éxito** | Comprensión clara de la información, rapidez en el análisis y acceso estructurado a los datos |
| **Implicación** | Media a alta, dependiendo del uso del sistema en el análisis |

<p style="margin-left: 20px;">3.6 Necesidades de los interesados y usuarios</p>

<ul style="margin-left: 40px;">
  <li>Contar con un mecanismo automatizado que permita obtener información de la base de datos sin intervención manual.</li>
  <li>Comprender de forma rápida la organización interna de la base de datos.</li>
  <li>Disponer de una representación clara de las dependencias entre entidades para facilitar el análisis del sistema.</li>
  <li>Minimizar el esfuerzo requerido en la interpretación de esquemas complejos o poco documentados.</li>
  <li>Facilitar el análisis técnico para actividades de desarrollo, mantenimiento o mejora de sistemas.</li>
</ul>


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


4. <span id="_Toc52661349" class="anchor"></span>**Estudio de
    Factibilidad**

<p style="margin-left: 20px;">4.1 Perspectiva del producto</p>

El sistema se plantea como una solución tecnológica orientada a la automatización del proceso de documentación de bases de datos, permitiendo analizar su estructura interna y generar información clara, organizada y accesible para los usuarios.

A diferencia de los métodos tradicionales, donde la documentación se realiza de forma manual, esta propuesta busca centralizar y simplificar dicho proceso mediante una aplicación web que se conecte directamente a la base de datos y obtenga su estructura en tiempo real.

El objetivo principal es facilitar la comprensión, mantenimiento y evolución de las bases de datos, contribuyendo a mejorar la eficiencia del trabajo de desarrolladores, administradores y analistas, así como reducir errores derivados de la falta de documentación actualizada.

<p style="margin-left: 20px;">4.2 Resumen de capacidades</p>

El sistema contará con las siguientes capacidades principales:

<ul style="margin-left: 40px;">
  <li>Analizar automáticamente la estructura de la base de datos, identificando tablas, campos, claves primarias y foráneas.</li>
  <li>Detectar y representar relaciones entre entidades de forma estructurada.</li>
  <li>Generar documentación detallada de cada componente de la base de datos.</li>
  <li>Permitir la exportación de la documentación en formatos accesibles.</li>
  <li>Ofrecer una interfaz sencilla que facilite la navegación de la información generada.</li>
</ul>

<p style="margin-left: 20px;">4.3 Suposiciones y dependencias</p>

Para el correcto funcionamiento del sistema, se consideran las siguientes suposiciones y dependencias:

<ul style="margin-left: 40px;">
  <li>Los equipos utilizados contarán con navegadores web compatibles con tecnologías modernas.</li>
  <li>El sistema dependerá de la compatibilidad con los sistemas gestores de bases de datos soportados.</li>
  <li>La estructura de la base de datos será lo suficientemente consistente para permitir su análisis automático.</li>
  <li>Los usuarios tendrán conocimientos básicos sobre bases de datos para interpretar la información generada.</li>
</ul>

<p style="margin-left: 20px;">4.4 Costos y precios</p>

| **Tipo de costo**   | **Costos Mensuales** | **Costos Totales** |
|---------------------|----------------------|--------------------|
| Costos generales    | S/. 147.50           | S/. 295.00         |
| Costos operativos   | S/. 130.00           | S/. 260.00         |
| Costos ambiente     | S/. 25.00            | S/. 50.00          |
| Costos personal     | S/. 1600.00          | S/. 3200.00        |
| **Total**           | **S/. 1902.50**      | **S/. 3805.00**    |

<p style="margin-left: 20px;">4.5 Licenciamiento e instalación</p>

El sistema será implementado como una aplicación web, lo que permitirá su acceso a través de navegadores sin requerir instalación adicional en los dispositivos de los usuarios.

En cuanto al licenciamiento, se plantea un enfoque de uso académico o institucional, con posibilidad de ampliación a un modelo más formal en caso de futuras versiones.

Asimismo, el sistema contemplará mecanismos de autenticación para controlar el acceso y garantizar la seguridad de la información.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


5. <span id="_Toc52661350" class="anchor"></span>**Características del producto**

<ul style="margin-left: 40px;">
  <li>Conexión a distintos SGBD.</li>
  <li>Análisis automático de tablas y relaciones.</li>
  <li>Generación de documentación estructurada.</li>
  <li>Visualización gráfica (diagramas ER).</li>
  <li>Exportación en diferentes formatos.</li>
  <li>Interfaz amigable e intuitiva.</li>
</ul>


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


6. <span id="_Toc52661351" class="anchor"></span>**Restricciones**

<ul style="margin-left: 40px;">
  <li>El sistema requiere conexión a internet o red local para establecer la comunicación con la base de datos y permitir el acceso a la aplicación.</li>
  <li>La precisión de la documentación generada dependerá de la estructura y calidad de la base de datos analizada.</li>
  <li>El desarrollo del sistema se encuentra condicionado por el tiempo y recursos disponibles del equipo de trabajo, al tratarse de un proyecto académico.</li>
  <li>El sistema no modificará la base de datos, limitándose únicamente a la lectura de su estructura, lo cual restringe funcionalidades relacionadas a edición o administración de datos.</li>
  <li>El uso adecuado del sistema requiere que los usuarios cuenten con conocimientos básicos sobre bases de datos para interpretar correctamente la documentación generada.</li>
</ul>


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


7. <span id="_Toc52661352" class="anchor"></span>**Rangos de Calidad**

<ul style="margin-left: 40px;">
  <li>El sistema deberá mantener una disponibilidad del 99% durante su uso.</li>
  <li>El tiempo de respuesta en la carga y visualización de la documentación no deberá superar los 5 segundos.</li>
  <li>La documentación generada deberá reflejar la estructura de la base de datos.</li>
  <li>La interfaz deberá ser clara y facilitar la navegación entre los distintos elementos.</li>
</ul>

  
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


8. <span id="_Toc52661353" class="anchor"></span>**Precedencia y Prioridad**

<ul style="margin-left: 40px;">
  <li>Obtener y analizar la estructura (tablas, campos y relaciones).</li>
  <li>Generar la documentación de forma organizada.</li>
  <li>Permitir la visualización clara de la información.</li>
  <li>Habilitar la exportación de los resultados</li>
</ul>


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


9. <span id="_Toc52661354" class="anchor"></span>**Otros requerimientos del producto**

<p style="margin-left: 20px;">a) Estandares legales</p>

Uso adecuado y seguro de las credenciales de acceso a la base de datos.

<p style="margin-left: 20px;">b) Estandares de comunicación</p>

Mensajes claros durante los procesos de conexión, análisis y generación de documentación.

<p style="margin-left: 20px;">c) Estandaraes de cumplimiento de la plataforma	</p>

Compatibilidad con navegadores web modernos.

<p style="margin-left: 20px;">d) Estandaraes de calidad y seguridad</p>

Control de acceso al sistema, protección de la información obtenida, y operación en modo lectura sin modificar la base de datos.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


<span id="_Toc52661355" class="anchor"></span>**CONCLUSIONES**

El sistema documentador de bases de datos se plantea como una solución orientada a facilitar la comprensión de la estructura interna de las bases de datos, especialmente en contextos donde la documentación es limitada o inexistente. Mediante la automatización de este proceso, se logra generar información clara y organizada sobre tablas, atributos y relaciones.

Su implementación permite reducir el tiempo de análisis, mejorar el mantenimiento de los sistemas y apoyar el trabajo de desarrolladores, administradores y analistas, proporcionando una visión estructurada de la información. De esta manera, el sistema contribuye a optimizar la gestión de bases de datos y a disminuir errores asociados a la falta de documentación.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


<span id="_Toc52661356" class="anchor"></span>**RECOMENDACIONES**

Se recomienda realizar pruebas periódicas para asegurar la precisión de la documentación generada y garantizar que refleje correctamente la estructura de la base de datos. Asimismo, es importante que los usuarios cuenten con una capacitación básica que les permita interpretar adecuadamente la información proporcionada por el sistema.

Por otro lado, se sugiere ampliar progresivamente la compatibilidad con distintos sistemas gestores de bases de datos y mejorar la visualización de la información, con el fin de incrementar la utilidad del sistema en diferentes entornos de desarrollo.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


<span id="_Toc52661357" class="anchor"></span>**BIBLIOGRAFIA**

<ul style="margin-left: 40px;">
  <li>Silberschatz, A., Korth, H. F., & Sudarshan, S. (2019). Fundamentos de bases de datos. McGraw-Hill. </li>
  <li>Elmasri, R., & Navathe, S. (2016). Sistemas de bases de datos. Pearson. </li>
</ul>


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


<span id="_Toc52661358" class="anchor"></span>**WEBGRAFIA**

<ul style="margin-left: 40px;">
  <li>Mysql Documentación. (n.d.). Mysql.com. https://dev.mysql.com/doc/ </li>
  <li>PosgreSQL Documentación. (n.d.). Postgresql.org. https://www.postgresql.org/docs/ </li>
  <li>SQL tutorial. (n.d.). W3schools.com. https://www.w3schools.com/sql/ </li>
</ul>


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

