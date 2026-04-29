<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERÍA**

**Escuela Profesional de Ingeniería de Sistemas**

 **Proyecto: Sistema de documentación de Base de Datos**

Curso: Base de Datos II

Docente: Mag. Patrick Cuadros Quiroga

Integrantes:

**Andia Navarro, Diego Fabrizio (2022073906)**  
**Quispe Chileno, Clara Briyith Mayra (2024080129)**

**Tacna – Perú**  
***2026***

# **Sistema *de documentación de base de datos***

# **Propuesta de Proyecto**

# 

# **Versión *{1.0}***

| CONTROL DE VERSIONES |  |  |  |  |  |
| :---: | :---: | :---: | :---: | :---: | ----- |
| Versión | Hecha por | Revisada por | Aprobada por | Fecha | Motivo |
| 1.0 | MPV | ELV | ARV | 10/10/2020 | Versión Original |

**ÍNDICE GENERAL**

[1\.	Resumen Ejecutivo	3](#resumen-ejecutivo)

[2\.	Introducción	3](#introducción)

[3\.	Objetivos	4](#objetivos)

[3.1	Objetivo General	4](#objetivo-general)

[3.2	Objetivos Específicos	4](#objetivos-específicos)

[4\.	Alcance y Limitaciones	4](#alcance-y-limitaciones)

[5\.	Metodología	5](#metodología)

[6\.	Cronograma	5](#cronograma)

[7\.	Presupuesto	6](#presupuesto)

[8\.	Riesgos y Mitigación	6](#riesgos-y-mitigación)

[9\.	Conclusiones	7](#conclusiones)

**Propuesta de Proyecto**

1. Resumen Ejecutivo

El presente proyecto propone el desarrollo de un sistema de documentación automática de bases de datos utilizando inteligencia artificial. Este sistema permitirá analizar la estructura de bases de datos relacionales y no relacionales, generando documentación técnica detallada, diagramas entidad-relación y reportes de auditoría que identifiquen posibles problemas de diseño.

La solución busca resolver la problemática común de falta de documentación en bases de datos, que genera dificultades en el mantenimiento, evolución y comprensión de sistemas de información. Mediante el uso de tecnologías modernas como Node.js, Express y la API de OpenAI, se desarrollará una aplicación web que facilite el análisis automatizado de esquemas de datos.

El proyecto tiene una duración estimada de 2 meses, con un presupuesto moderado que incluye recursos tecnológicos y tiempo de desarrollo. Se espera que el sistema contribuya significativamente a mejorar las prácticas de documentación en el ámbito académico y profesional.

1. Introducción

En el contexto actual del desarrollo de software, las bases de datos representan uno de los componentes más críticos de cualquier sistema de información. Sin embargo, la documentación adecuada de estos elementos suele ser insuficiente o inexistente, lo que genera múltiples problemas durante el ciclo de vida del software.

La documentación manual de bases de datos requiere tiempo considerable y está sujeta a errores humanos, además de volverse rápidamente obsoleta cuando se realizan modificaciones en la estructura. Esta situación se agrava en entornos donde múltiples desarrolladores trabajan en el mismo proyecto, o cuando el sistema evoluciona con el tiempo.

Frente a esta problemática, surge la oportunidad de desarrollar una herramienta automatizada que no solo genere documentación técnica, sino que también analice la calidad del diseño de la base de datos, identifique inconsistencias y proponga mejoras. La incorporación de inteligencia artificial permite interpretar estructuras complejas y generar análisis detallados que serían difíciles de obtener mediante métodos tradicionales.

El proyecto se enmarca dentro del curso de Base de Datos II, buscando aplicar los conocimientos adquiridos en un desarrollo práctico que demuestre la viabilidad de soluciones innovadoras para problemas reales en el ámbito de la ingeniería de sistemas.

1. Objetivos

1. Objetivo General

Desarrollar un sistema web que permita documentar y auditar bases de datos de manera automatizada utilizando inteligencia artificial, facilitando el análisis, mantenimiento y mejora de sistemas de información.

2. Objetivos Específicos

* Implementar un parser que permita extraer la estructura de bases de datos desde archivos SQL, JSON y otros formatos comunes.
* Integrar un modelo de inteligencia artificial para generar documentación técnica detallada y análisis de calidad.
* Desarrollar una interfaz web intuitiva que permita visualizar la estructura de la base de datos y los resultados del análisis.
* Generar diagramas entidad-relación automáticos utilizando tecnologías de visualización como Mermaid.js.
* Implementar funcionalidades de auditoría que identifiquen problemas de diseño, redundancias y oportunidades de mejora.
* Crear un sistema de reportes que permita exportar la documentación en formatos accesibles como PDF o HTML.

1. Alcance y Limitaciones

El alcance del proyecto incluye el desarrollo completo de una aplicación web con las siguientes funcionalidades principales:

* Carga y análisis de archivos de bases de datos (SQL, JSON, DBML, etc.)
* Generación automática de documentación técnica
* Creación de diagramas ER interactivos
* Análisis de auditoría con recomendaciones de mejora
* Interfaz web responsive y moderna
* Soporte para bases de datos relacionales y no relacionales

Las limitaciones del proyecto incluyen:

* No se contempla la conexión directa a bases de datos en producción por cuestiones de seguridad
* El análisis se limita a la estructura de la base de datos, no incluye análisis de datos contenidos
* La precisión del análisis depende de la calidad del archivo de entrada proporcionado
* El sistema está diseñado para uso académico y profesional básico, no para entornos empresariales críticos

1. Metodología

Para el desarrollo del proyecto se utilizará una metodología ágil basada en el marco SCRUM, adaptada al contexto académico y al tiempo disponible. Las fases principales incluyen:

1. **Planificación:** Definición de requisitos, alcance y cronograma
2. **Análisis y Diseño:** Modelado de la arquitectura del sistema y diseño de interfaces
3. **Desarrollo:** Implementación de funcionalidades por módulos
4. **Pruebas:** Validación del funcionamiento y corrección de errores
5. **Documentación:** Elaboración de manuales y reportes finales

El proyecto se desarrollará utilizando tecnologías modernas y herramientas de código abierto, priorizando la calidad del código y las buenas prácticas de desarrollo.

1. Cronograma

El proyecto tiene una duración total de 8 semanas, distribuidas de la siguiente manera:

| Semana | Actividades | Entregables |
|--------|-------------|-------------|
| 1 | Análisis de requisitos y diseño inicial | Documento de requisitos, mockups de interfaz |
| 2-3 | Desarrollo del backend y parser de archivos | API funcional, módulo de análisis |
| 4-5 | Desarrollo del frontend e integración con IA | Interfaz web completa, integración OpenAI |
| 6 | Desarrollo de funcionalidades avanzadas | Diagramas ER, sistema de auditoría |
| 7 | Pruebas y corrección de errores | Sistema funcional, casos de prueba |
| 8 | Documentación final y presentación | Informes completos, demo del sistema |

1. Presupuesto

El presupuesto estimado del proyecto es de S/ 3,800.00, distribuido de la siguiente manera:

| Concepto | Cantidad | Costo Unitario | Total |
|----------|----------|---------------|-------|
| Recursos Humanos (desarrollo) | 60 horas | S/ 50.00 | S/ 3,000.00 |
| Herramientas y software | - | - | S/ 200.00 |
| Servicios en la nube (OpenAI API) | - | - | S/ 300.00 |
| Materiales de oficina | - | - | S/ 100.00 |
| Contingencia (10%) | - | - | S/ 200.00 |
| **Total** | | | **S/ 3,800.00** |

Los costos se mantienen bajos gracias al uso de tecnologías open source y recursos académicos disponibles.

1. Riesgos y Mitigación

Los principales riesgos identificados y sus estrategias de mitigación incluyen:

* **Complejidad técnica:** Riesgo de dificultades en la integración con la API de OpenAI.
  * *Mitigación:* Realizar pruebas de integración tempranas y contar con alternativas.

* **Tiempo limitado:** El plazo de 2 meses puede ser ajustado.
  * *Mitigación:* Planificación detallada y seguimiento semanal del progreso.

* **Dependencia de servicios externos:** La API de OpenAI puede tener limitaciones.
  * *Mitigación:* Implementar manejo de errores y límites de uso.

* **Cambios en requisitos:** Posibles modificaciones durante el desarrollo.
  * *Mitigación:* Comunicación constante con el docente y flexibilidad en el alcance.

1. Conclusiones

La propuesta de desarrollo del sistema de documentación de bases de datos representa una oportunidad valiosa para aplicar conocimientos teóricos en un proyecto práctico que resuelve un problema real en el ámbito del desarrollo de software.

El proyecto combina tecnologías modernas con un enfoque innovador, utilizando inteligencia artificial para automatizar tareas que tradicionalmente requieren esfuerzo manual considerable. Se espera que el resultado final no solo cumpla con los objetivos académicos del curso, sino que también genere un producto funcional que pueda ser utilizado en contextos profesionales.

La viabilidad técnica, económica y operativa del proyecto, junto con los beneficios potenciales para la comunidad académica y profesional, justifican la aprobación y ejecución de esta propuesta.</content>
<parameter name="filePath">/workspaces/proyecto-si783-2026-i-u1-documentador-de-bd/FD06-EPIS-PropuestaProyecto.md