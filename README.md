# 🧪 QA Testing Manual & Gestión de Defectos — Talento Lab Consultora

Documentación del ciclo de pruebas de **Aseguramiento de Calidad (QA)** realizado sobre la plataforma web de la consultora **Talento Lab**, bajo metodología **Agile/Scrum** gestionada en **Jira Software**.

---

### 🔗 Enlaces del Proyecto

* 🌐 **Sitio Web Testeado (SUT):** [talentolab-test.netlify.app](https://talentolab-test.netlify.app/)
* 📋 **Tablero de Gestión y Backlog en Jira:** [Talento Lab Scrum Board](https://talento-lab-2026-jimenasr.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog?atlOrigin=eyJpIjoiMGY5MzU3OGQ5N2M0NDE3MWEwMWI0MTExOGZkZWUwODYiLCJwIjoiaiJ9)

---

### 📊 Resumen Ejecutivo y Métricas del Sprint #1

* **Tester Responsable:** Jimena Ruiz
* **Fechas de Ejecución:** Sprint #1
* **Casos de Prueba Diseñados:** 12 casos
* **Casos Ejecutados:** 8 casos (66% Cobertura)
* **Resultado de Pruebas:** 5 Exitosos | 3 Fallidos
* **Defectos Detectados:** 7 Bugs (3 Críticos, 2 Medios, 2 Leves)
* **Dictamen Final de Calidad:** 🔴 **NO APROBADO PARA PRODUCCIÓN** (Debido a fallos críticos de comunicación en el formulario de servicios).

---

### 🎯 Alcance de las Pruebas por Funcionalidad

1. **F1 - Filtros de Búsqueda:** Validación de selección por categoría tecnológica (ej. *QA Manual*) y restablecimiento de filtros sin recarga de página.
2. **F2 - Detalle de Vacante y Postulación:** Comprobación del flujo de lectura de requisitos y habilitación de postulación con restricción de CV previo.
3. **F3 - Formulario de Contacto (Empresas):** Validación de datos corporativos, formato de correo electrónico y envío de solicitudes de presupuesto.
4. **F4 - Selección de Servicios Especializados:** Verificación de selección múltiple (Headhunting, Evaluación de candidatos) y tooltips explicativos.

---

### 🐛 Principales Hallazgos (Bug Reports)

* **BR-01 (Severidad: Muy Alta / Prioridad: Muy Alta):** Error *"unexpected token"* al intentar enviar el formulario de contacto, provocando el bloqueo del procesamiento del mensaje en el servidor.
* **BR-02 (Severidad: Media / Prioridad: Baja):** Botón *"Postularse"* habilitado para usuarios invitados/no registrados, redirigiendo al registro sin aviso previo.
* **BR-03 (Severidad: Muy Alta / Prioridad: Alta):** Bloqueo total del envío de solicitudes de servicios debido a la falla en la API/servidor del formulario de contacto.

---

### 📑 Documentación Adjunta en el Repositorio

En este repositorio se encuentran disponibles las planillas detalladas con toda la trazabilidad del proceso:
* 📊 **Planilla de Casos de Prueba, Cobertura y Métricas (Excel):** `QATalentoLab_Jimena Ruiz.xlsx`

---

### 🛠️ Herramientas y Metodologías

* **Gestión de Proyecto & User Stories:** Jira Software (Agile / Scrum Framework)
* **Diseño y Ejecución de Pruebas:** Black Box Testing, pruebas funcionales, de UI/UX y validación de errores.
* **Seguimiento de Defectos:** Bug Reporting estandarizado con severidad, prioridad y evidencia.
* **Documentación & Métricas:** Microsoft Excel / PDF.

---

### 👩‍💻 Autora

* **Jimena Soledad Ruiz** — *QA Tester / Frontend Developer*
* LinkedIn: [linkedin.com/in/jimena-soledad-ruiz-b5621524](https://www.linkedin.com/in/jimena-soledad-ruiz-b5621524)
* GitHub: [github.com/J-code-bit](https://github.com/J-code-bit)
