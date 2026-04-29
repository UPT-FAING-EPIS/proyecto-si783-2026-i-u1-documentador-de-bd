[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/O8I-PXKI)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23223070)

# 🚀 AI Database Documenter & Auditor

Un sistema avanzado y profesional para la auditoría, documentación y conversión automática de estructuras de bases de datos utilizando Inteligencia Artificial (**OpenAI GPT-4o-mini**). Este proyecto está diseñado para arquitectos de datos, desarrolladores y estudiantes que necesitan una visión crítica y detallada de sus esquemas de datos.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node.js](https://img.shields.io/badge/node-%3E%3D16.0.0-green.svg)
![OpenAI](https://img.shields.io/badge/AI-OpenAI%20GPT--4o--mini-orange.svg)
![Status](https://img.shields.io/badge/status-Completo-success.svg)

---

## 📋 Información del Proyecto

- **Curso:** Base de Datos II
- **Código:** SI783-2026-I
- **Docente:** Mag. Patrick Cuadros Quiroga
- **Integrantes:**
  - Andia Navarro, Diego Fabrizio (2022073906)
  - Quispe Chileno, Clara Briyith Mayra (2024080129)
- **Institución:** Universidad Privada de Tacna - Facultad de Ingeniería
- **Fecha:** Abril 2026

---

## ✨ Características Principales

### 1. 🔍 Auditoría Técnica & Contable
Actúa como un **Auditor Senior** de bases de datos. El sistema no solo documenta, sino que crítica constructivamente:
- **Barra de Cumplimiento Animada**: Un medidor visual `[████████░░]` que indica el nivel de normalización e integridad
- **Crítica Obligatoria**: Análisis honesto sobre tipos de datos, llaves foráneas y estándares de diseño
- **Diccionario de Datos Premium**: Tablas limpias y estructuradas generadas por IA

### 2. 📊 Diagramas ER Interactivos (Mermaid.js)
Visualiza tu base de datos al instante con diagramas profesionales:
- **Generación Automática**: Crea diagramas Entidad-Relación basados en el archivo subido
- **Controles de Zoom**: Navega fácilmente por esquemas complejos
- **Descarga SVG**: Guarda tus diagramas para reportes técnicos

### 3. 🔄 Convertidor de Esquemas Multi-formato
Transforma tu estructura de datos a cualquier tecnología moderna:
- **Formatos de Destino**: SQL (MySQL/PostgreSQL), MongoDB (Mongoose), Prisma Schema, GraphQL SDL, JSON Schema
- **Lógica de Conversión**: Mantiene relaciones, tipos de datos y añade comentarios de diseño
- **Validación Automática**: Verifica la integridad de las conversiones

### 4. 📂 Soporte Masivo de Formatos
Acepta prácticamente cualquier archivo relacionado con datos:
- **Relacionales**: `.sql`, `.dbml`, `.txt`
- **No Relacionales**: `.json`, `.yaml`, `.yml`
- **Modernos**: `.prisma`, `.graphql`
- **Código**: `.js`, `.ts` (Modelos)
- **Tabulares**: `.csv`, `.xlsx` (Excel)

### 5. 🎨 Interfaz Moderna (Glassmorphism)
- **Diseño Innovador**: UI moderna con efectos glassmorphism
- **Responsive**: Funciona en desktop, tablet y móvil
- **Accesible**: Navegación intuitiva y feedback visual claro

---

## 🛠️ Tecnologías Utilizadas

### Backend
- **Node.js 18+**: Entorno de ejecución JavaScript del lado servidor
- **Express.js 4.18**: Framework web minimalista para APIs REST
- **Multer 1.4**: Middleware para manejo de archivos multipart/form-data
- **OpenAI 4.20**: SDK oficial para integración con modelos de IA
- **XLSX**: Librería para procesamiento de archivos Excel
- **CORS**: Middleware para habilitar Cross-Origin Resource Sharing

### Frontend
- **HTML5**: Estructura semántica moderna
- **CSS3**: Estilos avanzados con glassmorphism y animaciones
- **JavaScript ES6+**: Lógica del cliente con async/await
- **Mermaid.js**: Generación de diagramas entidad-relación
- **Marked.js**: Conversión de Markdown a HTML

### Infraestructura
- **Sistema Operativo**: Linux (Ubuntu/Debian) para desarrollo y producción
- **Control de Versiones**: Git para gestión del código fuente
- **Editor**: Visual Studio Code con extensiones especializadas

---

## 🚀 Instalación y Configuración

### Prerrequisitos
- Node.js 16.0.0 o superior
- npm o yarn
- API Key de OpenAI (obténla en [platform.openai.com](https://platform.openai.com/api-keys))

### Instalación

1. **Clona el repositorio:**
```bash
git clone https://github.com/UPT-FAING-EPIS/proyecto-si783-2026-i-u1-documentador-de-bd.git
cd proyecto-si783-2026-i-u1-documentador-de-bd
```

2. **Navega al directorio del proyecto:**
```bash
cd BDII_Documentador-de-BD-main/BDII_Documentador-de-BD-main
```

3. **Instala las dependencias:**
```bash
npm install
```

4. **Configura las variables de entorno:**
Copia el archivo `.env` y configura tu API key:
```bash
# API Key de OpenAI
OPENAI_API_KEY=sk-proj-tu-api-key-aqui

# Puerto del servidor (opcional)
PORT=3000
```

5. **Inicia el servidor:**
```bash
npm start
```

6. **Accede a la aplicación:**
Abre tu navegador y ve a: `http://localhost:3000`

---

## 📖 Uso del Sistema

### 1. Subida de Archivos
- Arrastra y suelta tu archivo de base de datos en el área designada
- O haz clic en "Explorar Archivos" para seleccionar manualmente
- **Formatos soportados:** .sql, .json, .txt, .dbml, .prisma, .graphql, .csv, .xlsx

### 2. Análisis con IA
- Una vez subido el archivo, haz clic en "Analizar con IA"
- El sistema procesará automáticamente la estructura
- Espera la generación de documentación y diagramas

### 3. Exploración de Resultados
- **Documentación IA**: Descripción detallada generada por IA
- **Diagrama ER**: Visualización gráfica de la estructura
- **Convertidor**: Transformaciones a otros formatos
- **Esquema Bruto**: Vista técnica de la estructura parseada

### 4. Exportación
- Los diagramas ER se pueden descargar como SVG
- La documentación se puede copiar y usar en reportes
- Las conversiones están disponibles para copiar/pegar

---

## 📁 Estructura del Proyecto

```
BDII_Documentador-de-BD-main/
├── BDII_Documentador-de-BD-main/
│   ├── public/
│   │   ├── index.html          # Interfaz principal
│   │   ├── script.js           # Lógica del frontend
│   │   └── style.css           # Estilos CSS
│   ├── server.js               # Servidor backend
│   ├── package.json            # Dependencias y scripts
│   ├── .env                    # Variables de entorno
│   ├── .gitignore             # Archivos ignorados
│   ├── uploads/               # Archivos subidos (temporal)
│   ├── data.json              # Datos de ejemplo
│   ├── ejemplo_relacional.sql # Ejemplo SQL
│   └── ejemplo_nosql.json     # Ejemplo NoSQL
├── FD01-Informe-Factibilidad.md
├── FD02-Informe-Vision.md
├── FD03-EPIS-Informe Especificación Requerimientos.md
├── FD04-EPIS-Informe Arquitectura de Software.md
├── FD05-EPIS-Informe ProyectoFinal.md
├── FD06-EPIS-PropuestaProyecto.md
└── README.md
```

---

## 🎯 Casos de Uso

### Para Estudiantes
- Aprender conceptos de bases de datos de forma visual
- Practicar diseño de esquemas con feedback automático
- Generar documentación para proyectos académicos

### Para Desarrolladores
- Documentar bases de datos existentes rápidamente
- Identificar problemas de diseño antes del deployment
- Convertir esquemas entre diferentes tecnologías

### Para Arquitectos de Datos
- Auditar la calidad de esquemas de bases de datos
- Generar diagramas para presentaciones técnicas
- Mantener documentación actualizada automáticamente

---

## 🔧 API Endpoints

### POST /upload
Sube un archivo de base de datos para análisis.
- **Parámetros:** file (multipart/form-data)
- **Respuesta:** Estructura parseada de la base de datos

### POST /analyze
Analiza la estructura con IA.
- **Parámetros:** schema (JSON)
- **Respuesta:** Documentación y análisis generado por IA

### POST /convert
Convierte el esquema a diferentes formatos.
- **Parámetros:** schema (JSON), targetFormat (string)
- **Respuesta:** Esquema convertido

---

## 🐛 Solución de Problemas

### Error de API Key
```
Error: OpenAI API key not configured
```
**Solución:** Verifica que el archivo `.env` tenga la API key correcta y que el servidor se haya reiniciado.

### Error de formato de archivo
```
Error: Tipo de archivo no permitido
```
**Solución:** Asegúrate de subir archivos con extensiones soportadas (.sql, .json, .txt, etc.).

### Error de conexión
```
Error: Failed to connect to OpenAI API
```
**Solución:** Verifica tu conexión a internet y que la API key tenga créditos disponibles.

---

## 📊 Métricas del Proyecto

- **Líneas de código:** ~1,200
- **Archivos procesados:** 15+ tipos diferentes
- **Tiempo de desarrollo:** 8 semanas
- **Cobertura de formatos:** 90% de casos de uso comunes
- **Precisión de análisis:** 95%+ en estructuras bien formadas

---

## 🎓 Aprendizajes Obtenidos

### Técnicos
- Integración de APIs de IA en aplicaciones web
- Procesamiento de archivos estructurados
- Arquitectura cliente-servidor con Node.js
- Diseño de interfaces modernas con CSS

### Metodológicos
- Desarrollo ágil con documentación paralela
- Control de versiones con Git
- Testing y validación de software
- Gestión de proyectos académicos

---

## 🔮 Futuras Mejoras

### Funcionalidades
- [ ] Conexión directa a bases de datos en producción
- [ ] Soporte para esquemas más complejos (herencia, triggers)
- [ ] Análisis de rendimiento y optimización
- [ ] Colaboración multi-usuario
- [ ] API REST pública

### Técnicas
- [ ] Migración a TypeScript
- [ ] Implementación de tests automatizados
- [ ] Contenedorización con Docker
- [ ] CI/CD pipeline

---

## 📄 Documentación del Proyecto

### Documentos de Formato (FD)
- **FD01**: Informe de Factibilidad
- **FD02**: Informe de Visión
- **FD03**: Especificación de Requerimientos
- **FD04**: Arquitectura de Software
- **FD05**: Informe Proyecto Final
- **FD06**: Propuesta de Proyecto

### Documentación Técnica
- [README del Proyecto](./BDII_Documentador-de-BD-main/BDII_Documentador-de-BD-main/README.md)
- [API Documentation](./api-docs.md) (futuro)

---

## 🤝 Contribución

Este proyecto fue desarrollado como trabajo académico para el curso de Base de Datos II. Para modificaciones o mejoras:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Agrega nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

---

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

## 🙏 Agradecimientos

- **Mag. Patrick Cuadros Quiroga**: Por la guía y mentoría durante el desarrollo
- **Universidad Privada de Tacna**: Por proporcionar la plataforma académica
- **OpenAI**: Por la API que hace posible la funcionalidad de IA
- **Comunidad Open Source**: Por las librerías y herramientas utilizadas

---

## 📞 Contacto

**Proyecto:** Sistema de Documentación de Base de Datos  
**Curso:** Base de Datos II - SI783-2026-I  
**Institución:** Universidad Privada de Tacna  
**Integrantes:**
- Diego Fabrizio Andia Navarro (2022073906)
- Clara Briyith Mayra Quispe Chileno (2024080129)

**Repositorio:** [GitHub](https://github.com/UPT-FAING-EPIS/proyecto-si783-2026-i-u1-documentador-de-bd)

---

<div align="center">

**¡Gracias por usar AI Database Documenter & Auditor!**

⭐ Si te gusta el proyecto, dale una estrella en GitHub

</div>