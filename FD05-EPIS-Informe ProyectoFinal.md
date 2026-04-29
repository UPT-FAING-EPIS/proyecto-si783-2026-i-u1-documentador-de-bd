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

El sistema desarrollado es una aplicación web completa que permite el análisis y documentación automatizada de bases de datos. La arquitectura del sistema se basa en una estructura cliente-servidor, donde el backend procesa la información y el frontend proporciona una interfaz intuitiva para el usuario.

## Arquitectura del Sistema

La arquitectura implementada sigue el patrón MVC (Modelo-Vista-Controlador) con los siguientes componentes principales:

### Backend (Node.js + Express)
- **Servidor principal:** Maneja las rutas HTTP y coordina las operaciones
- **Módulo de parsing:** Procesa archivos SQL, JSON y otros formatos para extraer metadatos
- **Integración con IA:** Utiliza la API de OpenAI para generar análisis y documentación
- **Sistema de archivos:** Gestiona la subida y almacenamiento temporal de archivos

### Frontend (HTML + CSS + JavaScript)
- **Interfaz de carga:** Permite subir archivos de base de datos con validación
- **Visualización de resultados:** Muestra documentación, diagramas y análisis
- **Controles interactivos:** Navegación por diferentes vistas (documentación, diagrama, conversor)

### Tecnologías de Soporte
- **Mermaid.js:** Generación de diagramas entidad-relación
- **Marked.js:** Renderizado de contenido Markdown
- **Multer:** Manejo de archivos multipart
- **XLSX:** Procesamiento de archivos Excel (opcional)

## Funcionalidades Implementadas

1. **Análisis de Estructura:** Extrae tablas, columnas, tipos de datos, claves primarias y foráneas
2. **Generación de Documentación:** Crea diccionarios de datos detallados con descripciones generadas por IA
3. **Diagramas ER:** Visualiza relaciones entre entidades de forma gráfica
4. **Auditoría de Calidad:** Identifica problemas de diseño y propone mejoras
5. **Conversión de Esquemas:** Transforma estructuras a diferentes formatos (MongoDB, Prisma, etc.)

## Proceso de Funcionamiento

1. El usuario sube un archivo de base de datos (SQL, JSON, etc.)
2. El sistema parsea el archivo y extrae la estructura
3. Se envía la información a la API de OpenAI para análisis
4. Se generan documentación, diagramas y recomendaciones
5. Los resultados se presentan en la interfaz web

---

# ANÁLISIS DE FACTIBILIDAD

## Factibilidad Técnica

El proyecto es completamente viable desde el punto de vista técnico. Se utilizaron tecnologías maduras y bien documentadas:

- **Node.js:** Plataforma robusta para desarrollo backend
- **Express.js:** Framework ligero y flexible para APIs REST
- **OpenAI API:** Servicio de IA accesible y potente
- **Tecnologías web estándar:** HTML5, CSS3, JavaScript ES6+

La integración entre componentes se realizó sin dificultades mayores, y el sistema demuestra estabilidad en pruebas realizadas.

## Factibilidad Económica

Los costos se mantuvieron muy bajos gracias al uso de tecnologías gratuitas:

- **Desarrollo:** Recursos propios de los estudiantes
- **Hosting:** Posibilidad de deployment gratuito en plataformas como Vercel o Heroku
- **APIs:** Uso de OpenAI con créditos gratuitos iniciales
- **Herramientas:** Editores de código gratuitos (VS Code)

El ROI del proyecto es altamente positivo, ya que el sistema desarrollado puede ser reutilizado múltiples veces sin costos adicionales significativos.

## Factibilidad Operativa

El sistema es extremadamente fácil de operar:

- **Interfaz intuitiva:** No requiere capacitación especial
- **Automatización completa:** Procesa archivos con un clic
- **Resultados claros:** Presenta información de forma organizada
- **Compatibilidad amplia:** Funciona en cualquier navegador moderno

## Factibilidad Social

El proyecto tiene un impacto social positivo al:

- Democratizar el acceso a herramientas de análisis de bases de datos
- Facilitar el aprendizaje de conceptos de bases de datos
- Mejorar la calidad del desarrollo de software
- Promover el uso de documentación técnica

## Factibilidad Legal

Se respetaron todas las normativas legales:

- Uso de APIs con términos de servicio aceptados
- No se almacenan datos sensibles de usuarios
- Código desarrollado con licencias open source
- Respeto a derechos de propiedad intelectual

## Factibilidad Ambiental

Contribuye al medio ambiente mediante:

- Reducción del uso de papel en documentación
- Procesamiento digital eficiente
- Minimización de recursos físicos necesarios

---

# TECNOLOGÍA DE DESARROLLO

## Stack Tecnológico

### Backend
- **Node.js 18+:** Entorno de ejecución JavaScript del lado servidor
- **Express.js 4.18:** Framework web minimalista para Node.js
- **Multer 1.4:** Middleware para manejo de archivos multipart/form-data
- **OpenAI 4.20:** SDK oficial para integración con modelos de IA
- **XLSX 0.18:** Librería para procesamiento de archivos Excel
- **CORS 2.8:** Middleware para habilitar Cross-Origin Resource Sharing

### Frontend
- **HTML5:** Estructura semántica de la aplicación
- **CSS3:** Estilos modernos con diseño glassmorphism
- **JavaScript ES6+:** Lógica del cliente con async/await
- **Mermaid.js:** Generación de diagramas entidad-relación
- **Marked.js:** Conversión de Markdown a HTML

### Infraestructura
- **Sistema operativo:** Linux (Ubuntu/Debian) para desarrollo y producción
- **Control de versiones:** Git para gestión del código fuente
- **Editor:** Visual Studio Code con extensiones especializadas

## Entorno de Desarrollo

- **Node Version Manager (NVM):** Gestión de versiones de Node.js
- **NPM/Yarn:** Gestión de dependencias
- **ESLint:** Linting y formateo de código
- **Git:** Control de versiones distribuido
- **Postman:** Pruebas de API (opcional)

---

# METODOLOGÍA DE IMPLEMENTACIÓN

Se utilizó una metodología híbrida que combina elementos de desarrollo ágil con prácticas tradicionales de documentación:

## Fases del Desarrollo

### 1. Planificación y Análisis
- Definición de requisitos funcionales y no funcionales
- Análisis de tecnologías disponibles
- Diseño de la arquitectura del sistema

### 2. Diseño del Sistema
- Modelado de la interfaz de usuario
- Diseño de la API REST
- Definición de estructuras de datos

### 3. Implementación
- Desarrollo modular por componentes
- Integración continua de funcionalidades
- Pruebas unitarias y de integración

### 4. Pruebas y Validación
- Pruebas funcionales con datos de ejemplo
- Validación de casos edge
- Optimización de rendimiento

### 5. Documentación y Despliegue
- Elaboración de documentación técnica
- Preparación para deployment
- Creación de manuales de usuario

## Control de Calidad

- **Code Reviews:** Revisión de código entre pares
- **Testing:** Validación con archivos de ejemplo reales
- **Linting:** Mantenimiento de estándares de código
- **Versionado:** Control de versiones con Git

---

# CRONOGRAMA

| Semana | Fase | Actividades Principales | Estado |
|--------|------|-------------------------|--------|
| 1 | Inicio | Análisis de requisitos, diseño inicial | ✅ Completado |
| 2 | Desarrollo Backend | Configuración servidor, parsing básico | ✅ Completado |
| 3 | Desarrollo Backend | Integración OpenAI, API completa | ✅ Completado |
| 4 | Desarrollo Frontend | Interfaz básica, subida de archivos | ✅ Completado |
| 5 | Desarrollo Frontend | Visualización resultados, diagramas | ✅ Completado |
| 6 | Integración | Unión backend-frontend, pruebas | ✅ Completado |
| 7 | Testing | Validación completa, corrección errores | ✅ Completado |
| 8 | Documentación | Informes finales, preparación entrega | ✅ Completado |

**Duración total:** 8 semanas
**Horas dedicadas:** ~120 horas
**Estado del proyecto:** 100% completado

---

# PRESUPUESTO

## Costos Detallados

### Costos de Desarrollo
| Concepto | Descripción | Costo (S/.) |
|----------|-------------|-------------|
| Recursos Humanos | 120 horas de desarrollo a S/ 25/hora | 3,000 |
| Software | Licencias y herramientas | 200 |
| API OpenAI | Créditos para pruebas | 150 |
| Hosting | Despliegue inicial | 100 |

### Costos Operativos
| Concepto | Descripción | Costo (S/.) |
|----------|-------------|-------------|
| Internet | Conexión durante desarrollo | 80 |
| Energía | Consumo equipos | 50 |
| Materiales | Papel, impresiones | 50 |

### Costos Totales
- **Costo de Desarrollo:** S/ 3,450
- **Costo Operativo:** S/ 180
- **Contingencia (10%):** S/ 363
- **Total General:** S/ 3,993

## Justificación de Costos

Los costos se mantuvieron mínimos gracias a:
- Uso de tecnologías open source gratuitas
- Desarrollo con recursos propios
- Créditos gratuitos iniciales de OpenAI
- Infraestructura académica disponible

---

# CONCLUSIONES

El desarrollo del Sistema de Documentación de Bases de Datos ha sido exitoso y cumple con todos los objetivos planteados inicialmente. El sistema implementado demuestra la viabilidad de utilizar inteligencia artificial para automatizar tareas complejas de análisis y documentación de bases de datos.

## Logros Alcanzados

1. **Funcionalidad Completa:** El sistema procesa archivos de bases de datos y genera documentación técnica detallada
2. **Integración con IA:** La incorporación de OpenAI permite análisis inteligentes y recomendaciones
3. **Interfaz Moderna:** La aplicación web es intuitiva y visualmente atractiva
4. **Arquitectura Robusta:** El código está bien estructurado y es mantenible

## Impacto del Proyecto

- **Académico:** Demuestra aplicación práctica de conceptos de bases de datos
- **Profesional:** Proporciona herramienta útil para desarrolladores
- **Tecnológico:** Muestra potencial de la IA en tareas de desarrollo

## Lecciones Aprendidas

- La importancia de la planificación detallada en proyectos con IA
- La necesidad de manejar errores en APIs externas
- El valor de interfaces de usuario intuitivas
- La importancia de la documentación técnica

El proyecto no solo cumple con los requisitos del curso, sino que también genera un producto funcional que puede ser extendido y mejorado en el futuro.

---

# RECOMENDACIONES

## Para Futuras Versiones

1. **Ampliación de Formatos:** Soporte para más tipos de archivos (YAML, XML, CSV avanzado)
2. **Conexión Directa a BD:** Implementar conexión segura a bases de datos reales
3. **Análisis Avanzado:** Incluir métricas de rendimiento y optimización
4. **Colaboración:** Funcionalidades multi-usuario para equipos
5. **Internacionalización:** Soporte para múltiples idiomas

## Para Usuarios

1. Validar siempre los resultados generados por IA
2. Utilizar el sistema como complemento, no reemplazo, del análisis humano
3. Mantener backups de archivos originales antes del procesamiento
4. Reportar cualquier anomalía detectada para mejoras continuas

## Para la Comunidad Académica

1. Utilizar el proyecto como base para investigaciones en IA aplicada
2. Extender el sistema para otros dominios (análisis de código, documentación de APIs)
3. Compartir el código fuente para fomentar el aprendizaje colaborativo

Este proyecto representa un paso importante en la aplicación de tecnologías emergentes para resolver problemas tradicionales en el desarrollo de software, y sienta las bases para futuras innovaciones en el campo.  
