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

b) Estandares legales

c) Estandares de comunicación	](#_toc394513800)37


d) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42

e) Estandaraes de calidad y seguridad	](#_toc394513800)42

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Visión</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Introducción**

    1.1	Propósito
El propósito del presente proyecto es desarrollar un sistema que permita automatizar la documentación de bases de datos, facilitando la visualización de su estructura, relaciones y atributos. Con esta solución se busca mejorar la comprensión de las bases de datos, reducir el tiempo de análisis y minimizar errores en su gestión y mantenimiento.

    1.2	Alcance
El sistema se encuentra orientado a la generación automática de documentación a partir de bases de datos existentes, los cuales permitirá:
- Extraer información estructural (tablas, campos, claves y relaciones).
- Generar documentación organizada y clara.
- Visualizar diagramas entidad-relación.
- Exportar documentación generada.

    1.3	Definiciones, Siglas y Abreviaturas
- BD: Base de datos
- SGBD: Sistema de gestión de base de datos
- ER: Entidad-Relación
- Metadata: Información que describe la estructura de la base de datos

    1.4	Referencias
- Documentos
- Registros

    1.5	Visión General
La visión del proyecto es desarrollar un sistema funcional, claro y accesible que permita documentar automáticamente bases de datos, facilitando su entendimiento y uso. Este sistema se encontrará orientado a estudiantes y profesionales, permitiendo mejorar la organización de la información y optimizar los procesos de desarrollo y mantenimiento.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>**Posicionamiento**

    2.1	Oportunidad de negocio
Actualmente, muchas bases de datos no cuentan con documentación actualizada, lo que dificulta su comprensión y mantenimiento. Esto genera dependencia de los desarrolladores que las crearon y aumenta el riesgo de errores.
El desarrollo de este sistema representa una oportunidad para mejorar la gestión de la información, permitiendo contar con documentación clara, accesible y generada automáticamente.

    2.2	Definición del problema
La principal problemática es la falta de documentación estructurada en las bases de datos. En muchos casos, la información sobre tablas, relaciones y atributos no está disponible o se encuentra desactualizada.
Esto provoca dificultades en el mantenimiento, integración de nuevos desarrolladores y evolución de los sistemas, además de incrementar el tiempo necesario para comprender la base de datos.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>**Descripción de los interesados y usuarios**

    3.1	Resumen de los interesados
- Equipo de desarrollo.- Diego Fabrizio Andia Navarro y Clara Briyith Mayra Quispe Chileno
- Organización o usuario final del sistema

    3.2	Resumen de los usuarios
- Desarrollador.- Encargado de analizar la estructura de la base de datos y utilizar la documentación para el desarrollo de sistemas.
- Administrador de base de datos (DBA).- Responsable de gestionar la base de datos y verificar su integridad.
- Analista de sistemas.- Encargado de interpretar la información y apoyar en la toma de decisiones.

    3.3	Entorno de usuario
El sistema será una aplicación web ejecutada en computadoras, accesible desde navegadores modernos como Google Chrome, Mozilla Firefox o Microsoft Edge. El proyecto será utilizado en entornos académicos y de desarrollo de software.

    3.4	Perfiles de los interesados
- Equipo de desarrollo.- Encargado del análisis, diseño, desarrollo e implementación del sistema.
- Organización o usuario final del sistema.- Encargado de evaluar la documentación para agilizar los procesos de desarrollo.

    3.5	Perfiles de los Usuarios
- Equipo de desarrollo.- Consulta la estructura de la base de datos y analiza relaciones y dependencias.
- Administrador de base de datos (BDA).- Supervisa la correcta organización de la base de datos y valida la información generada por el sistema.
- Analista de sistemas.- Interpreta la documentación generada y utiliza la información para procesos de análisis.

    3.6	Necesidades de los interesados y usuarios
- Contar con documentación clara y organizada.
- Visualizar relaciones entre tablas.
- Reducir el tiempo de análisis.
- Mantener la documentación actualizada automáticamente.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>**Estudio de
    Factibilidad**

    4.1	Perspectiva del producto

    4.2	Resumen de capacidades

    4.3	Suposiciones y dependencias

    4.4	Costos y precios

    4.5	Licenciamiento e instalación

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

5. <span id="_Toc52661350" class="anchor"></span>**Características del producto**
- Conexión a distintos SGBD.
- Análisis automático de tablas y relaciones.
- Generación de documentación estructurada.
- Visualización gráfica (diagramas ER).
- Exportación en diferentes formatos.
- Interfaz amigable e intuitiva.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

6. <span id="_Toc52661351" class="anchor"></span>**Restricciones**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

7. <span id="_Toc52661352" class="anchor"></span>**Rangos de Calidad**
- Disponibilidad del sistema: 99%
- Precisión en la documentación generada
- Interfaz clara y fácil de usar
  
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

8. <span id="_Toc52661353" class="anchor"></span>**Precedencia y Prioridad**
- Conexión correcta a la base de datos
- Extracción de la estructura
- Generación de documentación
- Exportación de resultados

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

9. <span id="_Toc52661354" class="anchor"></span>**Otros requerimientos del producto**

b) Estandares legales
- Protección de acceso a la base de datos
- Uso seguro de credenciales

c) Estandares de comunicación	](#_toc394513800)37
- Interfaz clara y comprensible
- Mensajes de error adecuados

d) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42
- Compatible con navegadores modernos

e) Estandaraes de calidad y seguridad	](#_toc394513800)42
- Control de acceso
- Protección de datos
- Copias de seguridad

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661355" class="anchor"></span>**CONCLUSIONES**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661356" class="anchor"></span>**RECOMENDACIONES**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661357" class="anchor"></span>**BIBLIOGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661358" class="anchor"></span>**WEBGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>
