# ÍNDICE GENERAL

1. [Introducción](#1-introducción)  
   - [1.1 Propósito (Diagrama 4+1)](#11-propósito-diagrama-41)  
   - [1.2 Alcance](#12-alcance)  
   - [1.3 Definición, siglas y abreviaturas](#13-definición-siglas-y-abreviaturas)  
   - [1.4 Organización del documento](#14-organización-del-documento)  

2. [Objetivos y Restricciones Arquitectónicas](#2-objetivos-y-restricciones-arquitectónicas)  
   - [2.1 Priorización de requerimientos](#21-priorización-de-requerimientos)  
   - [2.2 Requerimientos Funcionales](#22-requerimientos-funcionales)  
   - [2.3 Requerimientos No Funcionales](#23-requerimientos-no-funcionales--atributos-de-calidad)  
   - [2.4 Restricciones](#24-restricciones)  

3. [Representación de la Arquitectura del Sistema](#3-representación-de-la-arquitectura-del-sistema)  
   - [3.1 Vista de Caso de Uso](#31-vista-de-caso-de-uso)  
   - [3.1.1 Diagramas de Casos de Uso](#311-diagramas-de-casos-de-uso)  
   - [3.2 Vista Lógica](#32-vista-lógica)  
   - [3.2.1 Diagrama de Subsistemas](#321-diagrama-de-subsistemas-paquetes)  
   - [3.2.2 Diagrama de Secuencia](#322-diagrama-de-secuencia-vista-de-diseño)  
   - [3.2.3 Diagrama de Colaboración](#323-diagrama-de-colaboración-vista-de-diseño)  
   - [3.2.4 Diagrama de Objetos](#324-diagrama-de-objetos)  
   - [3.2.5 Diagrama de Clases](#325-diagrama-de-clases)  
   - [3.2.6 Diagrama de Base de Datos](#326-diagrama-de-base-de-datos-relacional-o-no-relacional)  
   - [3.3 Vista de Implementación](#33-vista-de-implementación-vista-de-desarrollo)  
   - [3.3.1 Arquitectura Software](#331-diagrama-de-arquitectura-software-paquetes)  
   - [3.3.2 Diagrama de Componentes](#332-diagrama-de-arquitectura-del-sistema-diagrama-de-componentes)  
   - [3.4 Vista de Procesos](#34-vista-de-procesos)  
   - [3.4.1 Diagrama de Actividad](#341-diagrama-de-procesos-del-sistema-diagrama-de-actividad)  
   - [3.5 Vista de Despliegue](#35-vista-de-despliegue-vista-física)  
   - [3.5.1 Diagrama de Despliegue](#351-diagrama-de-despliegue)  

4. [Atributos de Calidad del Software](#4-atributos-de-calidad-del-software)  

---

# 1 Introducción

## 1.1 Propósito (Diagrama 4+1)

El presente documento tiene como propósito describir la arquitectura del sistema de documentación inteligente de bases de datos basado en inteligencia artificial, proporcionando una visión global de su diseño, estructura y funcionamiento.

El sistema está orientado a automatizar la generación de documentación técnica, análisis estructural y auditoría de bases de datos, permitiendo identificar relaciones, inconsistencias y oportunidades de mejora. Se consideran tanto los requisitos funcionales como no funcionales, priorizando aspectos como la eficiencia en el procesamiento de datos, la escalabilidad del sistema y la facilidad de uso.

Se adopta el modelo arquitectónico 4+1 para representar las distintas perspectivas del sistema, permitiendo una comprensión integral desde el punto de vista lógico, de desarrollo, procesos y despliegue.

## 1.2 Alcance

El documento abarca la definición de la arquitectura del sistema enfocado en la generación automatizada de documentación de bases de datos mediante inteligencia artificial.

Se incluye el diseño lógico del sistema, la interacción entre sus componentes principales, así como los mecanismos de análisis de datos y generación de reportes. Se consideran las vistas más relevantes del modelo 4+1, omitiendo detalles excesivamente técnicos que no aporten valor al entendimiento general del sistema.

## 1.3 Definición, siglas y abreviaturas

- IA: Inteligencia Artificial  
- BD: Base de Datos  
- SRS: Especificación de Requisitos de Software  
- SAD: Documento de Arquitectura de Software  
- API: Interfaz de Programación de Aplicaciones  
- ER: Modelo Entidad-Relación  
- SQL: Lenguaje de Consulta Estructurado  

## 1.4 Organización del documento

El documento se encuentra estructurado en secciones que describen los objetivos del sistema, sus restricciones, la representación arquitectónica mediante distintas vistas y los atributos de calidad del software. Cada sección permite comprender el sistema desde diferentes perspectivas, facilitando su análisis, desarrollo e implementación.

---

# 2 Objetivos y Restricciones Arquitectónicas

## 2.1 Priorización de requerimientos

| ID | Descripción | Prioridad |
|----|------------|----------|
| RQ01 | Generar documentación automática de bases de datos | Alta |
| RQ02 | Analizar relaciones entre tablas | Alta |
| RQ03 | Detectar errores de diseño | Alta |
| RQ04 | Generar recomendaciones de optimización | Media |
| RQ05 | Exportar documentación en formatos estándar | Media |

## 2.2 Requerimientos Funcionales

| ID | Descripción | Prioridad |
|----|------------|----------|
| RF01 | Importar estructura de base de datos | Alta |
| RF02 | Generar diccionario de datos | Alta |
| RF03 | Identificar claves primarias y foráneas | Alta |
| RF04 | Analizar integridad referencial | Alta |
| RF05 | Generar reportes técnicos | Media |

## 2.3 Requerimientos No Funcionales – Atributos de Calidad

| ID | Descripción | Prioridad |
|----|------------|----------|
| RNF01 | Tiempo de respuesta eficiente | Alta |
| RNF02 | Escalabilidad del sistema | Alta |
| RNF03 | Seguridad de los datos | Alta |
| RNF04 | Usabilidad de la interfaz | Media |
| RNF05 | Mantenibilidad del sistema | Media |

## 2.4 Restricciones

- Dependencia de modelos de inteligencia artificial para el análisis  
- Necesidad de conexión a internet para procesamiento avanzado  
- Compatibilidad con motores de base de datos específicos (MySQL, PostgreSQL)  
- Limitaciones en el análisis si la base de datos está incompleta o mal estructurada  

---

# 3 Representación de la Arquitectura del Sistema

## 3.1 Vista de Caso de Uso

Esta vista permite entender cómo interactúan los usuarios con el sistema y cuáles son las funciones principales que este ofrece.

El sistema está pensado para que el usuario pueda cargar o conectarse a una base de datos, analizar su estructura y, a partir de eso, generar automáticamente una documentación completa junto con un informe que evalúe el estado de la base de datos.

### Actores

- Usuario (desarrollador o analista)  
- Sistema de IA  

### Casos de uso principales

- Cargar o conectar una base de datos  
- Analizar la estructura de la base de datos  
- Identificar relaciones entre tablas  
- Generar documentación automática  
- Obtener un reporte de auditoría  
- Exportar los resultados  

## 3.1.1 Diagramas de Casos de Uso

Los diagramas permiten representar de forma más clara cómo el usuario interactúa con el sistema. A través de distintos escenarios, se puede ver el flujo desde que se carga la base de datos hasta que se obtiene la documentación final.

Estos diagramas ayudan a validar que el sistema cumple con lo que se espera y permiten detectar posibles mejoras en el proceso.

---

## 3.2 Vista Lógica

En esta vista se muestra cómo está organizado el sistema internamente. Para hacerlo más claro, el sistema se divide en módulos, donde cada uno cumple una función específica.

### Módulos principales

- Módulo de entrada de datos  
- Módulo de análisis estructural  
- Módulo de inteligencia artificial  
- Módulo de documentación  
- Módulo de reportes  

## 3.2.1 Diagrama de Subsistemas (paquetes)

- Data Input  
- Data Analyzer  
- AI Engine  
- Documentation Generator  
- Report Manager  

## 3.2.2 Diagrama de Secuencia (vista de diseño)

El proceso inicia cuando el usuario carga una base de datos, pasa por análisis estructural, luego por inteligencia artificial y finalmente genera documentación y reportes.

## 3.2.3 Diagrama de Colaboración (vista de diseño)

- Diagrama de secuencia: flujo del proceso  
- Diagrama de colaboración: interacción de módulos  
- Diagrama de objetos  
- Diagrama de clases  

## 3.2.4 Diagrama de Objetos

Incluye:

- Tablas (Usuario, Producto, Pedido)  
- Columnas  
- Relaciones (claves primarias y foráneas)  

## 3.2.5 Diagrama de Clases

Clases principales:

- BaseDeDatos  
- Tabla  
- Columna  
- Relacion  
- Analizador  
- GeneradorDocumentacion  
- MotorIA  

## 3.2.6 Diagrama de Base de Datos (relacional o no relacional)

Analiza:

- Tablas  
- Campos  
- Claves primarias  
- Claves foráneas  
- Relaciones  

---

## 3.3 Vista de Implementación (vista de desarrollo)

### Capas

- Capa de presentación  
- Capa lógica  
- Capa de datos  
- Capa de inteligencia artificial  

## 3.3.1 Diagrama de arquitectura software (paquetes)

Sistema modular con separación de responsabilidades.

## 3.3.2 Diagrama de arquitectura del sistema (Diagrama de componentes)

Incluye:

- Frontend  
- Backend API  
- Motor de análisis  
- Servicio de IA  
- Base de datos  

---

## 3.4 Vista de Procesos

Describe cómo funciona el sistema internamente.

## 3.4.1 Diagrama de Procesos del sistema (diagrama de actividad)

Flujo:

- Recepción de la base de datos  
- Validación de la estructura  
- Análisis  
- Procesamiento IA  
- Generación de documentación  
- Generación de auditoría  
- Presentación de resultados  

---

## 3.5 Vista de Despliegue (vista física)

Arquitectura cliente-servidor.

## 3.5.1 Diagrama de despliegue

Incluye:

- Cliente (navegador web)  
- Servidor de aplicaciones  
- Servicio de IA  
- Base de datos  

---

# 4 Atributos de Calidad del Software

## Escenario de Funcionalidad

El sistema cumple con su objetivo principal de análisis y documentación automática, incluyendo recomendaciones.

## Escenario de Usabilidad

Interfaz clara y fácil de usar.

## Escenario de Confiabilidad

Resultados consistentes y seguros.

## Escenario de Rendimiento

Procesamiento eficiente incluso con grandes volúmenes.

## Escenario de Mantenibilidad

Sistema modular que permite mejoras.

## Otros Escenarios

Soporta múltiples solicitudes simultáneamente.

---
