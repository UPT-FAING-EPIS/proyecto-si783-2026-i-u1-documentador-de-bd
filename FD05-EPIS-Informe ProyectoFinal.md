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

# DOCUMENTO DE INFORME - PROYECTO FINAL
## Sistema de documentación de Base de Datos  
**Versión 1.0**

---


# ÍNDICE GENERAL

- [Antecedentes](#antecedentes)

- [Planteamiento del Problema](#planteamiento-del-problema)  
  - [Problema](#problema)  
  - [Justificación](#justificación)  
  - [Alcance](#alcance)  

- [Objetivos](#objetivos)  
  - [Objetivo General](#objetivo-general)  
  - [Objetivos Específicos](#objetivos-específicos)  

- [Marco Teórico](#marco-teórico)  
  - [Bases de Datos](#bases-de-datos)  
  - [Documentación de Bases de Datos](#documentación-de-bases-de-datos)  
  - [Inteligencia Artificial](#inteligencia-artificial)  
  - [Auditoría de Datos](#auditoría-de-datos)  

- [Desarrollo de la Solución](#desarrollo-de-la-solución)

- [Análisis de Factibilidad](#análisis-de-factibilidad)  
  - [Factibilidad Técnica](#factibilidad-técnica)  
  - [Factibilidad Económica](#factibilidad-económica)  
  - [Factibilidad Operativa](#factibilidad-operativa)  
  - [Factibilidad Social](#factibilidad-social)  
  - [Factibilidad Legal](#factibilidad-legal)  
  - [Factibilidad Ambiental](#factibilidad-ambiental)  

- [Tecnología de Desarrollo](#tecnología-de-desarrollo)

- [Metodología de Implementación](#metodología-de-implementación)

- [Cronograma](#cronograma)

- [Presupuesto](#presupuesto)

- [Conclusiones](#conclusiones)

- [Recomendaciones](#recomendaciones)
- 
---
# ANTECEDENTES

En la actualidad, las bases de datos se han convertido en un componente fundamental dentro de cualquier sistema de información, ya que permiten almacenar, organizar y gestionar grandes volúmenes de datos de manera estructurada. Sin embargo, a pesar de su importancia, en muchos proyectos no se le da la debida atención a la documentación de la base de datos.

En entornos académicos y profesionales es común encontrar bases de datos sin documentación clara o con información incompleta, lo que dificulta su comprensión, mantenimiento y evolución. Esta situación se vuelve más crítica cuando el sistema crece o cuando nuevos desarrolladores deben integrarse al proyecto sin contar con una guía adecuada.

Por otro lado, el avance de la inteligencia artificial ha permitido automatizar diversas tareas dentro del desarrollo de software, incluyendo el análisis de estructuras de datos. Esto abre una oportunidad para mejorar la forma en que se documentan las bases de datos, reduciendo el esfuerzo manual y aumentando la calidad de la información generada.

---

# PLANTEAMIENTO DEL PROBLEMA

## Problema

Actualmente, muchas bases de datos carecen de una documentación adecuada, lo que genera dificultades en su análisis, mantenimiento y modificación. Esta falta de documentación provoca que los desarrolladores tengan que invertir más tiempo en entender la estructura de la base de datos, aumentando la probabilidad de cometer errores.

Además, en muchos casos existen problemas como relaciones mal definidas, redundancia de datos, falta de normalización y ausencia de estándares en el diseño. La documentación manual, cuando se realiza, suele ser incompleta, desactualizada o inconsistente.

## Justificación

El desarrollo de este proyecto se justifica por la necesidad de contar con una herramienta que permita documentar bases de datos de manera automática, clara y eficiente.

La incorporación de inteligencia artificial permite no solo generar documentación, sino también analizar la calidad del diseño de la base de datos, identificar posibles errores y proponer mejoras. Esto representa una ventaja importante frente a los métodos tradicionales, ya que reduce el tiempo de trabajo y mejora la precisión de los resultados.

Además, este sistema puede ser utilizado tanto en entornos académicos como profesionales, aportando valor en el aprendizaje y en la optimización de procesos de desarrollo.

## Alcance

El sistema estará enfocado en el análisis y documentación de bases de datos, incluyendo las siguientes funcionalidades:

- Generación automática de documentación técnica  
- Creación de diccionario de datos  
- Identificación de relaciones entre tablas  
- Detección de errores estructurales  
- Generación de reportes de auditoría  
- Propuestas de mejora en el diseño  

El sistema no contempla la modificación directa de la base de datos ni la ejecución automática de cambios, ya que su objetivo principal es el análisis y la documentación.

---

# OBJETIVOS

## Objetivo General

Desarrollar un sistema que permita analizar y documentar bases de datos de manera automatizada utilizando inteligencia artificial.

## Objetivos Específicos

- Automatizar la generación de documentación de bases de datos  
- Identificar y analizar relaciones entre tablas  
- Detectar problemas de diseño como redundancias o inconsistencias  
- Generar recomendaciones para mejorar la estructura  
- Reducir el tiempo requerido para la documentación manual  

---

# MARCO TEÓRICO

## Bases de Datos

Las bases de datos son sistemas diseñados para almacenar información de forma organizada, permitiendo su acceso y manipulación de manera eficiente. Son utilizadas en diversos ámbitos, desde aplicaciones web hasta sistemas empresariales.

## Documentación de Bases de Datos

La documentación consiste en describir la estructura de la base de datos, incluyendo tablas, atributos, relaciones y restricciones. Su objetivo es facilitar la comprensión del sistema y permitir su mantenimiento.

## Inteligencia Artificial

La inteligencia artificial permite analizar grandes cantidades de información y generar resultados automatizados. En este proyecto, se utiliza para interpretar la estructura de la base de datos y generar documentación y análisis.

## Auditoría de Datos

La auditoría de datos se enfoca en evaluar la calidad de la información, detectando errores, inconsistencias y oportunidades de mejora dentro de una base de datos.

---

# DESARROLLO DE LA SOLUCIÓN

El sistema propuesto permitirá al usuario cargar o conectarse a una base de datos para analizar su estructura de forma automática.

Una vez que se obtiene la información, el sistema procesa los datos mediante un módulo de análisis estructural y posteriormente utiliza inteligencia artificial para interpretar la información. Como resultado, se genera documentación técnica detallada, junto con un informe de auditoría que incluye observaciones y recomendaciones.

El sistema está diseñado de forma modular, lo que permite que cada componente cumpla una función específica dentro del proceso general.

---

# ANÁLISIS DE FACTIBILIDAD

## Factibilidad Técnica

El proyecto es técnicamente viable, ya que existen herramientas y tecnologías que permiten desarrollar tanto la parte de análisis como la integración con inteligencia artificial.

## Factibilidad Económica

El costo del proyecto es relativamente bajo, ya que se pueden utilizar tecnologías open source y servicios gratuitos o de bajo costo.

## Factibilidad Operativa

El sistema es fácil de utilizar y no requiere conocimientos avanzados, lo que facilita su adopción por parte de estudiantes y profesionales.

## Factibilidad Social

El proyecto contribuye a mejorar la calidad del desarrollo de software, facilitando la comprensión de sistemas y reduciendo errores.

## Factibilidad Legal

Se debe tener en cuenta el manejo adecuado de la información, especialmente si se trabaja con datos sensibles o privados.

## Factibilidad Ambiental

El uso de documentación digital reduce el consumo de papel, contribuyendo al cuidado del medio ambiente.

---

# TECNOLOGÍA DE DESARROLLO

El sistema será desarrollado utilizando tecnologías modernas que permitan un buen rendimiento y escalabilidad:

- **Backend:** Node.js o Python  
- **Frontend:** HTML, CSS y JavaScript  
- **Base de datos:** MySQL o PostgreSQL  
- **Inteligencia Artificial:** Modelos de lenguaje  
- **Plataforma:** Aplicación web  

---

# METODOLOGÍA DE IMPLEMENTACIÓN

Para el desarrollo del sistema se utilizará una metodología basada en documentación:

- **Documento de Visión:** define los objetivos, alcance y actores del sistema  
- **SRS:** describe los requisitos funcionales y no funcionales  
- **SAD:** define la arquitectura del sistema  

Esta metodología permite una mejor organización del proyecto y reduce riesgos durante el desarrollo.

---

# CRONOGRAMA

El desarrollo del proyecto se organiza en diferentes etapas que permiten avanzar de forma ordenada, asegurando que cada fase cumpla con sus objetivos antes de pasar a la siguiente.

| Fase | Actividad | Duración | Descripción |
|------|----------|---------|------------|
| 1 | Análisis del problema | 1 semana | Identificación de necesidades, revisión del contexto y definición del problema |
| 2 | Diseño del sistema | 1 semana | Definición de la arquitectura, módulos y estructura del sistema |
| 3 | Desarrollo del prototipo | 3 semanas | Implementación de las funcionalidades principales del sistema |
| 4 | Pruebas del sistema | 1 semana | Validación del funcionamiento y detección de errores |
| 5 | Documentación final | 1 semana | Elaboración del informe y documentación técnica del sistema |

---

# PRESUPUESTO

El presupuesto del proyecto considera principalmente los recursos necesarios para el desarrollo e implementación del sistema. Al tratarse de un proyecto académico con uso de tecnologías accesibles, los costos se mantienen relativamente bajos.

Los principales componentes del presupuesto incluyen:

- **Recursos humanos:** tiempo invertido en el desarrollo, análisis y pruebas del sistema  
- **Herramientas tecnológicas:** software de desarrollo, editores de código y plataformas de apoyo  
- **Servicios en la nube (opcional):** uso de servidores o APIs de inteligencia artificial  
- **Infraestructura básica:** equipos de cómputo y conexión a internet  

Una ventaja importante de este proyecto es que puede desarrollarse utilizando herramientas open source, lo que reduce significativamente los costos. En caso de utilizar servicios de inteligencia artificial en la nube, el costo dependerá del nivel de uso, pero en una etapa inicial se puede trabajar con planes gratuitos o de bajo costo.

---

# CONCLUSIONES

El desarrollo de un sistema de documentación de bases de datos apoyado en inteligencia artificial representa una solución eficiente frente a los problemas tradicionales de documentación manual.

A lo largo del proyecto, se ha evidenciado que la automatización del análisis y la generación de documentación permite mejorar significativamente la comprensión de la estructura de una base de datos, facilitando su mantenimiento y reduciendo el riesgo de errores.

Asimismo, la incorporación de un análisis de auditoría aporta un valor adicional, ya que no solo se limita a describir la base de datos, sino que también permite identificar fallas, inconsistencias y oportunidades de mejora.

En conjunto, el sistema propuesto no solo optimiza el proceso de documentación, sino que también contribuye a mejorar la calidad del diseño de bases de datos, convirtiéndose en una herramienta útil tanto en el ámbito académico como en el profesional.

---

# RECOMENDACIONES

Para asegurar el correcto funcionamiento y evolución del sistema, se plantean las siguientes recomendaciones:

- Validar los resultados generados por el sistema, especialmente en casos donde la estructura de la base de datos sea compleja o poco organizada  
- Mejorar continuamente el modelo de inteligencia artificial para obtener análisis más precisos y detallados  
- Ampliar la compatibilidad del sistema para soportar diferentes motores de bases de datos (por ejemplo, NoSQL además de relacionales)  
- Implementar mejoras en la interfaz de usuario para facilitar la interpretación de los resultados  
- Considerar la integración de visualizaciones gráficas, como diagramas entidad-relación generados automáticamente  
- Realizar pruebas con bases de datos reales para evaluar el desempeño del sistema en escenarios más complejos  
